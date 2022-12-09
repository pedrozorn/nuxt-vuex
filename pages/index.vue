<template>
  <section class="container">
    <div>
      <!-- <p>{{ $store.state.message}}</p> -->
      <p>{{ $store.state.hello.message }}</p>
      <!-- <button v-on:click="$store.commit('updateMessage','')">Update</button> -->
      <!-- <button v-on:click="$store.commit('updateMessage', 'commit with pay load')">Update</button> -->
      <!-- <button v-on:click="$store.dispatch('updateMessageAction')">dispatch</button> -->
      <button v-on:click="$store.dispatch('hello/updateMessageAction','hikisuuwatasi')">dispatch</button>
    </div>
  </section>
</template>

<script>

export default {
}
</script>
