# Juego de Memoria en React
## Descripción

Este proyecto es un juego de memoria desarrollado en React usando un solo archivo HTML, sin utilizar herramientas como create-react-app o vite. El objetivo es encontrar todas las parejas de cartas volteándolas de dos en dos. El juego incluye animaciones, contador de movimientos y un mensaje de felicitación al completar el juego.
Tecnologías Utilizadas

    React y ReactDOM (importados vía CDN)

    Babel (para permitir el uso de JSX en el navegador)

    CSS Grid (para el diseño de la grilla de tarjetas)

    CSS Transitions (para animar el flip de las tarjetas)

### ¿Cómo funciona React en este proyecto?

    El juego está encapsulado en un componente funcional llamado MemoryGame.

    Utiliza hooks de React (useState y useEffect) para manejar el estado del juego:

        Las cartas y su orden aleatorio.

        Las cartas volteadas temporalmente.

        Las parejas encontradas.

        El número de movimientos realizados.

        La detección de que el juego ha sido completado.

    El contenido de la pantalla se renderiza dinámicamente usando JSX, y React se encarga de actualizar la vista automáticamente cada vez que cambian los estados.

    Se usa .map() para generar las tarjetas de forma dinámica basándose en el estado actual del arreglo de cartas.

    La inicialización de la aplicación se realiza con:

    ReactDOM.createRoot(document.getElementById('root')).render(<MemoryGame />);

### Características principales

    Grid de 4x4 cartas generadas aleatoriamente cada vez que se carga la página.

    Animación de flip al voltear las cartas.

    Contador de movimientos visibles todo el tiempo.

    Mensaje de victoria cuando se completan todas las parejas.

    Diseño responsivo usando CSS Grid.

    Código organizado en un solo archivo .html como lo exige el laboratorio.

#### Nota

Se prohíbe el uso de create-react-app o vite. Todo el entorno de React y Babel es cargado manualmente a través de CDN.
