<template>
  <!-- counter // hide-details -->
  <client-only>
    <div>
      <v-file-input
        chips
        multiple
        show-size
        label="첨부파일업로드"
        placeholder="파일을 선택해주세요."
        variant="outlined"
        counter
      />
    </div>
  </client-only>
</template>
<script>
export default {
  name: 'CompUpload',
}
</script>

<style lang="scss" scoped></style>
