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
                <button class="btn btn-primary" on-click={() => this.increment()}>
                    You clicked me {this.count} times.
                </button>
            );
        }
    };
</script>
