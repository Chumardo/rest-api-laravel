<script>
import { RouterView } from "vue-router";
export default {
    components: [RouterView],
};
</script>

<template>
    <div>
        <header>
            <div class="max-w-7xl mx-auto">
                <nav>
                    <RouterLink to="/">Home</RouterLink>
                    <RouterLink to="/skills">Skills</RouterLink>
                </nav>
            </div>
        </header>
        <main class="max-w-7xl mx-auto min-h-screen">
            <RouterView />
        </main>
    </div>
</template>
