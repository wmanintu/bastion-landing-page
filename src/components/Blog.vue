<template>
    <section class="light-bg">
        <div class="my-container">
            <h2 class="has-text-black has-text-centered has-text-weight-bold is-size-1">New On Our Blog</h2>
            <div class="columns">
                <div class="column is-half">
                    <div class="is-flex is-flex-direction-column has-background-white big-card">
                        <div class="big-card-image-wrapper">
                            <img src="../assets/dumbbells.jpg" alt="Image of gym dumbbells" />
                        </div>
                        <div class="columns is-justify-content-space-between is-align-items-center">
                            <div class="column is-three-fifths">
                                <h3 class="is-size-4 has-text-weight-bold has-text-black">Body Fat Spot Reduction Isn’t a
                                    Myth?</h3>
                            </div>
                            <div class="is-size-6 read-more-container">
                                <a class="is-flex" href="#">Read More <img class="pl-2"
                                        src="../assets/icon-arrow-circle.svg" alt="" /></a>
                            </div>
                        </div>

                    </div>
                </div>
                <div class="column is-half">
                    <div class="is-flex is-flex-direction-column is-justify-content-space-between height-100">
                        <div class="is-flex has-background-white small-card">
                            <div class="small-card-image-wrapper">
                                <img src="../assets/situp.jpg" alt="Image of woman doing situp"/>
                            </div>
                            <div class="small-card-text-wrapper">
                                <h3 class="is-size-4 has-text-weight-bold has-text-black">Body Fat Spot Reduction Isn’t a
                                    Myth?</h3>
                                    <div class="is-size-6 read-more-container">
                                <a class="is-flex" href="#">Read More <img class="pl-2"
                                        src="../assets/icon-arrow-circle.svg" alt="" /></a>
                            </div>
                            </div>
                        </div>
                        <div class="is-flex has-background-white small-card">
                            <div class="small-card-image-wrapper">
                                <img src="../assets/gym-class.jpg" alt="Image of woman in gym class"/>
                            </div>
                            <div class="small-card-text-wrapper">
                                <h3 class="is-size-4 has-text-weight-bold has-text-black">Body Fat Spot Reduction Isn’t a
                                    Myth?</h3>
                                    <div class="is-size-6 read-more-container">
                                <a class="is-flex" href="#">Read More <img class="pl-2"
                                        src="../assets/icon-arrow-circle.svg" alt="" /></a>
                            </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.my-container {
    padding-top: 8rem;
    padding-bottom: 16rem;
}

h2 {
    margin-bottom: 4.2rem;
}

.big-card, .small-card {
    border: 1.33px solid #D9D9D9;
}

.small-card-text-wrapper {
    padding: 4.25rem 6rem 2rem 2.68rem;
}

.big-card h3 {
    padding: 2rem;
    line-height: 120%;
}

.small-card h3 {
    padding-bottom: 2rem;
    line-height: 120%;
}

.big-card, .small-card {
    border-radius: 12px;
    overflow: hidden;
}

.big-card-image-wrapper, .small-card-image-wrapper {
    overflow: hidden;
    flex-shrink: 0;
}

.big-card-image-wrapper img {
    aspect-ratio: 10 / 5.2;
    object-fit: cover;
    object-position: center top;
    transform: scale(1.3);
}

.small-card-image-wrapper img {
    aspect-ratio: 1 / 1;
    width: 14rem;
    object-fit: cover;
    transform: scale(1.7);
}

.big-card .read-more-container {
    padding-right: 3rem;
}

.small-card .read-more-container {
    /* padding: 0 0 2rem 2.68rem; */
}

.read-more-container a {
    color: var(--font-dark-gray-color) !important;
    font-family: var(--font-4);
}
</style>