<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<style>
.wrapper{
  max-width: 400px; 
  border: 2px solid black; 
  display: incline flex; 
  background-color: lightblue; 
  text-align: center;
}
img{
  width: 400px; 
}
.buttons button:hover {
  background-color: rgba(1,1,1,1);
  color: white;   
}


.btn{
  margin: 16px; 
}


@media screen and (max-width:500px){
  .wrapper{
    font-size: 5vw;
  }
  
} 

</style>


