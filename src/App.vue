<script>
    import ButtonCounter from "./components/ButtonCounter.vue";

    export default {
        components: { ButtonCounter },
        data() {
            return {
                title: "Vuejs & Parcel & JSX"
            };
        },
        render(h) {
            return (
                <div>
                    <h1>{this.title}</h1>
                    <ButtonCounter />
                </div>
            );
        }
    };
</script>

<style lang="scss" scoped>
    .container {
        color: blue;
    }
</style>
