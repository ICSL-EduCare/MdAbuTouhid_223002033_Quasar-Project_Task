<template>
  <q-page class="page flex flex-center">

    <div class="row q-col-gutter-md items-stretch justify-center full-width container">

      <!-- Left Side: Login Card -->
      <div class="col-12 col-sm-6 col-md-5 flex">
        <q-card class="my-card shadow-10 full-width flex flex-center column">

          <q-card-section class="full-width">
            <div class="text-h5 text-center text-primary text-bold">
              Login
            </div>
          </q-card-section>

          <q-card-section class="full-width q-pt-none">
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
              unelevated
            />
          </q-card-section>

        </q-card>
      </div>


      <!-- Right Side: Mouse Image Card -->
      <div class="col-12 col-sm-6 col-md-5 flex">
        <q-card class="my-card shadow-10 full-width overflow-hidden">

          <q-img
            src="https://images.unsplash.com/photo-1615663245857-ac93bb7c39e7?q=80&w=1000&auto=format&fit=crop"
            class="image full-height"
            spinner-color="primary"
          >
            <div class="absolute-bottom text-subtitle2 text-center">
              Computer Mouse
            </div>
          </q-img>

        </q-card>
      </div>

    </div>

  </q-page>
</template>

<style scoped>
.page {
  min-height: 100vh;
  background-color: #f5f5f5;
  padding: 20px;
}

.container {
  max-width: 900px;
}

.my-card {
  border-radius: 12px;
}

.input {
  margin-bottom: 15px;
}

.button {
  width: 100%;
  padding: 10px 0;
}

.image {
  min-height: 280px;
  object-fit: cover;
}
</style>