<title>Harry Beck — Diseño y Visualización de Información</title>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    :root {
        --negro: #111111;
        --texto: #333333;
        --gris: #6f6f6f;
        --gris-claro: #f7f7f7;
        --borde: #d8d8d8;
    }

    body {
        font-family: Helvetica, Arial, sans-serif;
        color: var(--texto);
        background: db7248;
    }

    .contenedor {
        max-width: 800px;
        margin: 0 auto;
        padding: 0 3rem;
    }

    /* BARRA SUPERIOR */

    nav {
        padding: 1.15rem 0;
        border-bottom: 1px solid var(--borde);
        font-size: 0.72rem;
        letter-spacing: 0.08em;
        text-transform: uppercase;
    }

    nav .contenedor {
        display: flex;
        justify-content: space-between;
        gap: 20px;
        flex-wrap: wrap;
    }

    nav strong {
        color: var(--negro);
    }

    nav span:last-child {
        color: var(--gris);
    }

    /* PORTADA */

    header {
        text-align: center;
        padding: 3.2rem 0 2.6rem;
    }

    h1 {
        font-size: clamp(2.2rem, 6vw, 3.5rem);
        line-height: 1.08;
        color: var(--negro);
        font-weight: 700;
    }

    .subtitulo {
        font-family: Georgia, "Times New Roman", serif;
        font-style: italic;
        font-size: 1.45rem;
        color: var(--negro);
        margin: 0.65rem 0 1rem;
    }

    .autores {
        font-size: 0.82rem;
        color: var(--gris);
        line-height: 1.6;
    }

    /* CONTENIDO */

    article {
        padding-bottom: 3rem;
    }

    section {
        margin-bottom: 2.6rem;
    }

    h2 {
        font-family: Georgia, "Times New Roman", serif;
        font-style: italic;
        font-size: 1.05rem;
        font-weight: 700;
        color: var(--negro);

        margin-bottom: 0.6rem;
    }

    p {
        font-size: 0.97rem;
        line-height: 1.65;
        margin-bottom: 1rem;
    }

    .intro {
        font-family: Georgia, "Times New Roman", serif;
        font-style: italic;
        font-size: 1.05rem;
        line-height: 1.65;

        border-left: 3px solid var(--negro);
        padding-left: 1rem;
    }

    /* IMÁGENES */

    figure {
        margin: 2rem 0 2.3rem;

        border: 1px solid var(--borde);
        background: white;

        padding: 1rem;
    }

    figure img {
        display: block;
        width: 100%;
        height: auto;
    }

    figcaption {
        font-family: Georgia, "Times New Roman", serif;
        font-style: italic;

        font-size: 0.78rem;
        line-height: 1.45;
        color: var(--gris);

        margin-top: 0.7rem;
    }

    .descripcion {
        margin-top: 0.75rem;
        padding-top: 0.75rem;

        border-top: 1px solid var(--borde);

        font-size: 0.78rem;
        line-height: 1.5;
        color: #555555;
    }

    .descripcion strong {
        color: var(--negro);
    }

    /* CUADROS DE INFORMACIÓN */

    .caja {
        border: 1px solid var(--borde);
        background: var(--gris-claro);

        padding: 1.2rem 1.35rem;
        margin: 1.4rem 0;
    }

    .caja strong {
        display: block;

        font-size: 0.76rem;
        letter-spacing: 0.08em;
        text-transform: uppercase;

        color: var(--negro);

        margin-bottom: 0.4rem;
    }

    .caja p {
        margin: 0;
        font-size: 0.9rem;
        line-height: 1.55;
    }

    /* ANTES / CON BECK */

    .comparacion {
        display: grid;
        grid-template-columns: 1fr 1fr;

        gap: 1rem;

        margin: 1.5rem 0;
    }

    .mini-caja {
        border: 1px solid var(--borde);
        padding: 1rem;
    }

    .mini-caja h3 {
        font-family: Georgia, "Times New Roman", serif;
        font-style: italic;

        font-size: 1rem;
        color: var(--negro);

        margin-bottom: 0.45rem;
    }

    .mini-caja p {
        font-size: 0.86rem;
        line-height: 1.5;
        margin: 0;
    }

    /* PIE */

    footer {
        border-top: 1px solid var(--borde);

        padding: 1.25rem;

        text-align: center;

        font-size: 0.72rem;
        letter-spacing: 0.06em;

        color: var(--gris);
    }

    /* CELULAR */

    @media (max-width: 600px) {

        .contenedor {
            padding: 0 1.4rem;
        }

        header {
            padding: 2.3rem 0 2rem;
        }

        .comparacion {
            grid-template-columns: 1fr;
        }
    }
</style>
