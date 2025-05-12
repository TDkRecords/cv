<script>
    import profileIMG from "$lib/assets/images/sentado(1-1).png";
    import profileIMG2 from "$lib/assets/images/cv-profile.jpg";
    import AntecedentesJudiciales from "$lib/assets/images/AntecedentesJudiciales.jpg";
    import ActaGrado from "$lib/assets/images/Acta de grado.jpg";
    import CedulaFrente from "$lib/assets/images/C.C Alex_page-0001.jpg";
    import CedulaReverso from "$lib/assets/images/C.C Alex_page-0002.jpg";
    /* PDFS */
    import CedulaPDF from "$lib/assets/pdf/Cedula-Alex.pdf";
    import ActaGradoPDF from "$lib/assets/pdf/Acta de grado.pdf";
    import AntecedentesJudicialesPDF from "$lib/assets/pdf/AntecedentesJudiciales.pdf";

    /* ESTILOS GLOBALES */
    import "$lib/assets/styles/style.css";
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
                <div class="ms-4">
                    <div class="ms-5 mt-4">
                        <h6>
                            PRODUCTOR MUSICAL <br />
                            <small class="text-secondary">
                                Independiente
                            </small>
                        </h6>
                    </div>
                    <div class="ms-4">
                        <ul>
                            <li class="text-secondary">
                                Control de los procesos de producción,
                                grabación, mezcla y masterización.
                            </li>
                            <li class="text-secondary">
                                Realización de arreglos musicales, vocales y
                                grabación de voces sobre bases instrumentales.
                            </li>
                            <li class="text-secondary">
                                Desarrollo de la visión artistica del proyecto.
                            </li>
                        </ul>
                    </div>
                    <div class="ms-5 mt-5">
                        <h6>
                            DISEÑADOR GRÁFICO <br />
                            <small class="text-secondary"> Plaza Norte </small>
                        </h6>
                    </div>
                    <div class="ms-4">
                        <ul>
                            <li class="text-secondary">
                                Creación de proyectos de diseño exclusivo para
                                los clientes desde el concepto hasta la
                                finalización.
                            </li>
                            <li class="text-secondary">
                                creación de piezas gráficas para la web, redes
                                sociales y distintos formatos digitales.
                            </li>
                            <li class="text-secondary">
                                creación de diseños de impacto para campañas de
                                marketing digital.
                            </li>
                        </ul>
                    </div>
                    <div class="ms-5 mt-5">
                        <h6>
                            PRACTICANTE <br />
                            <small class="text-secondary">
                                Soluciones Tecnologicas Empresariales
                            </small>
                        </h6>
                    </div>
                    <div class="ms-4">
                        <ul>
                            <li class="text-secondary">
                                Cumplimiento de las tareas de trabajo recibidas
                                al pie de la letra
                            </li>
                            <li class="text-secondary">
                                Cumplimiento de los objetivos fijados en la
                                practica.
                            </li>
                            <li class="text-secondary">
                                Colaboración con el equipo de trabajo en el
                                desarrollo de las tareas a cargo.
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="mt-5">
                    <h3 class="text-black-50">EDUCACIÓN</h3>
                </div>
                <div class="row mt-5 border-bottom p-1">
                    <div class="col">
                        <p>
                            <i class="bi bi-arrow-return-right"></i>
                            Ene 2010
                            <br />
                            <i class="bi bi-arrow-return-right"></i>
                            Nov 2019
                        </p>
                    </div>
                    <div class="col">
                        <h5>
                            Institución Educativa Municipal <br />
                            <small class="text-secondary">
                                Tecnico Industrial | Pasto, Nar
                            </small>
                        </h5>
                    </div>
                </div>
                <div class="row mt-3 border-bottom p-1">
                    <div class="col">
                        <p>
                            <i class="bi bi-arrow-return-right"></i>
                            Ene 2020
                            <br />
                            <i class="bi bi-arrow-return-right"></i>
                            Dic 2022
                        </p>
                    </div>
                    <div class="col">
                        <h5>
                            Institución Educativa <br />
                            <small class="text-secondary">
                                San Nicolas | Pasto, Nar
                            </small>
                        </h5>
                        <ul>
                            <li class="text-black-50">
                                Mención Honorifica y Medalla por Excelencia -
                                prom 2022
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="row mt-3 p-1">
                    <div class="col">
                        <p>
                            <i class="bi bi-arrow-return-right"></i>
                            Ago 2023
                            <br />
                            <i class="bi bi-arrow-return-right"></i>
                            Actualmente
                        </p>
                    </div>
                    <div class="col">
                        <h5>
                            Cinar Sistemas
                            <small class="text-secondary"> | Pasto, Nar </small>
                        </h5>
                    </div>
                </div>
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
                        href={CedulaPDF}
                        download="Cedula_Jhon_Alex_Burbano_Gordillo.pdf"
                    >
                        Cédula Frente
                    </a>
                </h3>

                <img
                    class="img-fluid"
                    src={CedulaFrente}
                    alt="CedulaFrente.jpg"
                />
            </div>
        </div>
        <div class="col-md-6">
            <div class="m-auto text-center my-4">
                <h3>
                    <a
                        href={CedulaPDF}
                        download="Cedula_Jhon_Alex_Burbano_Gordillo.pdf"
                    >
                        Cedula Reverso
                    </a>
                </h3>
                <img
                    class="img-fluid"
                    src={CedulaReverso}
                    alt="CedulaReverso.jpg"
                />
            </div>
        </div>

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
