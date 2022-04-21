<template>
  <section>
    <div class="card">
              <h5 class="card-header">Table <i class="bi bi-table" style="color:cornflowerblue;"></i> </h5> 
              <div class="description">
                This is about my Table from xlsx file
              </div>
              <div class="card-body">
                <DataTable></DataTable>
              </div>
    </div>
  </section>
</template>

<script>
import DataTable from '@/views/DataTable.vue';

export default ({
 name: 'MyTable',
  components: {
    DataTable,
  },
});

</script>

<style scoped>
.description{
  text-align: start;
}
/* .card{
  text-align: start;
} */
section{  background: url("https://i.ibb.co/Nmm9q3g/bg1.jpg") ;}
</style>


