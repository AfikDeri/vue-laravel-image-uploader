<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-9">
                <div class="card card-default">
                    <div class="card-header">Example Component</div>

                    <div class="card-body">
                        <image-uploader></image-uploader>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import ImageUploader from './ImageUploader';
    export default {
        mounted() {
            console.log('Component mounted.')
        },
        components: {
            ImageUploader
        }
    }
</script>

<style lang="sass">
@import '~vue-toastr/src/vue-toastr.scss';
</style>

