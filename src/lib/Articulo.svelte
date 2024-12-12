<script>
    export let title = ""; 
    export let description = ""; 
    export let imageUrl = "";
</script>

<div class="card">
    <img src={imageUrl} alt={title} />
    <h3>{title}</h3>
    <p>{description}</p>
</div>

<style>
    .card {
        background-color: #E2FFED; 
        border-radius: 10px; 
        box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        text-align: center;
        width: 150px; 
        padding: 10px;
        font-family: Arial, sans-serif;
    }

    .card img {
        width: 100%;
        border-radius: 8px;
    }

    .card h3 {
        margin: 10px 0 5px 0;
        font-size: 16px;
        font-weight: bold;
    }

    .card p {
        margin: 0;
        font-size: 12px;
        color: #333;
    }
</style>
