<template>
  <div class="person">
    <h2>姓名：{{name}}</h2>
    <h2>年龄：{{age}}</h2>
    <h2>电话：{{tel}}</h2>
    <button @click="changeName">修改名字</button>
    <button @click="showTel">展示联系方式</button>
  </div>
</template>

<script lang="ts">
  export default {
    name:'Person',
    data() {
        return {
          name:'张三',
          age: 18,
          tel:'13888888'
        }
    },
    methods: {
      changeName(){
        this.name = '李四';
      },
      showTel() {
        alert(this.tel);
      }
    }
  }
</script>

<style scoped>
</style>