<script>
    export default {
        data() {
            return {
                count: 0
            };
        },
        methods: {
            increment() {
                this.count++;
            }
        },
        render(h) {
            return (
                <button on-click={() => this.increment()}>
                    You clicked me {this.count} times.
                </button>
            );
        }
    };
</script>
