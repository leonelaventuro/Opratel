<template>
  <div>
    <h1 class="title">Vue Chart</h1>
    <div class="chart-div">
        <LineChart :chartData="chartData" />
    </div>
  </div>
</template>

<script>
export default{
    data(){
        return{
            pieData:{
                labels: ["Juan", "Feb", "Mar", "April"],
                datasets:[
                  {
                    label: "Numbers", 
                    borderColor: "#4bcc96",
                    borderWidth:4,
                    pointBackgroundColor: "#4bcc96",
                    pointRadius:4,
                    pointHoverRadius: 8,
                    pointHoverBorderColor:"#000",
                    fill: false,
                    data:[100, 150, 300, 200],
                  },
                ],
            },
          pieOptions:{
            maintainAspectRatio: false,
            responsive: true,
            tooltips:{
              titleFontColor: "#ffffff",
              bodyFontColor: "#ffffff",
              backgroundColor: "#00055e",
              position: "nearest",
              mode: "nearest",
              intersect: 0,
              bodySpacing: 4,
              xPadding:20,
            },
          },
        };
    },
};
</script>

<style>
 .title{
   color: tomato;
 }
  .chart-div{
  width: 400px;
  height: 400px;  
  }
</style>