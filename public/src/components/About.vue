<template>
  <v-layout wrap pa-2>
    <v-flex xs12>
      <h1>Ethereum Network - The Hitchhiker's Guide to the Ethereum Blockchain</h1>
      <p>Ethereum Network  is dedicated to foster and improve Ethereum and general blockchain ecosystem. We are independent from the <a href="https://ethereum.org/" target="_blank">Ethereum Foundation</a>, <a href="https://consensys.net/" target="_blank">ConsenSys</a> and the <a href="https://entethalliance.org/"" target="_blank">Enterprise Ethereum Alliance</a>, but support developers and users in other ways:</p>
      <p>Our <router-link to="/learn">learn page</router-link>  is a huge, but curated and up-to-date list of everything you possibly need to develop on Ethereum, from introduction videos for beginners to deep dive tutorials on scaling solutions and privacy technologies.</br>
      The <router-link to="/projects">project list</router-link> gives an overview of all Ethereum related projects, searchable by their names, industries, topics, and other criteria. URLs can link directly to the <router-link to="/project/AKASHA">project details</router-link> or <router-link to="/projects?q=prediction market">search queries</router-link>. It's more a tool to find ideas and people with similar interests to form connections and work together, rather than a list to brag how many projects exist on Ethereum. So you will also find <router-link to="/projects?q=abandoned">abandoned</router-link> projects and the ones which never made it past the idea stage.</br>
      The <router-link to="/explorer">explorer</router-link>(in progress) let you analyze the Ethereum blockchain in detail, see transactions coming in in real time, verify smart contract code and view statistics.</br>
      To connect with your local Ethereum community, you can use our <router-link to="/map">map</router-link>(in progress) to find nearby meetups, local cash traders and nodes close to you. For finding your way around the rapidly expanding, worldwide online community of Ethereum, our <router-link to="/social">media team</router-link> gathers the most important blockchain news of each day, finds the most engaged online communities and reports from Ethereum meetups around the world in our <a href="https://blog.ethereum.network/latest" target="_blank">blog</a>.</p>
      The plan is to turn Ethereum Network into a fully decentralized community project with the help of Colony, Aragon, or similar.
    </v-flex>
  </v-layout>
</template>

<script>
export default {
  name: 'about',
  props: ['searchField'],
  data () {
    return {
      msg: 'the network explorer is in the works...'
    }
  }
}
</script>

<style>
.profilePic {
  padding: 5px;
}
</style>
