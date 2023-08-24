<template>
    <section class="light-bg">
        <div class="my-container">
            <div class="columns is-align-items-center">
                <div class="column is-three-fifths ml-5">
                    <h1 class="has-text-black">Better Than Personal Training.</h1>
                    <h2 class="py-5 is-size-2 has-text-black">
                        Match with a personalized coach. <br />
                        Accelerate your progress. <br />
                        Become your best self.
                    </h2>
                    <div class="is-flex pt-5">
                        <button class="button is-medium is-primary mr-6">
                            Find your Coach
                        </button>
                        <button class="button is-medium is-relative">
                            Learn More
                            <img src="../assets/arrow-up-right.svg" alt="Right arrow icon" />
                        </button>
                    </div>
                </div>
                <div class="column is-relative">
                    <img class="dots-narrow" src="../assets/dots-narrow.svg" alt="Decorative dots image" />
                    <img class="dots-wide" src="../assets/dots-wide.svg" alt="Decorative dots image" />
                    <div class="video-wrapper">
                        <video src="../assets/hero.mp4" autoplay loop muted></video>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
section {
    padding-top: 3rem;
    padding-bottom: 4rem;
}

h1 {
    font-family: var(--font-primary);
    font-size: 5rem;
    font-weight: 700;
    line-height: 120%;
    /* 6rem */
    letter-spacing: 0.1875rem;
}

h2 {
    font-family: var(--font-secondary);
    line-height: 140%;
    letter-spacing: 0.1875rem;
}

button {
    padding: 2rem 1.1rem;
    color: var(--font-black-color) !important;
    font-family: var(--font-secondary);
    font-size: 1.125rem !important;
    font-weight: 600;
    outline: none !important;
    border: 0 !important;
}

button img {
    position: absolute;
    right: -1rem;
    top: 1.25rem;
}

.is-primary,
.is-primary:hover {
    border-radius: 0.625rem;
    background: linear-gradient(180deg, #00f0ff 0%, #00eeff4f 100%);
    margin: 0;
}

.video-wrapper {
    overflow: hidden;
    width: 25.6875rem;
    height: 38.5625rem;
    aspect-ratio: 25.6875 / 38.5625;
    /* width: 22rem; */
    border-radius: 8px;
}

video {
    transform: translateY(-5rem);
}

.column:first-child {
    margin: 5rem 4rem;
}

.dots-narrow,
.dots-wide {
    position: absolute;
    z-index: 10;
}

.dots-narrow {
    right: 1rem;
    top: -2.5rem;
}

.dots-wide {
    left: -11rem;
    bottom: -2.5rem;
}
</style>
