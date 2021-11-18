<script>
import {Doughnut} from 'vue-chartjs'
export default{
    extends: Doughnut,
    props: ["douOneData", "douOneOptions"],
    mounted(){
        this.renderChart(this.douOneData, this.douOneOptions);
    },
};
</script>
