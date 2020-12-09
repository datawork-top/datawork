<template>
  <div>
    <svg-icon icon-class="question" @click="goto"/>
  </div>
</template>

<script>
export default {
  name: 'DataworkDoc',
  data() {
    return {
      url: 'http://datawork.top/doc'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
