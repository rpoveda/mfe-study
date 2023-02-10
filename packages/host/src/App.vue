<template>
  <div class="container">
    <fieldset style="border:1px solid #7c7c7c; width:900px">
      <legend>Remote</legend>
      <Header teste="Send props" />
    </fieldset>
    <hr />
    <fieldset style="border:1px solid #6c6c6c; width:900px">
      <legend>Seccond</legend>
      <Pine />
    </fieldset>
  </div>
</template>

<script>
import Header from "remote/Header"
import Pine from "seccond/Pine"
export default {
  components: {
    Header,
    Pine
  }
}
</script>
