<!DOCTYPE html>
<html lang="es-ES">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>castillo Nacho</title>
</head>
<body>
    <h1>📝 Control de Inventario</h1>

    <section>
        <h2>Agregar Nuevo Producto</h2>
        <form id="formulario-producto">
            <label for="codigo">Código/SKU:</label>
            <input type="text" id="codigo" name="codigo" required><br><br>
            
            <label for="nombre">Nombre del Producto:</label>
            <input type="text" id="nombre" name="nombre" required><br><br>
            
            <label for="cantidad">Cantidad Inicial:</label>
            <input type="number" id="cantidad" name="cantidad" min="0" required><br><br>
            
            <label for="precio">Precio Unitario:</label>
            <input type="number" id="precio" name="precio" min="0" step="0.01" required><br><br>
            
            <button type="submit">Registrar Producto</button>
        </form>
    </section>
    
     <hr>

    <section>
        <h2>Inventario Actual</h2>
        <table id="tabla-stock" border="1" style="width:100%">
            <thead>
                <tr>
                    <th>Código/SKU</th>
                    <th>Nombre</th>
                    <th>Cantidad</th>
                    <th>Precio Unitario</th>
                    <th>Valor Total</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>PROD-001</td>
                    <td>Laptop X1</td>
                    <td>15</td>
                    <td>$800.00</td>
                    <td>$12000.00</td>
                </tr>
                <tr>
                    <td>PROD-002</td>
                    <td>Mouse Ergonómico</td>
                    <td>50</td>
                    <td>$25.50</td>
                    <td>$1275.00</td>
                </tr>
                </tbody>
        </table>
    </section>

    </body>
</html>
</body>
</html>
