<template>
    <nav class="n-screen" style="">
        <div class="container-nav-one  grey-color flex justify-between items-center py-2.5 px-5">
            <div class="grey-color flex">
                <div class="flex justify-around items-center mr-20">
                    <img class="person mr-5" src="person.svg" alt="">
                    <img class="arrow flex mr-5" src="arrow.svg" alt="">
                    <img class="notification mr-5" src="notification.svg" alt="">
                </div>
                <div class="container-circle flex content-center justify-center">
                    <div class="circle flex content-center justify-center h-full mr-8"><a href="">ag</a></div>
                    <div class="circle flex content-center justify-center h-full mr-8"><a href="">fm</a></div>
                    <div class="circle flex content-center justify-center h-full mr-8"><a href="">R16</a></div>
                    <div class="circle flex content-center justify-center h-full mr-8"><a href="">op</a></div>
                </div>
            </div>
            <div class="container-circle flex justify-end">
                <div class="cicle-content flex content-center justify-center h-full mr-8"><a href="">ov2</a></div>
            </div>
        </div>
        <div class="grey-color flex py-1 px-3 pb-2 items-center">
            <div class=" grey-color flex flex-row w-full">
                <div class="flex items-center">
                    <img class="glass flex mr-4 h-full items-center" src="magnifyingGlass.svg" alt="">
                    <p class="search flex mr-32 h-full items-center">Buscar</p>
                </div>
                <div class="flex items-center"> 
                    <img class="square flex flex-row mr-3 h-full items-center" src="square.svg" alt="">
                    <p class="dash flex mr-16 h-full items-center">Dashboard</p>
                </div>
                <div class="w-full px-2 " style="background-color: #494949;">
                    <img class="h-8 w-8 flex mr-5" src="more.svg" alt="">
                </div>
            </div>
        </div>
    </nav>

</template>

<style>
.person{
    width: 40px;
    height: 40px;
    background-color: #494949;
    border-radius: 50px;
}
.grey-color{
    background-color: #282828;
}
.arrow{
    width: 13px;
    height: 13px;
}
.notification{
    width: 30px;
    height: 30px;
    color:#494949;
}
.circle{
    background-color: #494949;
    border-radius: 50px;
    color:#ffffff;
    width: 40px;
    height: 40px;
    padding: 5px;
    text-transform: uppercase;
    max-width: 40px;
    max-height: 40px;
    text-align: center;
}
.cicle-content{
    background-color: #cacaca;
    border-radius: 50px;
    color:#282828;
    width: 60px;
    height: 60px;
    padding: 10px;
    text-transform: uppercase;
    max-width: 60px;
    max-height: 60px;
    text-align: center;
    font-size: 25px;
}
.glass{
    width: 25px;
    height: 25px;
}
.search{
    color: #f19e04;
}
.square{
    width: 25px;
    height: 25px;
}
.dash{
    color:#838383;
}
</style>