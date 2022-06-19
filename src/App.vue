<script setup>
  import { createApp } from 'vue'
	import Tabs from './components/Tabs.vue'
	import Tab from './components/Tab.vue'
</script>

<template>
	<Tabs>
  	<Tab active="true" title="First Tab">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce gravida purus vitae vulputate commodo.
    </Tab>
  	<Tab title="Second Tab">
      Cras scelerisque, dolor vitae suscipit efficitur, risus orci sagittis velit, ac molestie nulla tortor id augue.
    </Tab>
  	<Tab title="Third Tab">
      Morbi posuere, mauris eu vehicula tempor, nibh orci consectetur tortor, id eleifend dolor sapien ut augue.
    </Tab>
  	<Tab title="Fourth Tab">
      Aenean varius dui eget ante finibus, sit amet finibus nisi facilisis. Nunc pellentesque, risus et pretium hendrerit.
    </Tab>
  </Tabs>
</template>