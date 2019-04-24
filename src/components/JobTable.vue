<template>
  <v-container>
    <v-layout row text-xs-center wrap>
      <v-flex xs12 d-flex justify-space-between>
        <JobSearch />
        </v-flex>
      <v-flex xs12>
        <JobsList />
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import JobsList from './JobsList';
import JobSearch from './JobSearch';

export default {
  components: {
    JobsList,
    JobSearch
  },
  data: () => ({
    
  })
};
</script>

<style>
</style>
