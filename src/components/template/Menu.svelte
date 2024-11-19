<script>
    export let title = "Title";
</script>

<div class="flex flex-col gap-3">
    <span class="text-sm font-bold text-zinc-600">{title}</span>
    <ul class="flex flex-col">
        <slot></slot>
    </ul>
</div>