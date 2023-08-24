<template>
    <section class="py-6 light-bg">
        <div class="my-container is-relative">
            <img class="dots-top" src="../assets/dots-2-rows.svg" alt="Decorative dots image" />
            <h2 class="is-size-1 has-text-weight-bold text has-text-centered has-text-black pb-6">How Bastion Works</h2>
            <div class="my-cards is-flex is-relative">
                <div class="is-flex is-flex-direction-column my-card dark">
                    <h3 class="is-size-5 is-uppercase has-text-weight-bold header">Building Life Long Habits</h3>
                    <p>Bastion is about changing and sustaining your lifestyle for the better in the long-run</p>
                    <img src="../assets/icon-upward.svg" alt="Upward icon" />
                </div>
                <div class="is-flex is-flex-direction-column my-card light">
                    <h3 class="is-size-5 is-uppercase has-text-weight-bold header">Custom Exercise & Nutrition Plans</h3>
                    <p>Your coach will monitor every aspect of your progress and hold you accountable to your goals every
                        step
                        of the way.</p>
                    <img src="../assets/icon-dumbell.svg" alt="Dumbell icon" />
                </div>
                <div class="is-flex is-flex-direction-column my-card dark">
                    <h3 class="is-size-5 is-uppercase has-text-weight-bold header">Monitoring and accountability</h3>
                    <p>Your coach will accelerate your progress by tailoring personalized exercise and nutrition plans no
                        matter
                        what your goals are or what life throws at you.</p>
                    <img src="../assets/icon-monitor.svg" alt="Monitor icon" />
                </div>
            </div>
            <img class="dots-bottom" src="../assets/dots-2-rows.svg" alt="Decorative dots image" />
        </div>
    </section>
</template>

<style scoped>
.dots-top,
.dots-bottom {
    position: absolute;
}

.dots-top {
    top: 0;
    left: -1rem;
}

.dots-bottom {
    bottom: -15rem;
    right: -1rem;
}

h2 {
    padding-top: 8rem;
}

.my-cards {
    padding: 5.8rem 4rem;
    margin: 6rem 0 16rem;
}

.my-card {
    width: 36%;
    position: absolute;
    height: 16.5rem;
    padding: 2.1rem 1.75rem;
    border-radius: 1.25rem;
}

.my-card:nth-child(1) {
    left: 2rem;
    top: 0;
}

.my-card:nth-child(2) {
    top: 0;
    left: 0;
    right: 0;
    margin-left: auto;
    margin-right: auto;
}

.my-card:nth-child(3) {
    right: 2rem;
    top: 0;
}

.my-card img {
    width: 6.5rem;
    height: 6.5rem;
    position: absolute;
    bottom: 0;
    right: 3rem;
}

.my-card.dark img {
    visibility: hidden;
}

.my-card p {
    font-family: var(--font-secondary);
    padding-top: 1.1rem;
}

.my-card .header {
    padding-bottom: 1.1rem;
}

.my-card.light .header {
    border-bottom: 1px solid var(--font-black-color);
}

.my-card.dark .header {
    border-bottom: 1px solid var(--font-white-color);
}

.my-card.dark {
    background-color: var(--card-dark-color);
    color: var(--font-white-color);
    z-index: 1;
}

.my-card.light {
    background-color: var(--aqua-color);
    color: var(--font-black-color);
    z-index: 2;
    box-shadow: var(--card-box-shadow);
}
</style>