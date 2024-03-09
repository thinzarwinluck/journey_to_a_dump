<template>
    <div>
        <nav>
            <RouterLink to="/">Home</RouterLink>
            <RouterLink to="/about">About</RouterLink>
            <h1 className="text-3xl font-bold underline">
                Hello world!
              </h1>
        </nav>
    </div>
</template>
<script setup lang="ts">
import { RouterLink } from 'vue-router';
</script>