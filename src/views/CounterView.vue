<script>
 export default{
        name: 'CounterView',
        data(){
            return{
                count: 0
            }
        },
        methods:{
            increment(){
                this.count++
            },
            decrement(){
                this.count--
            },
            reset(){
                this.count = 0
            },
            setvalue(value){
                this.count = value
            }
        }
 }
</script>

<template>
    <div class="counter">
        <h1 class="count-header">Count: {{ count }}</h1>
        <button class="btn-inc" @click="increment">Increase</button>
        <button class="btn-dec" @click="decrement">Decrease</button>
        <button class="btn-rs" @click="reset">Reset</button>
        <button class="btn-sv" @click="setvalue(count)">Set Value</button>
        <input class="impt" type="number" v-model.number="count" />
        <p v-if="count>=10">You are hiking too high</p>
        <p v-if="count <=-1"> You are diving too deep!</p>

    </div>
</template>

 <style>
  .counter{
        text-align: center;
        margin-top: 1.5rem;
  }
  


button{
    background-color: rgba(198,123,17,1);
    color:whitesmoke;
    border: none;
    padding: 10px 20px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
    border-radius: 5px;}

/* CSS */




button:hover,
button:focus {
  background-color: #660da2;
  color: rgba(198,123,17,1);
}
.impt{
    background-color: rgba(198,123,17,1);
    color:whitesmoke;
    border: none;
    padding: 10px 20px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
    border-radius: 5px;
    margin-top: 100px;

}
.count-header{
    color: rgba(198,123,17,1);
    font-size: 30px;
    font-weight: bold;
    text-align: center;
    padding: 0px;
}
.impt:hover{
    background-color: #660da2;
    color:rgba(198,123,17,1);
}
  
</style>