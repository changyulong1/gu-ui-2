<demo>
常规用法
</demo>
<template>
    <tabs v-model:selected="x">
        <Tab title="导航1">内容1</Tab>
        <Tab title="导航">内容2222222</Tab>
    </tabs>
</template>
<script lang="ts">
import Tabs from '../../lib/Tabs.vue'
import Tab from '../../lib/Tab.vue'
import { ref } from 'vue'
export default {
    components:{Tabs,Tab},
    setup() {
         const x = ref('导航1')
        return {x}
    },
}
</script>
