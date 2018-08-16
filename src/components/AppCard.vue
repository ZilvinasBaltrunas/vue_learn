<template>
    <div class="card">
        <div class="card-image">
            <img :src="imageInside" alt="e">
        </div>
        <div class="card-content">
            <div class="media">
                <div class="media-content">
                    <p class="title is-4">{{title}}</p>
                    <p class="subtitle is-6">@johnsmith</p>
                </div>
            </div>

            <div class="content">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Phasellus nec iaculis mauris. <a>@bulmaio</a>.
            </div>
        </div>
    <AppButton>Spausk Batona</AppButton>
    </div>
</template>

<script>
import AppButton from './AppButton.vue'

export default {
    name: "AppCard",
    props: {
        imageInside: String,
        title: String
    },
    components: {
        AppButton
    }
    
}
</script>
