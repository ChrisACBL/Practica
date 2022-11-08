# Practica
Practica
<!DOCTYPE html> 
<html lang="en">
<head>
    <meta char set="UTF-8">
    <meta http-equiv="X-UL-compatible" content="IEedge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout y rutas</title>
</head>
<body>
    <header>
        <h1> Tacos el jefe, desde 2022</h1>
    </header>
    <section>
    <img src="./C:\Users\Chris Brun\OneDrive\Escritorio" alt="logo tacos el jefe"/>
    <h2>MENU</h2>
    <h2>Tacos Grandes</h2>
    <p>Incluye cilantro</p>
    <ul>
        <li>Bisteck................. Bs. 25</li>
        <li>Chorizo................. Bs. 25</li>
        <li>Chuleta................. Bs. 25</li>
        <li>Campechano.............. Bs. 25</li>
    </ul> 
    <h2>Tacos Pequenos</h2>
    <p>Incluye cebolla</p>
    <ul>
        <li>Bisteck................. Bs. 15</li>
        <li>Chorizo................. Bs. 15</li>
        <li>Chuleta................. Bs. 15</li>
        <li>Campechano.............. Bs. 15</li>
    </ul>
    <h2>Especiales</h2> 
    <p>Incluye cilantro y cebolla</p>
    <p>combo con refresco 5 bs mas</p> 
    <dl>
        <dt><b>Sharpei</b>.......................BS. 30</dt>
        <dd>-Tortilla frita con salsa, rellena de pollo</dd>
        <dt><b>Pastor Aleman</b>.................BS. 30</dt>
        <dd>-tortilla de harina con carne de res y queso</dd>
        <dt><b>Pug</b>...........................BS. 30</dt>
        <dd>-tortilla de maiz con chuleta</dd>
        <dt><b>Adoptado</b>......................BS. 30</dt>
        <dd>-Tortilla de maiz con pastor</dd>
    </dl> 
    </section>

    <hr>
    <section>
    <h2>Ubicacion</h2>
    <h3>SUCURSALES</h3>
    <table>
        <tr>
            <th>Nombre</th>
            <th>Ubicacion</th>
            <th>Horarios</th>
        </tr>
        <tr>
            <td>Este</td>
            <td><a href="https://goo.gl/maps/S4dW3cNcZiezfg7TA"target="_blank">Cochabamba</th></td>
            <td>L - D 24H</td>
        </tr>
        <tr>
            <td>Sur</td>
            <td><a href="https://goo.gl/maps/S4dW3cNcZiezfg7TA"target="_blank">Sacaba</th></td>
            <td>L - D 5pm - 3am</td>
        </tr>
        <tr>
            <td>Norte</td>
            <td><a href="https://goo.gl/maps/S4dW3cNcZiezfg7TA"target="_blank">Quillacollo</th></th>
            <td>M - D 6pm - 12am</td>
        </tr>

    </table>
    </section>

    <hr>
    <section>

    <h2>Pedidos</h2>
    <h3>Haz tu pedido aqui</h3>
        <form action="a">
        <p> De que taqueria quieres?</p>
    <select>
        <option value="Este">Este</option>
        <option value="Sur">Sur</option>
        <option value="Norte">Norte</option>
    </select>
    <p>De que tacos quieres?</p>
    <input type="checkbox" id="Bisteck" name="Bisteck" value="Bisteck">
    <label for="Bisteck">Bisteck</label>
    <input type="number" id="BisteckNumber" name="BisteckNumber"placeholder="Cuantos?">
    <br><br>
    <input type="checkbox" id="Chorizo" name="Chorizo" value="Chorizo">
    <label for="Chorizo">Chorizo</label>
    <input type="number" id="ChorizoNumber" name="ChorizoNumber"placeholder="Cuantos?">
    <br><br>
    <input type="checkbox" id="Pastor" name="Pastor" value="Pastor">
    <label for="Pastor">Pastor</label>
    <input type="number" id="PastorNumber" name="PastorNumber"placeholder="Cuantos?">
    <br><br>
    <input type="checkbox" id="Chuleta" name="Chuleta" value="Chuleta">
    <label for="Chuleta">Bisteck</label>
    <input type="number" id="ChuletaNumber" name="ChuletaNumber"placeholder="Cuantos?">
    <br><br>
    <input type="checkbox" id="Campechano" name="Campechano" value="Campechano">
    <label for="Campechano">Bisteck</label>
    <input type="number" id="CampechanoNumber" name="CampechanoNumber"placeholder="Cuantos?">
    
    <br><br>

    <label for="Nombre">Nombre</label><br>
    <input type="text" id="Nombre" name="Nombre" placeholder="Como te llamas?">
    
    <br><br>

    <label for="Telefono">Telefono</label><br>
    <input type="text" id="Telefono" name="Telefono" placeholder="Como te llamas?">
    
    <br><br>

    <label for="Direccion">Direccion</label><br>
    <input type="text" id="Direccion" name="Direccion" placeholder="Como te llamas?">
    
    <button type="submit">Enviar pedido</button>
    <br><br>
    </form>
    </section>
</body>>
</html>>
