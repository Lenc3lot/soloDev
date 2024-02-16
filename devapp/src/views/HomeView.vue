<template>
  <main>
    <div id="homeAccueil">
      <h2>Bienvenue sur Etu'Connect !</h2>
      <p>Le site de vote des étudiants de 2TSSIO !</p>
    </div>
  </main>
</template>

<script>
// import store from '@/store'
export default {
  name: 'HomeView',
  head () {
    return {
      title: 'Document',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Your Page Description'
        }
      ]
    }
  },
  components: {
    // components here
  },
  props: {
    // props here
  },
  watch: {
    // variables to watch here
  },
  data () {
    return {
      // variables here
      // dataStore: store
    }
  },
  methods: {
    // methods here
  },
  mounted () {
    // mounted here
  },
  created () {
    // created here
  }
}
</script>

<style scoped>
/* Style here */
#homeAccueil{
  align-items: center;
  background-color:white;
  border: solid 1px;
  border-radius: 10px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin: 1%;
  padding: 1%;
  width: 30%;
}

#homeAccueil>h2{
  flex: 1 1 100%;
  text-align: center;
  color: black;
}
</style>
