<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dinámica Estructural Avanzada</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #34495e;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
</head>
<body>
    <header>
        <h1>Dinámica Estructural Avanzada</h1>
    </header>
    
    <nav>
        <a href="#introduccion">Introducción</a>
        <a href="#conceptos">Conceptos Clave</a>
        <a href="#aplicaciones">Aplicaciones</a>
        <a href="#recursos">Recursos</a>
    </nav>
    
    <section id="introduccion">
        <h2>Introducción</h2>
        <p>La dinámica estructural es una rama de la ingeniería civil que se enfoca en el análisis y diseño de estructuras sujetas a cargas dinámicas. Este campo es crucial para la seguridad y el rendimiento de las estructuras modernas, especialmente en zonas sísmicas.</p>
    </section>
    
    <section id="conceptos">
        <h2>Conceptos Clave</h2>
        <ul>
            <li>Grados de Libertad (DOF)</li>
            <li>Modelos de masa-resorte-amortiguador</li>
            <li>Análisis modal</li>
            <li>Respuesta de las estructuras a sismos</li>
        </ul>
        <h3>Ecuaciones Importantes</h3>
        <p>Una de las ecuaciones fundamentales en dinámica estructural es la ecuación de movimiento para un sistema de un grado de libertad (SDOF):</p>
        <p>$$m \ddot{x}(t) + c \dot{x}(t) + k x(t) = F(t)$$</p>
        <p>Donde:</p>
        <ul>
            <li><strong>m</strong> es la masa</li>
            <li><strong>c</strong> es el coeficiente de amortiguamiento</li>
            <li><strong>k</strong> es la rigidez</li>
            <li><strong>x(t)</strong> es el desplazamiento en el tiempo</li>
            <li><strong>F(t)</strong> es la fuerza aplicada en el tiempo</li>
        </ul>
        <p>Para un análisis modal, se utiliza la siguiente ecuación de autovalores:</p>
        <p>$$[K] \{\phi\} = \lambda [M] \{\phi\}$$</p>
        <p>Donde:</p>
        <ul>
            <li><strong>[K]</strong> es la matriz de rigidez</li>
            <li><strong>[M]</strong> es la matriz de masa</li>
            <li><strong>\{\phi\}</strong> es el vector modal</li>
            <li><strong>\lambda</strong> es el autovalor asociado</li>
        </ul>
    </section>
    
    <section id="aplicaciones">
        <h2>Aplicaciones</h2>
        <p>La dinámica estructural se aplica en el diseño de puentes, edificios altos, presas, y otras estructuras críticas. También es fundamental en la evaluación de la respuesta estructural frente a terremotos y otros eventos dinámicos.</p>
    </section>
    
    <section id="recursos">
        <h2>Recursos</h2>
        <p>A continuación, algunos recursos útiles para el estudio de la dinámica estructural:</p>
        <ul>
            <li><a href="https://www.sciencedirect.com" target="_blank">ScienceDirect</a></li>
            <li><a href="https://ascelibrary.org" target="_blank">ASCE Library</a></li>
            <li><a href="https://www.researchgate.net" target="_blank">ResearchGate</a></li>
        </ul>
    </section>
    
    <footer>
        <p>&copy; 2024 Dinámica Estructural Avanzada. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
