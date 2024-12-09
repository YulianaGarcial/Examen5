<!DOCTYPE html>
<html lang="es-mx">
<head>
    <meta charset="UTF-8">
    <title>IntroPhp7 Grupo X</title>
    <link rel="stylesheet" href="css/estilos.css">
    <link rel="stylesheet" href="css/menu.css">
    <link rel="stylesheet" href="css/problemas.css">
    <link href="https://fonts.googleapis.com/css?family=Rambla" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Comfortaa" rel="stylesheet">
</head>
<body>
    <section class="wrapper">
        <header>
            <h1 class="logo"><a href="index.php">StemPhp</a></h1>
            <nav>
                <ul>
                    <li><a href="index.php" class="current">Inicio</a></li>
                </ul>
            </nav>
        </header>
        
        <section id="contenedor">
            <section class="problema">
                <h2>Problema: Calcular la cantidad de calor </h2>
                <p>Descripción:</p>
                <p>
                    Calcula la cantidad de calor (en Kcal) que habra entrado en una casa 
                    durante el mes de Agosto si tiene una cristalera de 3 x 2 m y no se han 
                    producido perdidas de vidrio.

                    K = 950 W/m2 y considera 10 horas de sol al día 
                </p>
            </section>

            <section class="formulas">
                <h2>Fórmulas</h2>
                <p><strong>Q = K × t × S × r</strong> (en Kcal)</p>
                <p>Para convertir a KWh (base 1 hora):</p>
                <p><strong>1 cal = 4.18 J</strong> y <strong>1 KWh = 3.6 × 10⁶ J</strong></p>
            </section>

            <section class="datos">
                <h2>Datos:</h2>
                <ul>
                    <li><strong> Q = Energia generada </strong></li>
                    <li><strong> t = Tiempo en minutos </strong></li>
                    <li><strong> S = Area en cm2 </strong></li>
                    <li><strong> r = Rendimienti </strong></li>
                    <li><strong> K = Coeficiente de radiacion </strong></li>
                </ul>
            </section>

            <section class="calculos">
    <h2>Solución</h2>
    <p>Se calcula la cantidad de calor (en Kcal) que entra en la casa durante el mes de agosto 
        considerando las condiciones establecidas.</p>
</section>
</section>

<section class="resultado">
    <h2>Resultado:</h2>
    <div id="resultadoA">
        <?php
            // Datos del problema
            $k = 950; // W/m²
            $area_m2 = 3 * 2; // Área en m² (3 x 2)
            $horas_dia = 10; // Horas de sol al día
            $dias_mes = 31; // Días en agosto

            // Cálculo de la energía total en Wh
            $energia_wh = $k * $area_m2 * $horas_dia * $dias_mes;

            // Conversión de Wh a Kcal (1 Wh = 0.859845 Kcal)
            $energia_kcal = $energia_wh * 0.859845;

            // Mostrar resultados
            echo "<p><strong>Energía generada en el mes:</strong> " . number_format($energia_kcal, 2) . " Kcal</p>";
        ?>
    </div>
</section>

    <footer class="pie">
        García García Yuliana
    </footer>
</body>
</html>