<template>
    <div class="main-bg">
        <div class="myContainer">
            <nav
                class="is-flex is-justify-content-space-between is-align-items-center"
                role="navigation"
                aria-label="main navigation"
            >
                <div class="is-flex nav-links">
                    <a href="#">Home</a>
                    <a href="#">Coaches</a>
                    <a href="#">About</a>
                </div>
                <div>
                    <img src="../assets/logo.svg" alt="Bastion Logo" />
                </div>
                <div class="is-flex nav-links">
                    <a href="#">Blog</a>
                    <a href="#">Shop</a>
                    <a href="#">Login</a>
                </div>
            </nav>
        </div>
    </div>
</template>

<style scoped>
nav {
    padding: 1rem 2rem;
    color: var(--font-black-color);
    text-align: center;
    font-size: 1.25rem;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
    letter-spacing: 0.025rem;
}



.nav-links a {
    margin-right: 2rem;
}

.nav-links a:last-child {
    margin-right: 0;
}
</style>
