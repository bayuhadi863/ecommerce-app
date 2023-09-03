<template>
  <section class="py-5">
    <h1 class="text-center heading">Our Services</h1>
    <div class="d-flex justify-content-center mt-4">
      <div class="col-1 bg-red" style="height: 5px"></div>
    </div>
    <div class="container mt-5 pt-5">
      <div class="row row-cols-1 row-cols-md-2 row-cols-lg-4 g-4">
        <div v-for="(service, index) in about" :key="index" class="col">
          <div class="card h-100 py-5">
            <div class="card-body d-flex flex-column align-items-center gap-4">
              <fa :icon="['fas', service.icon]" size="3x" />
              <h5 class="card-title text-center">{{ service.title }}</h5>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  data() {
    return {
      // Daftar task
      about: [
        {
          icon: 'truck',
          title: 'Delivery Services',
        },
        {
          icon: 'arrow-right-arrow-left',
          title: 'Shipping & Return',
        },
        {
          icon: 'percent',
          title: 'Promotion',
        },
        {
          icon: 'user',
          title: '24 Hours Service',
        },
      ],
    }
  },
}
</script>

<style scoped>
.card {
  background-color: #002c3e;
  border: none;
  color: #fff;
}
h5 {
  font-weight: 500;
  font-size: 1.3rem;
}
p {
  font-size: 1.2rem;
}
</style>
