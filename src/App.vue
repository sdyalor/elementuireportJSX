
<script lang="tsx">
import Vue from "vue";
import HelloWorld from "./components/HelloWorld.vue";
import lang from 'element-ui/lib/locale/lang/en.js'
import locale from 'element-ui/lib/locale'
import {Aside,Container,Select, Menu, Divider, Button} from "element-ui"

locale.use(lang)

export default Vue.extend({
  name: "App",
  render: h => {
   /* 
    <Aside>
      <Menu>
      <Select></Select>
      </Menu>
    </Aside>
    */
   /*
   h('Aside',
     {
       class:{container:true},
       style:{
         background: 'green',
        //  width: '100px'
       }
      //  attrs:{width:'10px'}
     },
     ['hellow']
   )
   */
  return (<Aside
  data={{class:{container:true}}}
  // {..{data}}
  
  // data={{class:{container:true},style:{background:'green'}}}
  // className="container"
  // propsData={{class:{container:true}}}
   >
   render
   </Aside>)
  }
});
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.container {
  width: 400px;
  background-color: #78a1ca;

}
</style>
