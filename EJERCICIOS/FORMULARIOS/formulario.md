    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>formularios</title>
        <!-- los uso de los formularios son los siguientes: -->
        <!-- + recibirlos por correo electronico -->
        <!-- + modificar mi pagina web -->
        <!-- + mandar los datos a una base de datos -->
    </head>
    <body>
        <h1>FORMULARIO DE TAQUERIA</h1>
        <h2>MENU</h2>
        <h3>TACOS</h3>
        <ul>
            <li>bisteck................15 pesos</li>
            <li>suadero...............15 pesos</li>
            <li>longaniza............15 pesos</li>
            <li>campechano........15 pesos</li>
            <li>lengua...............15 pesos</li>
        </ul>

            <h3>ESPECIALIDADES</h3>
            <dl>
                <dt>combinadods de bisteck..............25 pesos</dt>
                <dd>lleva una varidad de carne de res dentro de un mismo taco</dd>

                <dt>volcanes.......................................25 pesos</dt>
                <dd> taco de suadero con queso oaxaca derretido</dd>

                <dt>torta de suadero............................30 pesos</dt>
                <dd>bolillo con suadero adentro</dd>

            </dl>


        <h2>REALIZA TU PEDIDO AQUI</h2>

        <form action="" method="">
        NOMBRE <input type="text" placeholder="Angel Hernandez" maxlength="30" minlength="3" required> <br>  <!-- estr atributo ayudara al usuario para saber como poner su nombre, maxlength es un atributo para en numero maz
        de caracteres, minlength es para el minimo de caracteres, required es un atributo que hace un campo de un formulario obligatorio -->    
        TELEFONO <input type="tel" min="10" max="10" placeholder="5553649270" value="(+52)"> <br> <!-- es para colocar un telefono -->
        CORREO <input type="imail" placeholder="usuario@dominio del correo"> <br>
        <P>ES PARA ENVIO O PARA COMER EN EL LOCAL</P> <input type="radio" value="llevar" name="llevar"> para llevar <br>
        <input type="radio" value="local" name="llevar"> para comer en el local <br>
    <!-- el value me dice que escojio y el name me dice como se llama la pregunta -->
    <p>SI ESCOJES LLEVAR DANOS TU DIRECCION</p> <textarea name="direccion" id="" cols="30" rows="10"></textarea placeholder="calle, numero, colonia, CP, alcaldia"> <br>
        <p>ELIJE TU TACO</p>
        <select name="primera orden" id="">
            <option value="bisteck">bisteck</option>
            <option value="suadero">suadero</option>
            <option value="longaniza">longaniza</option>
            <option value="campechano">campechano</option>
            <option value="lengua">lengua</option>
            <option value="combinados con bisteck">combinados con bisteck</option>
            <option value="volcanes">volcanes</option>
            <option value="torta de suadero">torta de suadero</option>
        </select> 
        CUANTOS <input type="number" min="0" max="50"> <br>
        <h3>ordenes adicionales</h3>
        SALSA ROJA<input type="checkbox" value="salsa roja" name="salsa roja"> <br>
        CEBOLLA PICADA<input type="checkbox" value="cebolla picada" name="cebolla picada"> <br>
        SALSA VERDE<input type="checkbox" value="salsa verde" name="salsa verde"> <br>
        ORDEN DE LIMONES<input type="checkbox" value="orden de limones" name="orden de limones"> <br>
        ORDEN DE AGUACATES<input type="checkbox" value="orden de aguacates" name="orden de aguacates"> <br>

        <p>ELIJE TU TACO</p>
        <select name="segunda orden" id="">
            <option value="bisteck">bisteck</option>
            <option value="suadero">suadero</option>
            <option value="longaniza">longaniza</option>
            <option value="campechano">campechano</option>
            <option value="lengua">lengua</option>
            <option value="combinados con bisteck">combinados con bisteck</option>
            <option value="volcanes">volcanes</option>
            <option value="torta de suadero">torta de suadero</option>
        </select> 
        CUANTOS <input type="number" min="0" max="50"> <br>
        <h3>ordenes adicionales</h3>
        SALSA ROJA<input type="checkbox" value="salsa roja" name="salsa roja"> <br>
        CEBOLLA PICADA<input type="checkbox" value="cebolla picada" name="cebolla picada"> <br>
        SALSA VERDE<input type="checkbox" value="salsa verde" name="salsa verde"> <br>
        ORDEN DE LIMONES<input type="checkbox" value="orden de limones" name="orden de limones"> <br>
        ORDEN DE AGUACATES<input type="checkbox" value="orden de aguacates" name="orden de aguacates"> <br>

       <p>ELIJE TU TACO</p>
        <select name="tercera orden" id="">
            <option value="bisteck">bisteck</option>
            <option value="suadero">suadero</option>
            <option value="longaniza">longaniza</option>
            <option value="campechano">campechano</option>
            <option value="lengua">lengua</option>
            <option value="combinados con bisteck">combinados con bisteck</option>
            <option value="volcanes">volcanes</option>
            <option value="torta de suadero">torta de suadero</option>
        </select> 
        CUANTOS <input type="number" min="0" max="50"> <br>
        <h3>ordenes adicionales</h3>
        SALSA ROJA<input type="checkbox" value="salsa roja" name="salsa roja"> <br>
        CEBOLLA PICADA<input type="checkbox" value="cebolla picada" name="cebolla picada"> <br>
        SALSA VERDE<input type="checkbox" value="salsa verde" name="salsa verde"> <br>
        ORDEN DE LIMONES<input type="checkbox" value="orden de limones" name="orden de limones"> <br>
        ORDEN DE AGUACATES<input type="checkbox" value="orden de aguacates" name="orden de aguacates"> <br>
        PARA CUANDO ES TU ORDEN <input type="date" min="19/11/2022" max="31/12/2022"> <br>
        <input type="submit" value="ordena ya"> <input type="reset" value="reiniciar">
    <!-- el atributo reset es para limpiar la orden y empezar de nuevo -->
    </form>
    <!-- otros caracteristicas de los formatos -->
    <form action="color">
         ESCOJE UN COLOR <input type="color"> <br>
         PASSWORD <input type="password"> <br>
         SELECCIONA EL ARCHIVO QUE QUIERAS ENVIAR <input type="file"> <br>


    </form>
    </body>
    </html>
