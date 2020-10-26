<template>
  <div id="app">
  </div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      todos: [
        {id: 1,
        title: "Go to the Gym",
        completed: false
        },
        {id: 2,
        title: "Walk Dog",
        completed: false
        },
        {id: 3,
        title: "Go shopping",
        completed: false
        },
        {id: 4,
        title: "Call the vet",
        completed: false
        }
      ]
    }
  }

}
</script>

<style>

</style>
