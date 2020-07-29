<template>
  <div>
      <section class="name">
          <h1>{{ fullName }}</h1>
      </section>
  </div>

</template>

<script>
export default {
    data() {
        return {
            fullName: 'Ofurum Chiagoziem'
        }
    }

}
</script>

<style scoped>
.name{
    display: flex;
    justify-content: center;
    align-items: center;
    color: rgb(96, 96, 148)
}

</style>