<template>
  <div class="hello">
    <tabbar>
      <tabbar-item>
        <img slot="icon" src="@/assets/tabIcon/home.png">
        <span slot="label">首页</span>
      </tabbar-item>
      <tabbar-item show-dot>
        <img slot="icon" src="@/assets/tabIcon/news.png">
        <span slot="label">资讯</span>
      </tabbar-item>
      <tabbar-item selected link="/component/demo">
        <img slot="icon" src="@/assets/tabIcon/mine.png">
        <span slot="label">我的</span>
      </tabbar-item>
    </tabbar>
  </div>
</template>

<script>
import { Tabbar, TabbarItem } from 'vux'

export default {
  name: 'HelloWorld',
  data () {
    return {
      
    }
  },
  components: {
    Tabbar,
    TabbarItem
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
