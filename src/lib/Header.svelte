<script>
</script>

<div class="header">
    <div class="logo">
        <img src="../../logo-mercapp.png" alt="Cart Icon" width="70" />
    </div>

    <div class="buscador">
        <input type="text" placeholder="Buscar..." />
    </div>

    <div class="icons">
        <button class="icon">
            <img src="../../likes.png" alt="Heart Icon" />
        </button>
        
        <button class="icon">
            <img src="../../perfil.png" alt="Profile Icon" />
        </button>
    </div>
</div>

<style>
    .header {
        margin: 0;
        display: flex;
        align-items: center;
        background-color: #baf7a1;
        padding: 20px;
    }

    .logo {
        margin-right: 10px;
    }

    .buscador {
        flex-grow: 1;
        display: flex;
        justify-content: center;
    }

    .buscador input {
        width: 80%;
        padding: 8px;
        border: 1px solid #ccc;
        border-radius: 5px;
        background: rgb(227, 227, 227);
    }

    .icons {
        display: flex;
        align-items: center;
        gap: 15px;
    }

    .icon {
        background: none;
        border: 0;
    }

    .icon img {
        width: 50px; 
    }
</style>
