<! DOCTYPE html >

< html  lang = " en " >
< cabeza >
    < meta  charset = " UTF-8 " >
    < meta  http-equiv = " X-UA-Compatible " content = " IE = edge " >
    < meta  name = " viewport " content = " width = device-width, initial-scale = 1.0 " >
    < título > PrimeraActividad </ título >
</ cabeza >
< cuerpo >
    < h1  id = " Pagina Web " > </ h1 >
    < script  src = " App.js " > </ script >
</ cuerpo >
</ html >

< html  lang = " en " >
< cabeza >
    < meta  charset = " UTF-8 " >
    < meta  name = " viewport " content = " width = device-width, initial-scale = 1.0 " >
    < título > Nombre de las lineas </ título >

    < estilo >
        cuerpo {
           familia de fuentes : Arial;
        }

        . contenedor {
            pantalla : cuadrícula;
            grid-template-columnas : [ inicio ] 1fr [ linea2 ] 1fr [ linea3 ] 1fr [ destacado-fin ] 1fr [ linea5 ] 1fr [ destacado2-fin ] 1fr [ linea7 ] 1fr [ final ];
            grid-template-rows : [ inicio ] 200px [ linea2 ] 200px [ final ] 200px;
            brecha de cuadrícula : 5px;
            altura : 100vh;  / * Para que el contenido ocupe todo el ancho * /
            
        }

        . item {
            color de fondo : azul claro;
            relleno : 10 px ;
            borde : 1 px rojo sólido;
        }

        . artículo : n-ésimo de tipo ( 1 ) {
            color de fondo : azul;
            / * columna de cuadrícula: 1 / intervalo 3;
            fila de cuadrícula: 1 / tramo 2; * /
            columna-cuadrícula : inicio / destacado-end;
            rejilla-fila : inicio / final;
            
       }

       . item : nth-of-type ( 2 ) {
            color de fondo : amarillo;
           / * columna de cuadrícula: 4 / intervalo 2;
            fila de cuadrícula: 1 / tramo 2; * /
            columna-cuadrícula : destacado-end / destacado2-end;
            rejilla-fila : inicio / final;
       }

       . artículo : n-ésimo de tipo ( 3 ) {
            color de fondo : verde;
            / * columna de cuadrícula: 6 / intervalo 2; * /
            columna-cuadrícula : destacado2-end / final;
       }

    </ estilo >

</ cabeza >
< cuerpo >
    < section  class = " contenedor " >
        < div  class = " item " > elemento n. ° 1 </ div >
        < div  class = " item " > elemento n. ° 2 </ div >
        < div  class = " item " > elemento n. ° 3 </ div >
        < div  class = " item " > elemento # 4 </ div >
        < div  class = " item " > elemento n. ° 5 </ div >
    </ sección >
</ cuerpo >
</ html > |