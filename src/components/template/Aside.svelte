<script>
    import ManuItem from "./MenuItem.svelte";
import Menu from "./Menu.svelte";

</script>
<aside class="flex flex-col self-start border border-zinc-800 p-5 rounded-mg gap-10 w-72">

    
    <Menu title="Navegation">
        <ManuItem text="Home" href="/"/>
        <ManuItem text="Personage" href="/" />
        <ManuItem text="Authors" href="/authors"/>
        <ManuItem text="Series" href="/"/>
    </Menu>
    <Menu title="Main authors">
        <ManuItem text="J.K, Rowling" href="/"/>
        <ManuItem text="J.R.R. Tolkien" href="/" />
        <ManuItem text="George R.R. Martin" href="/authors/georgeMartin"/>
    </Menu>
    <Menu title="Other categories">
        <ManuItem text="J.K, Rowling" href="/"/>
        <ManuItem text="J.R.R. Tolkien" href="/" />
        <ManuItem text="George R.R. Martin" href="/authors/georgeMartin"/>
    </Menu>
</aside>