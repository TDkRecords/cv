<script>
    const experiencias = [
        {
            titulo: "PRODUCTOR MUSICAL",
            empresa: "Independiente",
            descripcion: [
                "Control de los procesos de producción, grabación, mezcla y masterización.",
                "Realización de arreglos musicales, vocales y grabación de voces sobre bases instrumentales.",
                "Desarrollo de la visión artística del proyecto.",
            ],
        },
        {
            titulo: "PRACTICANTE",
            empresa: "Soluciones Tecnológicas Empresariales",
            descripcion: [
                "Cumplimiento de las tareas de trabajo recibidas al pie de la letra",
                "Cumplimiento de los objetivos fijados en la práctica.",
                "Colaboración con el equipo de trabajo en el desarrollo de las tareas a cargo.",
            ],
        },
        {
            titulo: "Vendedor de comida rapida",
            empresa: "Parque infantil",
            descripcion: [
                "Preparar la comida rapida",
                "Atencion al cliente",
                "Trabajo en equipo",
                "Gestion del dinero",
                "Gestion de inventario",
                "Gestion de pedidos",
            ],
        },
        {
            titulo: "Mesero",
            empresa: "Restaurante Chipichape",
            descripcion: [
                "Atencion al cliente",
                "Trabajo en equipo",
                "Resolución de problemas",
            ],
        },
        {
            titulo: "DESARROLLADOR WEB",
            empresa: "Independiente",
            proyectos: [
                {
                    nombre: "Petlife - Aplicación web para la gestión de mascotas",
                    detalles: [
                        "Proyecto meramente demostrativo",
                        "Utilización de Sveltekit, Firebase y Bootstrap",
                        "Incluye Página Administrativa",
                    ],
                    enlace: "https://petlife-colombia.vercel.app/",
                },
                {
                    nombre: "New Style - Tienda de calzado",
                    detalles: [
                        "Proyecto meramente demostrativo",
                        "Utilización de Sveltekit, Firebase y Bootstrap",
                        "Incluye Página Administrativa",
                    ],
                    enlace: "https://newstyle-colombia.vercel.app/",
                },
                {
                    nombre: "Panel de reconocimiento para Google",
                    detalles: [
                        "Proyecto para indexar información del artista Axel Josh en las búsquedas de Google",
                        "Utilización de Sveltekit y Tailwind",
                    ],
                    enlace: "https://axeljosh.vercel.app/",
                },
                {
                    nombre: "Demon Store",
                    detalles: [
                        "Proyecto real hecho para administrar la tienda de ropa DemonStore utilizando sveltekit y tailwind",
                        "La base de datos utilizada es firebase",
                    ],
                    enlace: "https://demonstore-psi.vercel.app",
                },
                {
                    nombre: "Angel Store",
                    detalles: [
                        "Proyecto real hecho para administrar la tienda de ropa AngelStore utilizando sveltekit con pnpm y tailwind",
                        "La base de datos utilizada es firebase",
                    ],
                    enlace: "https://angelstore.vercel.app",
                },
                {
                    nombre: "Acorde",
                    detalles: [
                        "Proyecto real hecho para administrar la tienda de fragancias Acorde utilizando sveltekit con pnpm y tailwind",
                        "La base de datos utilizada es firebase",
                    ],
                    enlace: "https://acorde.vercel.app",
                },
            ],
        },
    ];
</script>

<div class="ms-4">
    {#each experiencias as experiencia, i}
        <div class="ms-5 mt-4">
            <h6>
                {experiencia.titulo} <br />
                <small class="text-secondary">
                    {experiencia.empresa}
                </small>
            </h6>
        </div>
        {#if experiencia.descripcion}
            <div class="ms-4">
                <ul>
                    {#each experiencia.descripcion as item}
                        <li class="text-secondary">
                            {item}
                        </li>
                    {/each}
                </ul>
            </div>
        {/if}
        {#if experiencia.proyectos}
            <div class="ms-4">
                <ul>
                    {#each experiencia.proyectos as proyecto}
                        <li class="text-secondary mb-3">
                            <div class="text-black">
                                {proyecto.nombre}
                            </div>
                            <ol>
                                {#each proyecto.detalles as detalle}
                                    <li>{detalle}</li>
                                {/each}
                            </ol>
                            <div>
                                Enlace:
                                <a
                                    href={proyecto.enlace}
                                    target="_blank"
                                    rel="noopener noreferrer"
                                    class="text-black-50"
                                >
                                    {proyecto.enlace.replace("http://", "")}
                                </a>
                            </div>
                        </li>
                    {/each}
                </ul>
            </div>
        {/if}
    {/each}
</div>
