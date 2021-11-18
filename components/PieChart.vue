<script>
import {Pie} from 'vue-chartjs'
export default{
    extends: Pie,
    props: ["pieData", "pieOptions"],
    mounted(){
        this.renderChart(this.pieData, this.pieOptions);
    },
};
</script>
