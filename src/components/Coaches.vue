<template>
    <section class="dark-bg">
        <div class="my-container">
            <div class="columns px-6">
                <div class="column has-text-white is-two-fifths">
                    <img class="dots" src="../assets/dots-1-row.svg" alt="Decorative dots" />
                    <h2 class="is-size-2 has-text-weight-bold">The best coaches for your best self.</h2>
                    <p class="is-size-4 subheader">Nationally certified in personal training, nutrition, behavior change,
                        and years of experience with
                        beginners
                        to world-class athletes.</p>
                    <button class="button">View All Coaches <img src="../assets/arrow-right.svg"
                            alt="Right arrow icon" /></button>
                </div>
                <div class="column">
                    <div class="is-flex is-flex-direction-column coach-cards-container is-relative">
                        <div class="is-flex coach-cards">
                            <div class="is-flex is-flex-direction-column coach-card">
                                <img src="../assets/coach-sebastien.jpg" alt="Coach Sebastien P." />
                                <div class="text-container">
                                    <p class="is-size-5 has-text-weight-bold has-text-black pb-3">Sebastien P.</p>
                                    <p class="has-text-weight-semibold description">Goal Oriented</p>
                                    <p class="has-text-weight-semibold description">Body Building</p>
                                    <a class="is-uppercase has-text-weight-medium has-text-centered pt-5 is-block"
                                        href="#">View Profile</a>
                                </div>

                            </div>
                            <div class="is-flex is-flex-direction-column coach-card active">
                                <img src="../assets/coach-lucas.jpg" alt="Coach Lucas H." />
                                <div class="text-container">
                                    <p class="is-size-5 has-text-weight-bold has-text-black pb-3">Lucas H.</p>
                                    <p class="has-text-weight-semibold description">Empathetic</p>
                                    <p class="has-text-weight-semibold description">Nutrition</p>
                                    <a class="is-uppercase has-text-weight-medium has-text-centered pt-5 is-block"
                                        href="#">View Profile</a>
                                </div>

                            </div>
                            <div class="is-flex is-flex-direction-column coach-card">
                                <img src="../assets/coach-jesse.jpg" alt="Coach Jesse V." />
                                <div class="text-container">
                                    <p class="is-size-5 has-text-weight-bold has-text-black pb-3">Jesse V.</p>
                                    <p class="has-text-weight-semibold description">Tough Love</p>
                                    <p class="has-text-weight-semibold description">Weight Loss</p>
                                    <a class="is-uppercase has-text-weight-medium has-text-centered pt-5 is-block"
                                        href="#">View Profile</a>
                                </div>

                            </div>
                        </div>
                        <div class="arrows-container is-flex">
                            <img src="../assets/arrow-left-short.svg" alt="Left arrow" />
                            <img src="../assets/arrow-right-short.svg" alt="Right arrow" />
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </section>
</template>

<style scoped>
.my-container {
    padding-top: 15rem;
    padding-bottom: 12rem;
}

h2 {
    letter-spacing: 0.05rem;
    padding-bottom: 1.6rem;
    line-height: normal;
}

button,
button:hover {
    padding: 2rem 1.5rem;
    background-color: transparent;
    color: var(--aqua-color);
    border: 1px solid var(--aqua-color);
    border-radius: 8px;
    font-family: var(--font-secondary);
    font-size: 1.125rem !important;
    font-style: normal;
    font-weight: 600;
    line-height: 1.375rem;
    /* 122.222% */
    letter-spacing: 0.0625rem;
}

button img {
    width: 1.5625rem;
    margin-left: 1.25rem;
}

.subheader {
    font-family: var(--font-secondary);
    padding-right: 6rem;
    margin-bottom: 6rem;
    letter-spacing: 0.12rem;
}

.coach-cards {
    gap: 2rem;
    width: 150%;
}

.coach-cards-container {
    padding-left: 7rem;
}

.coach-card {
    background-color: #fff;
}

.coach-card a {
    color: var(--aqua-color);
    font-size: 0.875rem;
}

.text-container {
    padding: .94rem .87rem;
}

.coach-card img {
    width: 16.875rem;
    height: 16.875rem;
}

.description {
    color: var(--font-gray-color);
    font-family: var(--font-secondary);
    font-size: 0.875rem;
    font-style: normal;
    font-weight: 500;
    line-height: 1.5rem;
    letter-spacing: 0.07rem;
}

.arrows-container {
    position: absolute;
    bottom: -4rem;
    left: 31.5rem;
    gap: 2.25rem;
}

.arrows-container img {
    cursor: pointer;
}

.active {
    border: 4px solid var(--aqua-color);
    filter: drop-shadow(0px 8px 80px rgba(0, 240, 255, 0.25));
}

.dots {
    padding-bottom: 1.9rem;
}</style>