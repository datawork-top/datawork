<template>
  <div>
    <svg-icon icon-class="github" @click="goto"/>
  </div>
</template>

<script>
export default {
  name: 'DataworkGit',
  data() {
    return {
      url: 'https://github.com/datawork-top/datawork-portal'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
