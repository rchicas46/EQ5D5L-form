<!DOCTYPE html>
<html>
<head>
    <title>Cuestionario EQ-5D-5L</title>
</head>
<body>
    <h2>Cuestionario de Calidad de Vida EQ-5D-5L</h2>
    <form>
        <fieldset>
            <legend>1. Movilidad</legend>
            <label><input type="radio" name="movilidad" value="1"> No tengo problemas para caminar</label><br>
            <label><input type="radio" name="movilidad" value="2"> Tengo algunos problemas para caminar</label><br>
            <label><input type="radio" name="movilidad" value="3"> Tengo problemas moderados para caminar</label><br>
            <label><input type="radio" name="movilidad" value="4"> Tengo problemas graves para caminar</label><br>
            <label><input type="radio" name="movilidad" value="5"> No puedo caminar</label><br>
        </fieldset>

        <fieldset>
            <legend>2. Cuidado Personal</legend>
            <label><input type="radio" name="cuidado_personal" value="1"> No tengo problemas para asearme o vestirme</label><br>
            <label><input type="radio" name="cuidado_personal" value="2"> Tengo algunos problemas para asearme o vestirme</label><br>
            <label><input type="radio" name="cuidado_personal" value="3"> Tengo problemas moderados para asearme o vestirme</label><br>
            <label><input type="radio" name="cuidado_personal" value="4"> Tengo problemas graves para asearme o vestirme</label><br>
            <label><input type="radio" name="cuidado_personal" value="5"> No puedo asearme ni vestirme solo/a</label><br>
        </fieldset>

        <fieldset>
            <legend>3. Actividades Cotidianas</legend>
            <label><input type="radio" name="actividades" value="1"> No tengo problemas para realizar mis actividades diarias</label><br>
            <label><input type="radio" name="actividades" value="2"> Tengo algunos problemas para realizar mis actividades diarias</label><br>
            <label><input type="radio" name="actividades" value="3"> Tengo problemas moderados para realizar mis actividades diarias</label><br>
            <label><input type="radio" name="actividades" value="4"> Tengo problemas graves para realizar mis actividades diarias</label><br>
            <label><input type="radio" name="actividades" value="5"> No puedo realizar mis actividades diarias</label><br>
        </fieldset>

        <fieldset>
            <legend>4. Dolor o Malestar</legend>
            <label><input type="radio" name="dolor" value="1"> No tengo dolor ni malestar</label><br>
            <label><input type="radio" name="dolor" value="2"> Tengo algo de dolor o malestar</label><br>
            <label><input type="radio" name="dolor" value="3"> Tengo dolor o malestar moderado</label><br>
            <label><input type="radio" name="dolor" value="4"> Tengo dolor o malestar intenso</label><br>
            <label><input type="radio" name="dolor" value="5"> Tengo dolor o malestar extremo</label><br>
        </fieldset>

        <fieldset>
            <legend>5. Ansiedad o Depresión</legend>
            <label><input type="radio" name="ansiedad" value="1"> No estoy ansioso ni deprimido</label><br>
            <label><input type="radio" name="ansiedad" value="2"> Estoy un poco ansioso o deprimido</label><br>
            <label><input type="radio" name="ansiedad" value="3"> Estoy moderadamente ansioso o deprimido</label><br>
            <label><input type="radio" name="ansiedad" value="4"> Estoy muy ansioso o deprimido</label><br>
            <label><input type="radio" name="ansiedad" value="5"> Estoy extremadamente ansioso o deprimido</label><br>
        </fieldset>

        <fieldset>
            <legend>6. Escala Visual Analógica (0-100)</legend>
            <label for="vas">Indique su salud actual en una escala de 0 (peor estado de salud imaginable) a 100 (mejor estado de salud imaginable):</label><br>
            <input type="number" id="vas" name="vas" min="0" max="100" step="1"> 
        </fieldset>

        <br>
        <button type="submit">Enviar</button>
    </form>
</body>
</html>
