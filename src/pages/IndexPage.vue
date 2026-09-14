<template>
  <q-page class="page">

    <div class="row full-height">

      <!-- Left Side -->
      <div class="col-12 col-md-6 left">

        <q-card class="card">

          <q-card-section>
            <div class="text-h5 text-center text-primary">
              Login
            </div>
          </q-card-section>

          <q-card-section>

            <q-input
              outlined
              label="Username"
              class="input"
            />

            <q-input
              outlined
              type="password"
              label="Password"
              class="input"
            />

            <q-btn
              label="Submit"
              color="primary"
              class="button"
            />

          </q-card-section>

        </q-card>

      </div>


      <!-- Right Side -->
      <div class="col-12 col-md-6 right">

        <q-img
          src="https://images.unsplash.com/photo-1497366754035-f200968a6e72"
          class="image"
        />

      </div>

    </div>

  </q-page>
</template>

<style scoped>
.page {
  height: 100vh;
}

.left {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 30px;
}

.right {
  height: 100%;
}

.card {
  width: 400px;
  max-width: 100%;
}

.input {
  margin-bottom: 15px;
}

.button {
  width: 100%;
}

.image {
  height: 100%;
}
</style>