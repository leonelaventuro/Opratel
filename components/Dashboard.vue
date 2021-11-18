<template>
    <div class="flex flex-col justify-center mx-7">
        <h1 class="text -m-2 my-7">Dashboard</h1>
        <div class=" flex h-full mb-5">
            <div class="container-title mr-5 w-full">
                <div><p class="title justify-center mb-3">Titulo</p></div>
                <div class="flex flex-row justify-between">
                    <div class="flex flex-col mr-10 items-center" >
                        <div class="w-44"><Doughnut :douOneData="douOneData" /></div>
                        <p class="description ">Description</p>
                    </div>
                    <div class="flex flex-col mr-10 items-center">
                        <div class="w-44"><Doughnut :douOneData="douOneData" /></div>
                        <p class="description ">Description</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <div class="w-44"><Doughnut :douOneData="douOneData" /></div>
                        <p class="description">Description</p></div>
                    </div>
                </div>
            <div class="container-altas  flex flex-col">
                <div class="flex flex row justify-around ">
                    <div class="mb-2">
                        <p class=" title mb-6">Altas</p>
                        <div class=" content-arrowup mb-4">
                            <img class="arrowup" src="arrowup.svg" alt="">
                        </div>
                        <div>
                            <p style="color: #ffffff">+40.000</p>
                        </div>
                    </div>
                    <div class="mb-2">
                        <p class="title mb-6">Bajas</p>
                        <div class="content-arrowdown flex justify-around mb-4">
                            <img class="" src="arrowup.svg" alt="">
                        </div>
                        <div class=" ">
                            <p style="color: #ffffff">-3.700</p>
                        </div>
                    </div>
                </div>
                
                <div class="flex text-center mt-6">
                    <p style="color: #ffffff">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
            </div>
        </div>
        <div class="container-title mb-5 flex justify-center flex-col">
            <div><p class="title flex flex-row w-full justify-center mb-3">Titulo</p></div>
            <div class="flex flex-row justify-center w-full">
                <div class=" w-full flex justify-center items-center">
                    <PieChart :pieData="pieData" />
                </div>
                <div class=" flex w-full flex-col justify-center">
                    <div class="flex w-full">
                        <div class="color-orange style-color"></div>
                        <p style="color: #ffffff">Lorem ipsum dolor sit amet</p>
                    </div>
                    <div class="flex w-full">   
                        <div class="color-violet style-color"></div>
                        <p style="color: #ffffff">Lorem ipsum dolor sit amet</p>
                    </div>
                    <div class="flex w-full">   
                        <div class="color-lightblue style-color"></div>
                        <p style="color: #ffffff">Lorem ipsum dolor sit amet</p>
                    </div>
                    <div class="flex w-full">  
                        <div class="color-blue style-color"></div>
                        <p style="color: #ffffff">Lorem ipsum dolor sit amet</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="flex justify-center w-full">
            <div class="container-three w-full flex flex-col mr-5">
                <p class="title w-full flex justify-center mb-3">Titulo</p>
                <div class=" flex w-full flex-col">
                    <div class="rounded-none flex w-full">
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>
                        <div class="style-color description-one"></div>
                        <p class="description-bar" style="color: #ffffff">71</p>
                    </div>
                    <div class=" flex w-full">   
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>
                        <div class=" style-color description-two"></div>
                        <p class="description-bar" style="color: #ffffff">139</p>
                    </div>
                    <div class=" flex w-full">
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>   
                        <div class=" style-color description-three"></div>
                        <p class="description-bar" style="color: #ffffff">54</p>
                    </div>
                    <div class=" flex w-full"> 
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div> 
                        <div class=" style-color description-four"></div>
                        <p class="description-bar" style="color: #ffffff">62</p>
                    </div>
                    <div class=" flex w-full">
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>  
                        <div class=" style-color description-five"></div>
                        <p class="description-bar" style="color: #ffffff">27</p>
                    </div>
                    <div class=" flex w-full"> 
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>  
                        <div class=" style-color description-six"></div>
                        <p class="description-bar" style="color: #ffffff">96</p>
                    </div>
                    <div class=" flex w-full"> 
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>   
                        <div class=" style-color description-seven"></div>
                        <p class="description-bar" style="color: #ffffff">154</p>
                    </div>
                    <div class=" flex w-full"> 
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>   
                        <div class=" style-color description-eight"></div>
                        <p class="description-bar" style="color: #ffffff">48</p>
                    </div>
                    <div class=" flex w-full">
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>    
                        <div class=" style-color description-nine"></div>
                        <p class="description-bar" style="color: #ffffff">73</p>
                    </div>
                    <div class=" flex w-full">
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>    
                        <div class=" style-color description-ten"></div>
                        <p class="description-bar" style="color: #ffffff">113</p>
                    </div>
                </div>
            </div>
            <div class="container-three w-full flex flex-col">
                <p class="title w-full flex justify-center mb-3">Titulo</p>
                <div class=" flex w-full flex-col">
                    <div class="rounded-none flex w-full">
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>
                        <div class="style-color description-one"></div>
                        <p class="description-bar" style="color: #ffffff">71</p>
                    </div>
                    <div class=" flex w-full">   
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>
                        <div class=" style-color description-two"></div>
                        <p class="description-bar" style="color: #ffffff">139</p>
                    </div>
                    <div class=" flex w-full">
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>   
                        <div class=" style-color description-three"></div>
                        <p class="description-bar" style="color: #ffffff">54</p>
                    </div>
                    <div class=" flex w-full"> 
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div> 
                        <div class=" style-color description-four"></div>
                        <p class="description-bar" style="color: #ffffff">62</p>
                    </div>
                    <div class=" flex w-full">
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>  
                        <div class=" style-color description-five"></div>
                        <p class="description-bar" style="color: #ffffff">27</p>
                    </div>
                    <div class=" flex w-full"> 
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>  
                        <div class=" style-color description-six"></div>
                        <p class="description-bar" style="color: #ffffff">96</p>
                    </div>
                    <div class=" flex w-full"> 
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>   
                        <div class=" style-color description-seven"></div>
                        <p class="description-bar" style="color: #ffffff">154</p>
                    </div>
                    <div class=" flex w-full"> 
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>   
                        <div class=" style-color description-eight"></div>
                        <p class="description-bar" style="color: #ffffff">48</p>
                    </div>
                    <div class=" flex w-full">
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>    
                        <div class=" style-color description-nine"></div>
                        <p class="description-bar" style="color: #ffffff">73</p>
                    </div>
                    <div class=" flex w-full">
                        <div><p class="description-bar mr-5">Lorem ipsum dolor</p></div>    
                        <div class=" style-color description-ten"></div>
                        <p class="description-bar" style="color: #ffffff">113</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="container-title w-full flex justify-center ">
            <LineChart :width="1200" :chartData="chartData" />
        </div>
    </div>
</template>

<script>
export default{
    data(){
        return{
            chartData:{
                labels: ["1/01/2021", "1/01/2021", "1/01/2021", "1/01/2021", "1/01/2021", "1/01/2021", "1/01/2021", "1/01/2021", "1/01/2021", "1/01/2021", "1/01/2021",],
                datasets:[
                    {
                        label: "Numbers", 
                        borderColor: "#330086",
                        borderWidth:0,
                        pointBackgroundColor: "#4bcc96",
                        pointRadius:4,
                        pointHoverRadius: 8,
                        pointHoverBorderColor:"#000",
                        fill: false,
                        data:[70, 50, 47, 48, 47, 50, 80, 49, 54, 55, 60],
                        backgroundColor: ["#330086", "#f19e04","#330086", "#f19e04","#330086", "#f19e04","#330086", "#f19e04","#330086", "#f19e04","#330086"]
                    },
                ],
            },
            chartOptions:{
                maintainAspectRatio: false,
                responsive: true,
                    tooltips:{
                        titleFontColor: "#ffffff",
                        bodyFontColor: "#ffffff",
                        backgroundColor: "#00055e",
                        position: "nearest",
                        mode: "nearest",
                        intersect: 0,
                        bodySpacing: 10,
                        xPadding:20,
                    },
            },
            pieData:{
                labels: ["41,87%", "8,24%", "37,5%", "12;5%"],
                datasets:[
                    {
                        label: "Numbers", 
                        borderColor: "#4bcc96",
                        borderWidth:0,
                        pointBackgroundColor: "#4bcc96",
                        pointRadius:4,
                        pointHoverRadius: 8,
                        pointHoverBorderColor:"#000",
                        fill: false,
                        data:[100, 150, 300, 200],
                        backgroundColor: ["#f19e04","#330086","#008ca5","#3a3afb"]
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
            douOneData:{
                labels: ["41,87%", "8,24%", "37,5%", "12;5%"],
                datasets:[
                    {
                        label: "Numbers", 
                        borderColor: "#4bcc96",
                        borderWidth:0,
                        pointBackgroundColor: "#4bcc96",
                        pointRadius:4,
                        pointHoverRadius: 8,
                        pointHoverBorderColor:"#000",
                        fill: false,
                        data:[100, 150, 300, 200],
                        backgroundColor: ["#f19e04","#330086","#008ca5","#3a3afb"],
                         
                    },
                ],
            },
            douOneOptions:{
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
    .text{
        color: #f19e04;
        font-size: 30px;
    }
    .container-title{
        background-color:#2a2a2a; 
        padding: 15px;
        border-radius: 10px;
    }
    .container-altas{
        background-color:#2a2a2a;
        padding: 15px;
        border-radius: 10px;
    }
    .title{
        color: #ffffff;
        font-size: 30px;
        font-weight: 700;
        display: flex;
    }
    .description{
        color:#ffffff;
        font-size: 24px;
        font-weight: 500;
    }
    
    .content-arrowup{
        background-color:#01499d;
        width: 70px;
        height: 70px;
        border-radius: 100px;
    }
    .content-arrowdown{
        background-color:#f19e04;
        width: 70px;
        height: 70px;
        border-radius: 100px;
        transform: rotate(180deg);
    }
    .style-color{
         margin: 0 15px 20px 0;
    }
    .color-orange{
        background-color:#f19e04;
        width: 30px;
        height: 30px;
        max-width: 30px;
        max-height: 30px;
        border-radius: 100px;
       
    }
    .color-violet{
        background-color: #330086;
        width: 30px;
        height: 30px;
        border-radius: 100px;
        max-width: 30px;
        max-height: 30px;
    }
    .color-lightblue{
        background-color:#008ca5;
        width: 30px;
        height: 30px;
        border-radius: 100px;
        max-width: 30px;
        max-height: 30px;
    }
    .color-blue{
        background-color:#00005c;
        width: 30px;
        height: 30px;
        border-radius: 100px;
        max-width: 30px;
        max-height: 30px;
    }
    .description-bar{
        color:#ffffff;
        font-size: 18px;
        font-weight: 500;
    }
    .container-three{
        background-color:#2a2a2a; 
        padding: 15px;
        border-radius: 10px;
        margin-bottom: 30px;
    }
    .description-one{
        background-color:#f19e04;
        width: 190px;
        height: 30px;
    }
    .description-two{
        background-color:#3a3afb;
        width: 260px;
        height: 30px;
    }
    .description-three{
        background-color:#330086;
        width: 120px;
        height: 30px;
    }
    .description-four{
         background-color:#008ca5;
        width: 150px;
        height: 30px;
    }
    .description-five{
         background-color:#f19e04;
        width: 70px;
        height: 30px;
    }
    .description-six{
 background-color:#3a3afb;
        width: 220px;
        height: 30px;
    }
    .description-seven{
 background-color:#330086;
        width: 320px;
        height: 30px;
    }
    .description-eight{
 background-color:#008ca5;
        width: 100px;
        height: 30px;
    }
    .description-nine{
 background-color:#f19e04;
        width: 180px;
        height: 30px;
    }
    .description-ten{
 background-color:#330086;
        width: 240px;
        height: 30px;
    }
</style>