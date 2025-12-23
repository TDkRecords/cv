<script>
    import profileIMG from "$lib/assets/images/sentado(1-1).png";
    import profileIMG2 from "$lib/assets/images/cv-profile.jpg";
    import AntecedentesJudiciales from "$lib/assets/images/AntecedentesJudiciales.jpg";
    import ActaGrado from "$lib/assets/images/Acta de grado.jpg";
    /* PDFS */
    import ActaGradoPDF from "$lib/assets/pdf/Acta de grado.pdf";
    import AntecedentesJudicialesPDF from "$lib/assets/pdf/AntecedentesJudiciales.pdf";
    /* ESTILOS GLOBALES */
    import "$lib/assets/styles/style.css";

    import Experience from "$lib/components/Experience.svelte";
    import Education from "$lib/components/Education.svelte";
</script>

<svelte:head>
    <meta charset="utf-8" />
    <title>Presentación | Jhon Alex Burbano Gordillo</title>
</svelte:head>

<div class="container-fluid border-start border-dark-subtle w-100 h-100">
    <div class="row">
        <!-- Primera Columna -->
        <div class="col-sm-8 p-5 border-start border black">
            <div>
                <div class="text-end mt-5">
                    <h1>Jhon Alex <br /> Burbano Gordillo</h1>
                    <small class="fst-italic">Desarrollador Web</small>
                </div>
                <div class="mt-5">
                    <h3 class="text-black-50">EXPERIENCIA</h3>
                </div>
                <Experience />
                <div class="mt-5">
                    <h3 class="text-black-50">EDUCACIÓN</h3>
                </div>
                <Education />
            </div>
        </div>
        <!-- Segunda Columna -->
        <div class="col-sm-4 bg-secondary-subtle p-5">
            <!-- Imagen De Perfil -->
            <div class="w-100 text-center">
                <img
                    src={profileIMG2}
                    alt="logo.png"
                    class="img-fluid rounded-circle border border-black border-1"
                    width="320"
                />
            </div>
            <!-- Contacto -->
            <div class="mt-5">
                <p>
                    <i class="bi bi-envelope-at"></i>
                    tdksongs@gmail.com
                </p>
                <p>
                    <i class="bi bi-house-door"></i>
                    Cra 15A #1 sur 17
                </p>
                <p>
                    <i class="bi bi-phone"></i>
                    +57 315 960 3020
                </p>
                <p>
                    <i class="bi bi-calendar-event"></i>
                    30 Jul 2004
                </p>
                <p>
                    <i class="bi bi-instagram"></i>
                    @_axeljosh_
                </p>
            </div>
            <br />
            <!-- Objetivo Profesional -->
            <div class="mt-5 me-5">
                <h6>
                    OBJETIVO
                    <i class="bi bi-compass"></i>
                </h6>
                <p class="mt-3">
                    Soy un programador en formación con habilidades en diseño
                    gráfico y una base solida de ofimática. Mi Objetivo es
                    aportar soluciones innovadoras y eficientes al desarrollo de
                    software y aplicaciones, combinando creatividad y lógica.
                    Busco integrarme a un equipo donde pueda potenciar mis
                    habilidades técnicas y contribuir al éxito personal de cada
                    persona con compromiso y responsabilidad.
                </p>
            </div>
            <!-- HABILIDADES -->
            <br />
            <div class="mt-5">
                <h6>
                    HABILIDADES
                    <i class="bi bi-person-gear"></i>
                </h6>
                <div class="mt-3">
                    <ul>
                        <li>Progración web (Svelte, Django)</li>
                        <li>Producción Musical</li>
                        <li>Ofimática</li>
                        <li>Aprendizaje rápido</li>
                        <li>Trabajo en equipo</li>
                        <li>Resolución de problemas</li>
                    </ul>
                </div>
            </div>
            <!-- IDIOMAS -->
            <div class="mt-5">
                <h6>
                    IDIOMAS
                    <i class="bi bi-translate"></i>
                </h6>
                <div class="mt-3">
                    <ul>
                        <li>Español (Nativo)</li>
                        <li>Inglés (Intermedio)</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="container-fluid bg-dark-subtle">
    <div class="row p-5">
        <div class="col-md-6">
            <div class="m-auto text-center my-4">
                <h3>
                    <a
                        href={AntecedentesJudicialesPDF}
                        download="AntecedentesJudiciales_Jhon_Alex_Burbano_Gordillo.pdf"
                    >
                        Antecedentes Judiciales
                    </a>
                </h3>
                <img
                    class="img-fluid"
                    src={AntecedentesJudiciales}
                    alt="Antecedentes.jpg"
                />
            </div>
        </div>
        <div class="col-md-6">
            <div class="m-auto text-center my-4">
                <h3>
                    <a
                        href={ActaGradoPDF}
                        download="Acta_de_grado_Jhon_Alex_Burbano_Gordillo.pdf"
                    >
                        Acta de Grado
                    </a>
                </h3>
                <img class="img-fluid" src={ActaGrado} alt="ActadeGrado.jpg" />
            </div>
        </div>
    </div>
</div>

<style></style>
