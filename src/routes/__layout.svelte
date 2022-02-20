<script>
    import {page} from "$app/stores"
    
    console.log(page)
</script>


<nav>
    <ul>
        <li><a href ="/">Home</a></li>
        <li><a href ="/about">About</a></li>
        <li><a href ="/contact">Contact</a></li>
        <li><a href ="/projects">Projects</a></li>
    </ul>
</nav>


<slot />

<style>
    ul {
        display: flex;
        list-style: none;
    }
    li {
        margin-right: 1em;
        font-weight: bold;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        
    }
    li:hover{
        text-decoration: underline;
    }

</style>