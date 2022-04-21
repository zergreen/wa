<template>
    <div>
        hello
    </div>
    <h1 class="text-center" style="color: white; margin-top: 240px">
            UPLOAD YOUR FILE.<br>
            <button type="button" class="btn btn-outline-secondary">
              <input type="file" id="files" ref="files" multiple v-on:change="handleFilesUpload()" />
            </button>
          </h1>

</template>

<script>
// import {  } from '@vue/composition-api'

export default {
    name: 'MyHome',

}
</script>

<style scoped>

</style>