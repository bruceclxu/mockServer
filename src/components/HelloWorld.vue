<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>可参考文章</h2>
    <ul>
      <li>
        <a
          href="https://www.jianshu.com/p/9cfc5cdb0aeb"
          target="_blank"
        >
          json-server全攻略
        </a>
      </li>
    </ul>
    <h1>测试url</h1>
      <li>
        <a
          href="http://localhost:3000/data1"
          target="_blank"
        >
          http://localhost:3000/data1
        </a>
      </li>
    <h1>Tips</h1>
      <li>
        修改了db.json 后需要重启服务
      </li>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '这是一个mock 测试服务器'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
