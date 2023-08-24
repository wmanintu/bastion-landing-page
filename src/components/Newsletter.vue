<template>
    <section class="newsletter-bg">
        <div class="my-container">
            <div class="columns main">
                <div class="column width-41">
                    <h2 class="has-text-white">
                        Take control of your <br>
                        personal <span class="aqua">fitness today</span>
                    </h2>
                </div>
                <div class="column is-flex is-justify-content-flex-start gap py-5 pl-6">
                    <input class="width-100" type="text" placeholder="Enter your email" />
                    <button class="button is-large is-uppercase width-100 height-100">Subscribe Newsletter</button>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
h2 {
    font-family: var(--font-5);
    font-size: 3.4375rem;
    font-style: normal;
    font-weight: 600;
    line-height: 101.2%;
}

input {
    padding-left: 3.1rem;
    border-radius: 8px;
}

input::placeholder, input[type=text]:focus {
    color: var(--font-input-color);
    font-family: var(--font-primary);
    font-size: 1.25rem;
    font-style: normal;
    font-weight: 400;
    line-height: 198.5%;

}

button {
    border-radius: 8px;
    background-color: var(--aqua-color);
    font-size: 1.25rem;
    font-style: normal;
    font-weight: 600;
    line-height: 1.5rem;
}

.main {
    padding: 4rem 1.5rem;
}

.gap {
    gap: 1rem;
}

.aqua {
    color: var(--aqua-color);
}

.newsletter-bg {
    background-image: url('../assets/newsletter-bg.png');
    background-size: cover;
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
}

.width-41 {
    flex: none;
    width: 41%;
}
</style>