<template>
  <div>
    <quill-editor v-model="content" :options="editorOptions" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      content: '',
      editorOptions: {
        // Quill editor options go here
        theme: 'snow'
      },
    }
  },
}
</script>