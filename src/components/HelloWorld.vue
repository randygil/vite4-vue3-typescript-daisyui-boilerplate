<template>
  <!-- navbar -->
  <div class="navbar bg-base-100">
    <div class="navbar-start">
      <div class="dropdown">
        <label tabindex="0" class="btn btn-ghost lg:hidden">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h8m-8 6h16"
            />
          </svg>
        </label>
        <ul
          tabindex="0"
          class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52"
        >
          <li><a>Item 1</a></li>
          <li tabindex="0">
            <a class="justify-between">
              Parent
              <svg
                class="fill-current"
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
              >
                <path
                  d="M8.59,16.58L13.17,12L8.59,7.41L10,6L16,12L10,18L8.59,16.58Z"
                />
              </svg>
            </a>
            <ul class="p-2">
              <li><a>Submenu 1</a></li>
              <li><a>Submenu 2</a></li>
            </ul>
          </li>
          <li><a>Item 3</a></li>
        </ul>
      </div>
      <a class="btn btn-ghost normal-case text-xl">daisyUI</a>
    </div>
    <div class="navbar-center hidden lg:flex">
      <ul class="menu menu-horizontal px-1">
        <li><a>Item 1</a></li>
        <li tabindex="0">
          <a>
            Parent
            <svg
              class="fill-current"
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              viewBox="0 0 24 24"
            >
              <path
                d="M7.41,8.58L12,13.17L16.59,8.58L18,10L12,16L6,10L7.41,8.58Z"
              />
            </svg>
          </a>
          <ul class="p-2">
            <li><a>Submenu 1</a></li>
            <li><a>Submenu 2</a></li>
          </ul>
        </li>
        <li><a>Item 3</a></li>
      </ul>
    </div>
    <div class="navbar-end">
      <a class="btn">Get started</a>
    </div>
  </div>

  <!-- HERO -->

  <div class="hero min-h-screen">
    <div class="hero-overlay bg-opacity-60"></div>
    <div class="hero-content text-center text-neutral-content">
      <div class="max-w-md">
        <h1 class="mb-5 text-5xl font-bold">Hello there</h1>
        <p class="mb-5">
          Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda
          excepturi exercitationem quasi. In deleniti eaque aut repudiandae et a
          id nisi.
        </p>
        <button class="btn btn-primary">Get Started</button>
      </div>
    </div>
  </div>

  <!-- buttons -->
  <div class="p-4">
    <button class="btn btn-primary">primary</button>
    <button class="btn btn-secondary">secondary</button>
    <button class="btn btn-accent">accent</button>
  </div>

  <!-- same buttons with another theme! -->
  <div class="p-4" data-theme="valentine">
    <button class="btn btn-primary">primary</button>
    <button class="btn btn-secondary">secondary</button>
    <button class="btn btn-accent">accent</button>
  </div>

  <!-- tab -->
  <div class="p-4 tabs">
    <button class="tab tab-lifted">Tab 1</button>
    <button class="tab tab-lifted tab-active">Tab 2</button>
    <button class="tab tab-lifted">Tab 3</button>
  </div>

  <!-- toggle -->
  <div class="p-4">
    <input type="checkbox" class="toggle toggle-primary" />
    <input type="checkbox" class="toggle toggle-secondary" />
    <input type="checkbox" class="toggle toggle-accent" />
  </div>

  <!-- card -->
  <div class="card shadow-2xl w-80 m-4">
    <figure>
      <img src="https://picsum.photos/id/1005/500/250" />
    </figure>
    <div class="card-body">
      <h2 class="card-title">DaisyUI Card</h2>
      <p>
        Rerum reiciendis beatae tenetur excepturi aut pariatur est eos. Sit sit
        necessitatibus.
      </p>
    </div>
  </div>

  <!-- dropdown -->
  <div class="dropdown m-4">
    <div tabindex="0" class="m-1 btn">Dropdown</div>
    <ul
      tabindex="0"
      class="p-2 menu dropdown-content bg-neutral text-neutral-content rounded-box w-52"
    >
      <li><a>Item 1</a></li>
      <li><a>Item 2</a></li>
    </ul>
  </div>

  <!-- drawer -->

  <!-- modal button -->
  <label for="my-modal" class="btn modal-button">Modal</label>
  <!-- modal content -->
  <input type="checkbox" id="my-modal" class="modal-toggle" />
  <div class="modal">
    <div class="modal-box">
      <p>
        Enim dolorem dolorum omnis atque necessitatibus. Consequatur aut
        adipisci qui iusto illo eaque. Consequatur repudiandae et. Nulla ea
        quasi eligendi. Saepe velit autem minima.
      </p>
      <div class="modal-action">
        <label for="my-modal" class="btn">Close</label>
      </div>
    </div>
  </div>

  <!-- steps -->
  <ul class="steps my-4 w-full">
    <li class="step step-primary">Register</li>
    <li class="step step-primary">Choose plan</li>
    <li class="step">Purchase</li>
    <li class="step">Receive Product</li>
  </ul>

  <!-- avatar -->
  <div class="avatar online m-10">
    <div class="rounded-full w-24 h-24">
      <img src="http://daisyui.com/tailwind-css-component-profile-1@94w.png" />
    </div>
  </div>
  <div class="avatar offline m-10">
    <div class="rounded-full w-24 h-24">
      <img src="http://daisyui.com/tailwind-css-component-profile-2@94w.png" />
    </div>
  </div>

  <!-- footer -->

  <footer class="footer p-10 bg-neutral text-neutral-content">
    <div>
      <span class="footer-title">Services</span>
      <a class="link link-hover">Branding</a>
      <a class="link link-hover">Design</a>
      <a class="link link-hover">Marketing</a>
      <a class="link link-hover">Advertisement</a>
    </div>
    <div>
      <span class="footer-title">Company</span>
      <a class="link link-hover">About us</a>
      <a class="link link-hover">Contact</a>
      <a class="link link-hover">Jobs</a>
      <a class="link link-hover">Press kit</a>
    </div>
    <div>
      <span class="footer-title">Legal</span>
      <a class="link link-hover">Terms of use</a>
      <a class="link link-hover">Privacy policy</a>
      <a class="link link-hover">Cookie policy</a>
    </div>
  </footer>
</template>
