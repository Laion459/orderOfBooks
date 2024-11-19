<script>
    import Header from "./Header.svelte";
    import Aside from "./Aside.svelte";
    import Footer from "./Footer.svelte";
</script>

<div class="flex flex-col min-h-screen bg-black text-white">
    <Header />
    <div class="flex-1 flex max-w-7xl mx-auto w-full p-5">
        <main class="flex-1 ">
            <slot></slot>
        </main>
        <Aside />
    </div>
    <Footer />
</div>
