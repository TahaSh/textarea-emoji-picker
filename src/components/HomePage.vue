<template>
  <div class="home-page">
    <textarea-emoji-picker
      v-model="text"
    />
  </div>
</template>

<script>
import TextareaEmojiPicker from './TextareaEmojiPicker'

export default {
  name: 'HomePage',
  components: { TextareaEmojiPicker },
  data () {
    return {
      text: ''
    }
  }
}
</script>

<style scoped>
.home-page {
  padding-top: 50px;
}
</style>
