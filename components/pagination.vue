<template>
    <nav class="w-100 p-4 bg-light shadow mb-3 d-flex justify-content-start align-items-center gap-2">
         <a href="/" class="text-primary"><strong>HOME</strong></a>
         <i class="bi bi-chevron-compact-right"></i>
         <slot></slot>
    </nav>
</template>
<style scoped>
a{
    width: fit-content;
}
</style>