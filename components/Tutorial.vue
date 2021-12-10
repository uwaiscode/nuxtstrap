<!-- Please remove this file from your project -->
<template>
  <div>
    <div class="px-4 py-5 my-5 text-center">
      <NuxtLogo />
      <h1 class="display-5 fw-bold">Welcome to your Nuxt Application</h1>
      <div class="col-lg-6 mx-auto">
        <p class="lead mb-4">
          We recommend you take a look at the
          <a
            href="https://nuxtjs.org"
            target="_blank"
            class="text-green-500 hover:underline"
          >
            Nuxt documentation </a
          >, whether you are new or have previous experience with the
          framework.<br />
        </p>
      </div>
      <!-- Button trigger modal -->
      <button
        type="button"
        class="btn btn-primary"
        data-bs-toggle="modal"
        data-bs-target="#exampleModal"
      >
        Launch demo modal
      </button>

      <!-- Modal -->
      <div
        class="modal fade"
        id="exampleModal"
        tabindex="-1"
        aria-labelledby="exampleModalLabel"
        aria-hidden="true"
      >
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header">
              <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
              <button
                type="button"
                class="btn-close"
                data-bs-dismiss="modal"
                aria-label="Close"
              ></button>
            </div>
            <div class="modal-body">...</div>
            <div class="modal-footer">
              <button
                type="button"
                class="btn btn-secondary"
                data-bs-dismiss="modal"
              >
                Close
              </button>
              <button type="button" class="btn btn-primary">
                Save changes
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
