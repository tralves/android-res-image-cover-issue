<template>
  <Page class="page" actionBarHidden="true" backgroundColor="#167dc3">
    <StackLayout>
      <Label width="200" height="200" text="huge" class="huge"/>
      <Label width="200" height="200" text="medium" class="medium"/>
      <Label width="100" height="100" text="small" class="small"/>
    </StackLayout>
  </Page>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
label {
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  margin: 10;
}
.huge {
  background-image: url('res://chesshuge');
}
.medium {
  background-image: url('res://chessmedium');
}
.small {
  background-image: url('res://chesssmall');
}
</style>
