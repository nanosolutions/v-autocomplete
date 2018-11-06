<template lang="html">
  <div>
    <span>{{item.name}}</span>
    <abbr>{{item.title}}</abbr>
</div>
</template>

<script>
export default {
  props: {
    item: { required: true }
  }
}
</script>
