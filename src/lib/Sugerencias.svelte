<script>
    import Articulo from "./Articulo.svelte";
</script>

<div class="sugerencias">
    <h2>Sugerencias</h2>
    <div class="articulos">
        <Articulo
            title="Balon"
            description="Idenw lsncnks kltkfve fjyo iya"
            imageUrl="/producto.png"
        />
        <Articulo
            title="Balon"
            description="Idenw lsncnks kltkfve fjyo iya"
            imageUrl="/producto.png"
        />
        <Articulo
            title="Balon"
            description="Idenw lsncnks kltkfve fjyo iya"
            imageUrl="/producto.png"
        />
        <Articulo
            title="Balon"
            description="Idenw lsncnks kltkfve fjyo iya"
            imageUrl="/producto.png"
        />
        <Articulo
            title="Balon"
            description="Idenw lsncnks kltkfve fjyo iya"
            imageUrl="/producto.png"
        />
    </div>
</div>

<style>
    .sugerencias {
        padding: 20px;
        font-family: Arial, sans-serif;
    }

    h2 {
        margin: 0 0 20px 0;
    }

    .articulos {
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap; 
    }
</style>
