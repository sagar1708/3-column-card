<template>
  <div>
    <div class="container">
      <div class="row align-items-center">
        <div class="col-4" style="background-color:hsl(31, 77%, 52%)">
          <div class="p-5">
            <div class="container">
              <div class="row">
                <div class="p-4">
                  <img src="/assets/icon-sedans.svg">
                </div>
              </div>
              <div class="row">
                <div class="p-4">
                  <span class="text-white" style="font-family:Lexend Deca; font-size:35px">
                    SEDANS
                  </span>
          
                </div>
              </div>
              <div class="row">
                <div class="col-12 text-left p-4">
                <span class="text-white">
                Choose a sedan for its affordability and excellent fuel economy.
                </span>

                </div>
              </div>
              <div class="row">
                <div class="p-4">
                <button class="text-warning" style="border-radius: 30px;">Learn more</button>
                

                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col-4" style="background-color:hsl(184, 100%, 22%)">
          <div class="p-5">
            <div class="container">
              <div class="row">
                <div class="p-4">
                <img src="/assets/icon-suvs.svg" alt="">
                </div>
              </div>
              <div class="row">
                <div class="p-4">
                  <span class="text-white" style="font-family:Lexend Deca; font-size:35px">
                    SUVs
                  </span>
                </div>
              </div>
              <div class="row">
                <div class="col-12 text-left p-4">
                <span class="text-white">
                  Take an SUV for its spacious interior, power and versatility.
                </span>

                </div>
              </div>
              <div class="row">
                <div class="p-4">
                <button class="text-info" style="border-radius: 30px">Learn more</button>

                </div>
              </div>
            </div>
          </div>
        </div> 
        

        <div class="col-4" style="background-color:hsl(179, 100%, 13%)">
          <div class="p-5">
            <div class="container">
              <div class="row">
                <div class="p-4">
                  <img src="/assets/icon-luxury.svg" alt="">
                </div>
              </div>
              <div class="row">
                <div class="col-12 text-left p-4">
                  <span class="text-white" style="font-family: Lexend Deca; font-size:35px">
                    LUXURY
                  </span>
                </div>
              </div>
              <div class="row">
                <div class="col-12 text-left p-4">
                  <span class="text-white">
                    Cruise in the best car brands without the bloated prices.
                  </span>

                </div>
              </div>
              <div class="row">
                <div class="p-4">
               <button class="text-primary" style="border-radius: 30px">Learn more</button>

                </div>
              </div>
            </div>
          </div>
          </div>
      </div>
    </div>
  </div>
        
      
    

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.text-white {
  text-align: left;
  font-family: Big Shoulders Display;
  }
  
</style>
