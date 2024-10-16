<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sistema de Inventario de Equipos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        h1 {
            text-align: center;
            margin-bottom: 30px;
        }

        form {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 30px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        form div {
            margin-bottom: 10px;
        }

        label {
            display: block;
            margin-bottom: 5px;
        }

        input, select {
            width: 100%;
            padding: 8px;
            box-sizing: border-box;
        }

        button {
            padding: 10px 15px;
            cursor: pointer;
            background-color: #28a745;
            color: white;
            border: none;
            margin-top: 10px;
        }

        button:disabled {
            background-color: #ccc;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 12px;
            text-align: left;
        }

        th {
            background-color: #4CAF50;
            color: white;
        }

        .buttons {
            margin-top: 10px;
            display: flex;
            justify-content: space-between;
        }

        .buttons button {
            width: 32%;
            padding: 10px;
        }

        .delete-btn {
            background-color: #dc3545;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Sistema de Inventario de Equipos</h1>

        <!-- Formulario para agregar equipos -->
        <form id="formEquipo">
            <div>
                <label for="empresa">Empresa:</label>
                <input type="text" id="empresa" name="empresa" required>
            </div>
            <div>
                <label for="usuario">Nombre de Usuario:</label>
                <input type="text" id="usuario" name="usuario" required>
            </div>
            <div>
                <label for="tipoEquipo">Tipo de Equipo:</label>
                <input type="text" id="tipoEquipo" name="tipoEquipo" required>
            </div>
            <div>
                <label for="modelo">Modelo:</label>
                <input type="text" id="modelo" name="modelo" required>
            </div>
            <div>
                <label for="marca">Marca:</label>
                <input type="text" id="marca" name="marca" required>
            </div>
            <div>
                <label for="numSerie">Número de Serie:</label>
                <input type="text" id="numSerie" name="numSerie" required>
            </div>
            <div class="buttons">
                <button type="button" onclick="agregarEquipo()">Agregar</button>
                <button type="reset">Limpiar</button>
                <button type="button" onclick="eliminarEquipo()" class="delete-btn">Eliminar Último</button>
            </div>
        </form>

        <!-- Tabla de Inventario -->
        <table id="tablaInventario">
            <thead>
                <tr>
                    <th>Empresa</th>
                    <th>Nombre de Usuario</th>
                    <th>Tipo de Equipo</th>
                    <th>Modelo</th>
                    <th>Marca</th>
                    <th>Número de Serie</th>
                </tr>
            </thead>
            <tbody>
                <!-- Filas dinámicamente agregadas aquí -->
            </tbody>
        </table>
    </div>

    <script>
        const form = document.getElementById('formEquipo');
        const tablaInventario = document.getElementById('tablaInventario').getElementsByTagName('tbody')[0];

        // Función para agregar un equipo a la tabla
        function agregarEquipo() {
            // Obtener valores del formulario
            const empresa = form.empresa.value;
            const usuario = form.usuario.value;
            const tipoEquipo = form.tipoEquipo.value;
            const modelo = form.modelo.value;
            const marca = form.marca.value;
            const numSerie = form.numSerie.value;

            // Validar que todos los campos estén completos
            if (!empresa || !usuario || !tipoEquipo || !modelo || !marca || !numSerie) {
                alert('Por favor, complete todos los campos.');
                return;
            }

            // Crear una nueva fila
            const fila = tablaInventario.insertRow();

            // Insertar celdas en la fila
            const cellEmpresa = fila.insertCell(0);
            const cellUsuario = fila.insertCell(1);
            const cellTipoEquipo = fila.insertCell(2);
            const cellModelo = fila.insertCell(3);
            const cellMarca = fila.insertCell(4);
            const cellNumSerie = fila.insertCell(5);

            // Asignar valores a las celdas
            cellEmpresa.innerText = empresa;
            cellUsuario.innerText = usuario;
            cellTipoEquipo.innerText = tipoEquipo;
            cellModelo.innerText = modelo;
            cellMarca.innerText = marca;
            cellNumSerie.innerText = numSerie;

            // Limpiar el formulario después de agregar
            form.reset();
        }

        // Función para eliminar el último equipo ingresado
        function eliminarEquipo() {
            const rowCount = tablaInventario.rows.length;
            if (rowCount > 0) {
                tablaInventario.deleteRow(rowCount - 1);
            } else {
                alert('No hay equipos para eliminar.');
            }
        }
    </script>

</body>
</html>
