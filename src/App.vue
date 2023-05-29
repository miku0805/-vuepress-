<template>
  <v-md-editor :model-value="markdown"></v-md-editor>
</template>

<script>
export default {
  data() {
    return {
      markdown: '',
    };
  },
};
</script>