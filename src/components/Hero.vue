<template>
    <section>
        <div class="myContainer">
            <div class="columns main-bg">
                <div class="column is-three-fifths">
                    <h1>Better Than Personal Training.</h1>
                    <h2 class="py-5">
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
                            <img
                                src="../assets/right-arrow.svg"
                                alt="Right arrow icon"
                            />
                        </button>
                    </div>
                </div>
                <div class="column is-relative">
                    <img
                        class="dots-narrow"
                        src="../assets/hero-dots-narrow.svg"
                        alt="Decorative dots image"
                    />
                    <img
                        class="dots-wide"
                        src="../assets/hero-dots-wide.svg"
                        alt="Decorative dots image"
                    />
                    <div class="video-wrapper">
                        <video
                            src="../assets/hero.mp4"
                            autoplay
                            loop
                            muted
                        ></video>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
section {
    padding-top: 5rem;
}

h1 {
    color: #000;
    font-family: var(--font-primary);
    font-size: 5rem;
    font-style: normal;
    font-weight: 700;
    line-height: 120%; /* 6rem */
    letter-spacing: 0.1875rem;
}

h2 {
    color: #000;
    font-family: var(--font-secondary);
    font-size: 2.5rem;
    font-style: normal;
    font-weight: 400;
    line-height: 140%; /* 3.5rem */
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
    right: 0;
    top: -2.5rem;
}

.dots-wide {
    left: -11rem;
    bottom: -0.5rem;
}
</style>
