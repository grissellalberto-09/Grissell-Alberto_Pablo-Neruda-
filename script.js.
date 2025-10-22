// Este script es un ejemplo de cómo podrías añadir interactividad.
// En este caso, un simple mensaje de bienvenida y animación de scroll suave.

document.addEventListener('DOMContentLoaded', () => {
    // Scroll suave para la navegación
    document.querySelectorAll('nav a').forEach(anchor => {
        anchor.addEventListener('click', function (e) {
            e.preventDefault();
            document.querySelector(this.getAttribute('href')).scrollIntoView({
                behavior: 'smooth'
            });
        });
    });

    // Pequeño efecto al cargar la página (simulado)
    console.log("Página de Pablo Neruda cargada. ¡Bienvenido!");
});
