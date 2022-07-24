<template>
<div class="container mt-5">
  <div class="row mb-3" style="min-height: calc(30vh);">
    <div class="col-12">
      <div class="card" style="width: 100%; height: 100%;">
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
        </div>
      </div>
    </div>
  </div>
  <div class="row mb-5" style="min-height: calc(80vh);">
    <div class="col-7">
      <InvoiceInput/>
    </div>
    <div class="col-5">
      <div class="card mb-2" style="width: 100%; height: 100%;">
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
        </div>
      </div>
      
    </div>
  </div>
</div>
  
</template>

<script>
import InvoiceInput from './components/Main/InvoiceInput.vue'

export default {
  name: 'App',
  components: {
    InvoiceInput,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.card{
    box-shadow: 0px 3px #838383;
}
</style>
