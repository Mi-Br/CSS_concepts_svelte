<script>
    import  './styles.css';
</script>

<nav>
    <ul>
        <li><a href="/">🏠</a></li>
        <li><a href="/RenderingI/">Rendering logic part I</a></li>
        <li><a href="/RenderingII/">Rendering logic part II</a></li>
    </ul>
    
</nav>

<slot></slot>


<style>
    ul,li {
        list-style: none;
        padding: 0;
        margin: 0;
    }
    li {
        min-width: 6em;
    }
    ul {
        display: flex;
        background-color: #eee;
        padding: 1em;
        gap: 3em;
    }
    a {
        text-decoration: none;
        color: #333;
        /* font-weight: bold; */
        padding: 12px 8px;
        outline-offset: 1rem;
    }
</style>