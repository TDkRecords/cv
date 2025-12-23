<script>
    const educacion = [
        {
            fechaInicio: "Ene 2010",
            fechaFin: "Nov 2019",
            titulo: "Institución Educativa Municipal",
            institucion: "Tecnico Industrial | Pasto, Nar",
        },
        {
            fechaInicio: "Ene 2020",
            fechaFin: "Dic 2022",
            titulo: "Institución Educativa San Nicolas",
            institucion:
                "Mención Honorifica y Medalla por Excelencia - prom 2022 | Pasto, Nar",
        },
        {
            fechaInicio: "Ago 2023",
            fechaFin: "Actualmente",
            titulo: "Cinar Sistemas",
            institucion: "Ténico | Pasto, Nar",
        },
    ];
</script>

{#each educacion as item}
    <div class="row mt-3 border-bottom p-1">
        <div class="col">
            <p>
                <i class="bi bi-arrow-return-right"></i>
                {item.fechaInicio}
                <br />
                <i class="bi bi-arrow-return-right"></i>
                {item.fechaFin}
            </p>
        </div>
        <div class="col">
            <h5 class="">
                {item.titulo}
                <br />
                <small class="text-secondary">
                    {item.institucion}
                </small>
            </h5>
        </div>
    </div>
{/each}
