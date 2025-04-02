/* Estilos generales */
body {
    font-family: 'Comic Sans MS', cursive, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
    color: #333;
}

/* Contenedor principal */
.container {
    width: 80%;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

/* Títulos */
h1 {
    text-align: center;
    color: #ff6f61;
    font-size: 36px;
    margin-bottom: 20px;
}

h2 {
    color: #ff6f61;
    border-bottom: 2px solid #ffcc00;
    padding-bottom: 10px;
    font-size: 28px;
}

/* Tarjetas de cuentos */
.cuento-card {
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    overflow: hidden;
    text-align: center;
    margin-bottom: 20px;
    padding: 20px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.cuento-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
}

.cuento-card img {
    width: 100%;
    max-width: 300px;
    height: auto;
    border-radius: 8px;
    margin-bottom: 15px;
}

.cuento-card p {
    font-size: 18px;
    color: #555;
    line-height: 1.8;
    text-align: justify;
}

/* Pie de página */
footer {
    background-color: #2c3e50;
    color: #fff;
    text-align: center;
    padding: 20px 0;
    margin-top: 40px;
}

footer p {
    margin: 0;
    font-size: 16px;
}
