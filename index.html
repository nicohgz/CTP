<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>CTP Pro - Web</title>
<style>
    body { font-family: Arial; padding: 20px; }
    input, select, button { padding: 8px; margin: 5px; }
    table { border-collapse: collapse; width: 100%; margin-top: 20px; }
    th, td { border: 1px solid #ccc; padding: 8px; text-align: center; }
    th { background-color: #0056b3; color: white; }
</style>
</head>
<body>

<h2>CTP Pro - Gestión de Producción</h2>

<label>Páginas Totales:</label>
<input type="number" id="paginas">

<label>Tipo de PF:</label>
<select id="tipoPF">
    <option>Ninguna</option>
    <option>PF de 2 Páginas</option>
    <option>PF de 4 Páginas</option>
</select>

<button onclick="calcular()">GENERAR</button>

<table id="tabla">
    <thead>
        <tr>
            <th>Contenido Izquierda</th>
            <th>Posición</th>
            <th>Contenido Derecha</th>
            <th>Posición</th>
        </tr>
    </thead>
    <tbody></tbody>
</table>

<script>
function calcular() {
    let total = parseInt(document.getElementById("paginas").value);
    let tipo = document.getElementById("tipoPF").value;
    let tbody = document.querySelector("#tabla tbody");

    tbody.innerHTML = "";

    if (isNaN(total) || total % 2 !== 0) {
        alert("El número de páginas debe ser par.");
        return;
    }

    let mitad = total / 2;

    for (let i = 1; i <= mitad; i++) {
        let p_izq = i;
        let p_der = total - i + 1;

        let txt_izq = `Pág. ${p_izq}`;
        let txt_der = `Pág. ${p_der}`;

        // PF 2 páginas
        if (tipo === "PF de 2 Páginas") {
            if (p_izq === 1) {
                txt_izq = "PF 1 (PORTADA)";
                txt_der = `Pág. ${p_der - 2}`;
            } else if (p_izq === 2) {
                txt_izq = "PF 2 (VUELTA)";
                txt_der = `Pág. ${p_der - 2}`;
            } else {
                txt_izq = `Pág. ${p_izq - 2}`;
                txt_der = `Pág. ${p_der - 2}`;
            }
        }

        // PF 4 páginas
        else if (tipo === "PF de 4 Páginas") {
            if (p_izq === 1) {
                txt_izq = "PF 1 (PORTADA)";
                txt_der = "PF 4 (CONTRA)";
            } else if (p_izq === 2) {
                txt_izq = "PF 2 (VUELTA)";
                txt_der = "PF 3 (VUELTA)";
            } else {
                txt_izq = `Pág. ${p_izq - 2}`;
                txt_der = `Pág. ${p_der - 2}`;
            }
        }

        let row = `<tr>
            <td>${txt_izq}</td>
            <td>${p_izq}</td>
            <td>${txt_der}</td>
            <td>${p_der}</td>
        </tr>`;

        tbody.innerHTML += row;
    }
}
</script>

</body>
</html>
