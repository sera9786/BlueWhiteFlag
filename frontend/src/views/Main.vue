<template>
    <div>
      <div>
        <h1>청기백기 게임 만들기</h1> 
      </div>

      <div>
        백
          <LeftFlag/>
      </div>
      
      <div>
        <Character/>
      </div>
      <!-- <div>
        청
        <RightFlag/>
      </div> -->
    </div>
</template>

<script>
import Character from '../components/Character'
// import RightFlag from '../components/RightFlag'
import LeftFlag from '../components/LeftFlag'

export default {
  name: 'App',
  components: {
    Character,
    // RightFlag,
    LeftFlag
  }
}
</script>

<style>
 h1{ 
  text-align: center;
 }
</style>