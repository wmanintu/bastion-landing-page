<template>
    <section class="dark-bg is-relative">
        <img class="dots-wide" src="../assets/dots-wide2.svg" alt="Decorative dots image"/>
        <div class="my-container">
            <h2 class="has-text-white has-text-centered is-size-2 has-text-weight-bold is-uppercase">
                What Clients Say About Us
            </h2>
            <!-- TODO: get slider -->
        </div>
        <img class="dots-narrow" src="../assets/dots-narrow2.svg" alt="Decorative dots image"/>
    </section>
</template>

<style scoped>
.my-container {
    padding: 11.75rem 0 7.5rem;
}

.dots-wide, .dots-narrow {
    position: absolute;
}

.dots-wide {
    top: -6.6rem;
    right: 0;
}

.dots-narrow {
    bottom: -5rem;
    left: 2rem ;
}

h2 {
    letter-spacing: 0.8px;
}
</style>