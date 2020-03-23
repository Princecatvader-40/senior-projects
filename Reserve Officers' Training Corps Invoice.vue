<!-- Your Vuetify code -->
<template>
  <div >
        <h1>Reserve Officers' Training Corps Invoice</h1>
   
    <v-container >

          
      <div>
        <v-row no-gutters="">
          <v-col cols="6" md="4" xs="12">
            <v-img
              src="https://sv1.picz.in.th/images/2020/03/06/xy798I.png"
              class="my-3"
              max-width="300"
              max-height="100"
            >
            </v-img>
          </v-col>
          
          <v-col cols="10">
            <ul>
              <h1 class="headline text-uppercase font-italic font-weight-bold">
                invoice
              </h1>
              <h6>Invoice No#</h6>
              <h6>Issue date :</h6>
              <h6>Due Date :</h6>
            </ul>

            <ul>
              <h5>
                name: 
              </h5>
              <h5>
                Grade: 6
              </h5>
              <h5>
                Student number:
              </h5>
            </ul>
          </v-col>
        </v-row>
      </div>
      <div>
    <v-simple-table height="300px">
    <template v-slot:default>
      <thead>
        <tr>
          <th class="text-left">Name</th>
          <th class="text-left">Amount</th>
        </tr>
      </thead>
      <tbody>
        <tr v-for="item in desserts" :key="item.name">
          <td>{{ item.name }}</td>
          <td>{{ item.calories }}</td>
        </tr>
      </tbody>
    </template>
  </v-simple-table>
  </div>
    </v-container>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>