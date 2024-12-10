<script>
</script>

<div class="nav">
    <div class="menu-icono">
        <img src="../../menu.png" alt="Menu Icon" />
    </div>

    <div class="grupo-botones">
        <button>Muebles</button>
        <button>Videojuegos</button>
        <button>Coches</button>
        <button>Moda</button>
        <button>Tecnología</button>
        <button>Deportes</button>
    </div>
</div>

<style>
    .nav {
        display: flex;
        align-items: center;
        background-color: #E2FFED; 
        padding: 10px;
        width: 100%; 
        box-sizing: border-box;
        gap: 10px;
    }

    .menu-icono {
        display: flex;
        align-items: center;
    }

    .menu-icono img {
        width: 24px; 
        height: 24px;
    }

    .grupo-botones {
        display: flex;
        width: 100%;
        justify-content: space-evenly;
        gap: 10px; 
    }

    .grupo-botones button {
        background-color: #d6f8c4;
        border: none;
        border-radius: 5px;
        padding: 8px 12px;
        cursor: pointer;
        font-size: 14px;
        box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2); 
    }

    .grupo-botones button:hover {
        background-color: #c3eab5; 
    }
    
</style>
