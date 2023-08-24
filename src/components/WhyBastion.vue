<template>
    <section class="light-bg">
        <div class="my-container">
            <div class="columns is-variable is-2 ">
                <div class="column is-one-third main-column">
                    <div class="is-flex is-flex-direction-column">
                        <h2 class="is-size-2 has-text-weight-bold mb-4">Why Basiton</h2>
                        <p class="is-size-5 has-text-weight-normal has-text-black subheader">Highly credible coaches. Best
                            in-class
                            personal training App</p>
                        <img src="../assets/woman-climbing.jpg" alt="Woman climbing exercise wall" />
                    </div>
                </div>
                <div class="column is-one-third">
                    <div class="is-flex is-flex-direction-column cards-column-1">
                        <div class="has-text-white m-3 feature-card">
                            <h3 class="blue-line">Evidence-Based</h3>
                            <p>Many of our coaches have a Bachelor’s or higher degree in exercise science, psychology,
                                biomechanics, health, and more.</p>
                        </div>
                        <div class="has-text-white m-3 feature-card">
                            <h3 class="purple-line">Personalized</h3>
                            <p>Our coaches meet you where you are at. You can only workout once a week? No problem. Our
                                coaches work with you no matter what life throws at you and get you to a place YOU are happy
                                with.</p>
                        </div>
                    </div>
                </div>
                <div class="column is-one-third">
                    <div class="is-flex is-flex-direction-column">
                        <div class="has-text-white m-3 feature-card">
                            <h3 class="yellow-line">Holistic</h3>
                            <p>We understand that fitness is not just about exercise. It comes from setting the right
                                mindset, a proper approach to nutrition, and developing everyday habits to make it part of
                                your lifestyle.</p>
                        </div>
                        <div class="has-text-white m-3 feature-card">
                            <h3 class="green-line">Goal Oriented</h3>
                            <p>Setting a big goal to strive for is great. But our coaches take this to the next level by
                                setting mini goals for you every step of the way so you can develop key habits.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.my-container {
    padding: 10rem 7rem;
}

h2 {
    color: var(--aqua-color);
}

img {
    border-radius: 20px;
    margin-top: 1.62rem;
    aspect-ratio: 299 / 644;
    object-fit: cover;
}

h3 {
    font-size: 1.75rem;
    font-style: normal;
    font-weight: 600;
    line-height: 2.065rem;
    padding-left: 1.15rem;
    margin-bottom: .65rem;
}

.main-column {
    padding-right: 5rem !important;
}

.subheader {
    line-height: 24px;
    letter-spacing: 0.4px;
}

.blue-line {
    border-left: 3px solid #1FCFF1;
}

.purple-line {
    border-left: 3px solid #9945FF;
}

.yellow-line {
    border-left: 3px solid #FFD512;
}

.green-line {
    border-left: 3px solid #19FB9B;
}

.feature-card {
    padding: 2rem;
    padding-right: 3rem;
    background-color: var(--card-dark-color);
    border-radius: 24px;
    height: 22rem;
}

.feature-card p {
    color: var(--font-gray2-color);
    line-height: 1.70625rem;
}

.cards-column-1 {
    padding-top: 5rem;
}

.cards-column-2 {
    padding-bottom: 3rem;
}
</style>