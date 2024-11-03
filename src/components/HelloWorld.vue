<template>
  <div class="hello">
    <h1>ยินดีต้อนรับเข้าสู่เว็บไซด์ PhalconHost.com</h1>
    <p>
      ทดสอบการ deploy ด้วย vercel สำหรับใช้ในการพัฒนาซอฟต์แวร์ หากสนใจเช่าบริกา vps คุณภาพสูงในประเทศไทย สามารถสั่งซื้อผ่านหน้าเว็บไซด์ได้ที่
      <a href="https://www.phalconhost.com/promotion/vps/">เช่า vps</a>.
    </p>
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
</style>
