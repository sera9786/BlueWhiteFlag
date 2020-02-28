<template>
    <div>
        <canvas id="my-canvas" width="120" height="120"></canvas>
    </div>
</template>

<script>
export default{
    mounted:function (){
        this.draw();    
    },
    methods:{
        draw(){
            var ctx = document.getElementById("my-canvas").getContext("2d");
            ctx.beginPath();
            ctx.moveTo(10,10);
            ctx.lineTo(10,100);
            ctx.lineTo(100,100);
            ctx.closePath();
            ctx.fillStyle="blue";
            ctx.fill();
        }
    }
}
</script>