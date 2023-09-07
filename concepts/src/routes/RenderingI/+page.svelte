
<h1>Title</h1>
<div class="section">
    <div class="subject">
        <div class="title">Here goes my title</div>
    </div>
    <div class="content">
        <p>Lorem ipsum dolor sit am et, consectetur adipisicing elit. Quisquam, voluptatum.</p>
    </div>
</div>

<style>
    * {outline: 1px solid pink;}
    .section {
        height: 100vh;
        width: 100vw;
        display:grid;
        grid-template-columns: 300px 1fr;
    }
    .subject {
        background-color: #eee;
        position: relative;
    }
    .content {
        background-color: #ddd;
    }
    .title {
        font-size: 2rem;
        font-weight: bold;
        padding: 1rem;
        position: sticky;
        top: 100px;
    }
</style>