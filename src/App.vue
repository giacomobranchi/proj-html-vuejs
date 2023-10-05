<script>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  components: {
    AppHeader,
    AppFooter
  },
  data() {
    return {
      name: 'App'

    }
  }
}
</script>

<template>
  <AppHeader></AppHeader>
  <main>
    <div class="carousel mt-4">
      <div class="d-flex justify-content-between">
        <div class="card" style="width: 28rem;">
          <div class="badge position-absolute">Food</div>
          <img src="./assets/img/healthy-foods.webp" class="card-img-top position-relative" alt="...">
          <div class="card-body">
            <h5 class="card-title text-center">The Best Healty Foods in 2022</h5>
            <div class="card-text text-center">
              <div>December 26, 2022</div>

            </div>
          </div>
        </div>
        <div class="card" style="width: 28rem;">
          <div class="badge position-absolute">Fashion</div>
          <img src="./assets/img/winter.webp" class="card-img-top position-relative" alt="...">
          <div class="card-body">
            <h5 class="card-title text-center">The Best Winter Outfits</h5>
            <div class="card-text text-center">
              <div>December 26, 2022</div>

            </div>
          </div>
        </div>
        <div class="card" style="width: 28rem;">
          <div class="badge position-absolute">Fashion</div>
          <img src="./assets/img/photographers-mistakes.webp" class="card-img-top position-relative" alt="...">
          <div class="card-body">
            <h5 class="card-title text-center">Beginner Photographer's Mistakes</h5>
            <div class="card-text text-center">
              <div>December 26, 2022</div>

            </div>
          </div>
        </div>
        <div class="card" style="width: 28rem;">
          <div class="position-absolute">
            <span class="badge">Culture</span>
            <span class="badge">Stories</span>
          </div>
          <img src="./assets/img/ideas-anime.webp" class="card-img-top position-relative  " alt="...">
          <div class="card-body">
            <h5 class="card-title text-center">Live Ideas You Might Be Anime</h5>
            <div class="card-text text-center">
              <div>December 26, 2022</div>

            </div>
          </div>
        </div>
      </div>
    </div>
    <section class="jumbo">
      <div class="container">
        <div class="row">
          <div class="col-3">
            <div class="card" style="width: 100%;">
              <div class="position-absolute">
                <span class="badge">Fashion</span>
                <span class="badge">Lifestyle</span>
              </div>
              <img style="filter: brightness(0.6);" src="./assets/img/anime-fashion.webp"
                class="card-img-top position-relative" alt="...">
              <div class="align-self-center position-absolute text-white font-sm w-100 text-center" style="top: 75%;">
                <div class="d-flex justify-content-center align-items-baseline">
                  <svg fill="#ffffff" class="ps-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M224 256A128 128 0 1 0 224 0a128 128 0 1 0 0 256zm-45.7 48C79.8 304 0 383.8 0 482.3C0 498.7 13.3 512 29.7 512H418.3c16.4 0 29.7-13.3 29.7-29.7C448 383.8 368.2 304 269.7 304H178.3z" />
                  </svg>
                  <span class="px-1">demo</span>
                  <svg fill="#ffffff" class="px-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M152 24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H64C28.7 64 0 92.7 0 128v16 48V448c0 35.3 28.7 64 64 64H384c35.3 0 64-28.7 64-64V192 144 128c0-35.3-28.7-64-64-64H344V24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H152V24zM48 192h80v56H48V192zm0 104h80v64H48V296zm128 0h96v64H176V296zm144 0h80v64H320V296zm80-48H320V192h80v56zm0 160v40c0 8.8-7.2 16-16 16H320V408h80zm-128 0v56H176V408h96zm-144 0v56H64c-8.8 0-16-7.2-16-16V408h80zM272 248H176V192h96v56z" />
                  </svg>
                  <span class="px-1">December 26, 2022</span>
                </div>
                <div>
                  <h6 class="p-1">Traveling Alone is Awesome</h6>
                </div>
              </div>
            </div>
            <div class="card mt-3" style="width: 100%;">
              <div class="position-absolute">
                <span class="badge">Stories</span>
                <span class="badge">Travel</span>
              </div>
              <img style="filter: brightness(0.6);" src="./assets/img/travel-alone.webp"
                class="card-img-top position-relative" alt="...">
              <div class="align-self-center position-absolute text-white font-sm w-100 text-center" style="top: 75%;">
                <div class="d-flex justify-content-center align-items-baseline">
                  <svg fill="#ffffff" class="ps-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M224 256A128 128 0 1 0 224 0a128 128 0 1 0 0 256zm-45.7 48C79.8 304 0 383.8 0 482.3C0 498.7 13.3 512 29.7 512H418.3c16.4 0 29.7-13.3 29.7-29.7C448 383.8 368.2 304 269.7 304H178.3z" />
                  </svg>
                  <span class="px-1">demo</span>
                  <svg fill="#ffffff" class="px-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M152 24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H64C28.7 64 0 92.7 0 128v16 48V448c0 35.3 28.7 64 64 64H384c35.3 0 64-28.7 64-64V192 144 128c0-35.3-28.7-64-64-64H344V24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H152V24zM48 192h80v56H48V192zm0 104h80v64H48V296zm128 0h96v64H176V296zm144 0h80v64H320V296zm80-48H320V192h80v56zm0 160v40c0 8.8-7.2 16-16 16H320V408h80zm-128 0v56H176V408h96zm-144 0v56H64c-8.8 0-16-7.2-16-16V408h80zM272 248H176V192h96v56z" />
                  </svg>
                  <span class="px-1">December 26, 2022</span>
                </div>
                <div>
                  <h6 class="p-1">Traveling Alone is Awesome</h6>
                </div>
              </div>
            </div>
          </div>
          <div class="col-6">
            <div class="card" style="width: 100%;">
              <div class="position-absolute">
                <span class="badge">lifestyle</span>
                <span class="badge">Stories</span>
                <span class="badge">Travel</span>
              </div>
              <img style="filter: brightness(0.6);" src="./assets/img/best-places.webp"
                class="card-img-top position-relative" alt="...">
              <div class="align-self-center position-absolute text-white font-sm w-100 text-center" style="top: 88%;">
                <div class="d-flex justify-content-center align-items-baseline">
                  <svg fill="#ffffff" class="ps-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M224 256A128 128 0 1 0 224 0a128 128 0 1 0 0 256zm-45.7 48C79.8 304 0 383.8 0 482.3C0 498.7 13.3 512 29.7 512H418.3c16.4 0 29.7-13.3 29.7-29.7C448 383.8 368.2 304 269.7 304H178.3z" />
                  </svg>
                  <span class="px-1">demo</span>
                  <svg fill="#ffffff" class="px-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M152 24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H64C28.7 64 0 92.7 0 128v16 48V448c0 35.3 28.7 64 64 64H384c35.3 0 64-28.7 64-64V192 144 128c0-35.3-28.7-64-64-64H344V24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H152V24zM48 192h80v56H48V192zm0 104h80v64H48V296zm128 0h96v64H176V296zm144 0h80v64H320V296zm80-48H320V192h80v56zm0 160v40c0 8.8-7.2 16-16 16H320V408h80zm-128 0v56H176V408h96zm-144 0v56H64c-8.8 0-16-7.2-16-16V408h80zM272 248H176V192h96v56z" />
                  </svg>
                  <span class="px-1">December 26, 2022</span>
                </div>
                <div>
                  <h6 class="p-1">Traveling Alone is Awesome</h6>
                </div>
              </div>
            </div>
          </div>
          <div class="col-3">
            <div class="card" style="width: 100%;">
              <div class="position-absolute">
                <span class="badge">Culture</span>
                <span class="badge">Lifestyle</span>
              </div>
              <img style="filter: brightness(0.6);" src="./assets/img/music-love.webp"
                class="card-img-top position-relative" alt="...">
              <div class="align-self-center position-absolute text-white font-sm w-100 text-center" style="top: 75%;">
                <div class="d-flex justify-content-center align-items-baseline">
                  <svg fill="#ffffff" class="ps-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M224 256A128 128 0 1 0 224 0a128 128 0 1 0 0 256zm-45.7 48C79.8 304 0 383.8 0 482.3C0 498.7 13.3 512 29.7 512H418.3c16.4 0 29.7-13.3 29.7-29.7C448 383.8 368.2 304 269.7 304H178.3z" />
                  </svg>
                  <span class="px-1">demo</span>
                  <svg fill="#ffffff" class="px-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M152 24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H64C28.7 64 0 92.7 0 128v16 48V448c0 35.3 28.7 64 64 64H384c35.3 0 64-28.7 64-64V192 144 128c0-35.3-28.7-64-64-64H344V24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H152V24zM48 192h80v56H48V192zm0 104h80v64H48V296zm128 0h96v64H176V296zm144 0h80v64H320V296zm80-48H320V192h80v56zm0 160v40c0 8.8-7.2 16-16 16H320V408h80zm-128 0v56H176V408h96zm-144 0v56H64c-8.8 0-16-7.2-16-16V408h80zM272 248H176V192h96v56z" />
                  </svg>
                  <span class="px-1">December 26, 2022</span>
                </div>
                <div>
                  <h6 class="p-1">Traveling Alone is Awesome</h6>
                </div>
              </div>
            </div>
            <div class="card mt-3" style="width: 100%;">
              <div class="position-absolute">
                <span class="badge">Lyfestyle</span>
                <span class="badge">Travel</span>
              </div>
              <img style="filter: brightness(0.6);" src="./assets/img/visit-france.webp"
                class="card-img-top position-relative" alt="...">
              <div class="align-self-center position-absolute text-white font-sm w-100 text-center" style="top: 75%;">
                <div class="d-flex justify-content-center align-items-baseline">
                  <svg fill="#ffffff" class="ps-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M224 256A128 128 0 1 0 224 0a128 128 0 1 0 0 256zm-45.7 48C79.8 304 0 383.8 0 482.3C0 498.7 13.3 512 29.7 512H418.3c16.4 0 29.7-13.3 29.7-29.7C448 383.8 368.2 304 269.7 304H178.3z" />
                  </svg>
                  <span class="px-1">demo</span>
                  <svg fill="#ffffff" class="px-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M152 24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H64C28.7 64 0 92.7 0 128v16 48V448c0 35.3 28.7 64 64 64H384c35.3 0 64-28.7 64-64V192 144 128c0-35.3-28.7-64-64-64H344V24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H152V24zM48 192h80v56H48V192zm0 104h80v64H48V296zm128 0h96v64H176V296zm144 0h80v64H320V296zm80-48H320V192h80v56zm0 160v40c0 8.8-7.2 16-16 16H320V408h80zm-128 0v56H176V408h96zm-144 0v56H64c-8.8 0-16-7.2-16-16V408h80zM272 248H176V192h96v56z" />
                  </svg>
                  <span class="px-1">December 26, 2022</span>
                </div>
                <div>
                  <h6 class="p-1">Traveling Alone is Awesome</h6>
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>
    </section>
    <section class="lifestyle">
      <div class="container">
        <div class="d-flex justify-content-between">
          <h2 class="pb-3">LIFESTYLE & STORIES</h2>
          <div>
            <div class="badge mx-1 p-2">ALL</div>
            <div class="badge mx-1 p-2">LIFESTYLE</div>
            <div class="badge mx-1 p-2">STORIES</div>
          </div>
        </div>
        <div class="row">
          <div class="col-7">
            <div>
              <div class="card" style="width: 100%;">
                <div class="badge position-absolute">Food</div>
                <img style="filter: brightness(0.6);" src="./assets/img/success-story.webp"
                  class="card-img-top position-relative" alt="...">
                <div class="align-self-center ms-2 position-absolute text-white" style="left: 17%;
    top: 85%;">
                  <div class="d-flex align-items-baseline">
                    <svg fill="#ffffff" class="ps-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                      viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                      <path
                        d="M224 256A128 128 0 1 0 224 0a128 128 0 1 0 0 256zm-45.7 48C79.8 304 0 383.8 0 482.3C0 498.7 13.3 512 29.7 512H418.3c16.4 0 29.7-13.3 29.7-29.7C448 383.8 368.2 304 269.7 304H178.3z" />
                    </svg>
                    <span class="px-1">demo</span>
                    <svg fill="#ffffff" class="px-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                      viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                      <path
                        d="M152 24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H64C28.7 64 0 92.7 0 128v16 48V448c0 35.3 28.7 64 64 64H384c35.3 0 64-28.7 64-64V192 144 128c0-35.3-28.7-64-64-64H344V24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H152V24zM48 192h80v56H48V192zm0 104h80v64H48V296zm128 0h96v64H176V296zm144 0h80v64H320V296zm80-48H320V192h80v56zm0 160v40c0 8.8-7.2 16-16 16H320V408h80zm-128 0v56H176V408h96zm-144 0v56H64c-8.8 0-16-7.2-16-16V408h80zM272 248H176V192h96v56z" />
                    </svg>
                    <span class="px-1">December 26, 2022</span>
                  </div>
                  <div>
                    <h6 class="p-1">Traveling Alone is Awesome</h6>
                  </div>
                </div>
              </div>
            </div>

          </div>
          <div class="col-5">
            <div class="d-flex">
              <div class="card" style="width: 40%;">
                <div class="badge position-absolute">Food</div>
                <img style="filter: brightness(0.6);" src="./assets/img/travel-alone.webp"
                  class="card-img-top position-relative" alt="...">
              </div>
              <div class="align-self-center ms-2">
                <div class="d-flex align-items-baseline">
                  <svg class="ps-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M224 256A128 128 0 1 0 224 0a128 128 0 1 0 0 256zm-45.7 48C79.8 304 0 383.8 0 482.3C0 498.7 13.3 512 29.7 512H418.3c16.4 0 29.7-13.3 29.7-29.7C448 383.8 368.2 304 269.7 304H178.3z" />
                  </svg>
                  <span class="px-1">demo</span>
                  <svg class="px-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M152 24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H64C28.7 64 0 92.7 0 128v16 48V448c0 35.3 28.7 64 64 64H384c35.3 0 64-28.7 64-64V192 144 128c0-35.3-28.7-64-64-64H344V24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H152V24zM48 192h80v56H48V192zm0 104h80v64H48V296zm128 0h96v64H176V296zm144 0h80v64H320V296zm80-48H320V192h80v56zm0 160v40c0 8.8-7.2 16-16 16H320V408h80zm-128 0v56H176V408h96zm-144 0v56H64c-8.8 0-16-7.2-16-16V408h80zM272 248H176V192h96v56z" />
                  </svg>
                  <span class="px-1">December 26, 2022</span>
                </div>
                <div>
                  <h6 class="p-1">Traveling Alone is Awesome</h6>
                </div>
              </div>
            </div>

            <hr>
            <div class="d-flex">
              <div class="card" style="width: 40%;">
                <div class="badge position-absolute">Food</div>
                <img style="filter: brightness(0.6);" src="./assets/img/best-places.webp"
                  class="card-img-top position-relative" alt="...">
              </div>
              <div class="align-self-center ms-2">
                <div class="d-flex align-items-baseline">
                  <svg class="ps-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M224 256A128 128 0 1 0 224 0a128 128 0 1 0 0 256zm-45.7 48C79.8 304 0 383.8 0 482.3C0 498.7 13.3 512 29.7 512H418.3c16.4 0 29.7-13.3 29.7-29.7C448 383.8 368.2 304 269.7 304H178.3z" />
                  </svg>
                  <span class="px-1">demo</span>
                  <svg class="px-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M152 24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H64C28.7 64 0 92.7 0 128v16 48V448c0 35.3 28.7 64 64 64H384c35.3 0 64-28.7 64-64V192 144 128c0-35.3-28.7-64-64-64H344V24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H152V24zM48 192h80v56H48V192zm0 104h80v64H48V296zm128 0h96v64H176V296zm144 0h80v64H320V296zm80-48H320V192h80v56zm0 160v40c0 8.8-7.2 16-16 16H320V408h80zm-128 0v56H176V408h96zm-144 0v56H64c-8.8 0-16-7.2-16-16V408h80zM272 248H176V192h96v56z" />
                  </svg>
                  <span class="px-1">December 25, 2022</span>
                </div>
                <div>
                  <h6 class="p-1">Places For a Roadtrip</h6>
                </div>
              </div>
            </div>

            <hr>
            <div class="d-flex">
              <div class="card" style="width: 40%;">
                <div class="badge position-absolute">Food</div>
                <img style="filter: brightness(0.6);" src="./assets/img/music-love.webp" class="card-img-top" alt="...">
              </div>
              <div class="align-self-center ms-2">
                <div class="d-flex align-items-baseline">
                  <svg class="ps-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M224 256A128 128 0 1 0 224 0a128 128 0 1 0 0 256zm-45.7 48C79.8 304 0 383.8 0 482.3C0 498.7 13.3 512 29.7 512H418.3c16.4 0 29.7-13.3 29.7-29.7C448 383.8 368.2 304 269.7 304H178.3z" />
                  </svg>
                  <span class="px-1">demo</span>
                  <svg class="px-1" xmlns="http://www.w3.org/2000/svg" height="1em"
                    viewBox="0 0 448 512"><!--! Font Awesome Free 6.4.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. -->
                    <path
                      d="M152 24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H64C28.7 64 0 92.7 0 128v16 48V448c0 35.3 28.7 64 64 64H384c35.3 0 64-28.7 64-64V192 144 128c0-35.3-28.7-64-64-64H344V24c0-13.3-10.7-24-24-24s-24 10.7-24 24V64H152V24zM48 192h80v56H48V192zm0 104h80v64H48V296zm128 0h96v64H176V296zm144 0h80v64H320V296zm80-48H320V192h80v56zm0 160v40c0 8.8-7.2 16-16 16H320V408h80zm-128 0v56H176V408h96zm-144 0v56H64c-8.8 0-16-7.2-16-16V408h80zM272 248H176V192h96v56z" />
                  </svg>
                  <span class="px-1">December 25, 2022</span>
                </div>
                <div>
                  <h6 class="p-1">Music The Love Of My Life</h6>
                </div>
              </div>
            </div>

          </div>
        </div>
      </div>
    </section>
    <div class="banner py-4">
      <div class="container">
        <img src="./assets/img/page-banner-1.webp" style="width: 100%;" alt="">
      </div>
    </div>
    <section class="featured">
      <div class="container">
        <h2 class="pb-3">FEATURED POSTS</h2>
        <div class="row">
          <div class="col-4">
            <div class="card" style="width: 100%;">
              <div class="position-absolute">
                <span class="badge">Fashion</span>
                <span class="badge">Lifestyle</span>
              </div>
              <img src="./assets/img/ideas-anime.webp" class="card-img-top position-relative" alt="...">
              <div class="card-body">
                <h5 class="card-title text-center">Live Ideas You Might Be Anime</h5>
                <div class="card-text text-center">
                  <div>December 26, 2022</div>
                  <div>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum, provident a vitae numquam ab enim!
                  </div>
                  <button type="button" class="btn btn_bg">Read More</button>
                </div>
              </div>
            </div>
          </div>
          <div class="col-4">
            <div class="card" style="width: 100%;">
              <div class="position-absolute">
                <span class="badge">Fashion</span>
                <span class="badge">Lifestyle</span>
              </div>
              <img src="./assets/img/visit-france.webp" class="card-img-top position-relative" alt="...">
              <div class="card-body">
                <h5 class="card-title text-center">The Best Healty Foods in 2022</h5>
                <div class="card-text text-center">
                  <div>December 26, 2022</div>
                  <div>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum, provident a vitae numquam ab enim!
                  </div>
                  <button type="button" class="btn btn_bg">Read More</button>
                </div>
              </div>
            </div>
          </div>
          <div class="col-4">
            <div class="card" style="width: 100%;">
              <div class="position-absolute">
                <span class="badge">Fashion</span>
                <span class="badge">Lifestyle</span>
              </div>
              <img src="./assets/img/travel-alone.webp" class="card-img-top position-relative" alt="...">
              <div class="card-body">
                <h5 class="card-title text-center">The Best Healty Foods in 2022</h5>
                <div class="card-text text-center">
                  <div>December 26, 2022</div>
                  <div>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum, provident a vitae numquam ab enim!
                  </div>
                  <button type="button" class="btn btn_bg">Read More</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="player mt-4 py-4">
      <div class="container d-flex justify-content-center">
        <iframe width="800" height="400"
          src="https://www.youtube.com/embed/videoseries?si=HjHouNmK6Ju1-Wlx&amp;list=PLRe9ARNnYSY6bYx-ZE_Tx5llrFI5u4laE"
          title="YouTube video player" frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen></iframe>

      </div>

    </section>
    <section class="categories mb-4">
      <div class="row">
        <div class="row justify-content-center p-0 m-0">
          <div class="col_2">
            <div class="card text-white" style="width: 100%%;">
              <h4 class="position-absolute">FASHION</h4>
              <img src="./assets/img/anime-fashion.webp" class="card-img-top position-relative" alt="...">
            </div>
          </div>
          <div class="col_2">
            <div class="card" style="width: 100%%;">
              <h4 class="position-absolute text-white">CULTURE</h4>
              <img src="./assets/img/success-story.webp" class="card-img-top position-relative" alt="...">
            </div>
          </div>
          <div class="col_2">
            <div class="card" style="width: 100%%;">
              <h4 class="position-absolute text-white">FOOD</h4>
              <img src="./assets/img/healthy-foods.webp" class="card-img-top position-relative" alt="...">
            </div>
          </div>
          <div class="col_2">
            <div class="card" style="width: 100%%;">
              <h4 class="position-absolute text-white">LIFESTYLE</h4>
              <img src="./assets/img/visit-france.webp" class="card-img-top position-relative" alt="...">
            </div>
          </div>
          <div class="col_2">
            <div class="card" style="width: 100%%;">
              <h4 class="position-absolute text-white">STORIES</h4>
              <img src="./assets/img/travel-alone.webp" class="card-img-top position-relative" alt="...">
            </div>
          </div>
          <div class="col_2">
            <div class="card" style="width: 100%%;">
              <h4 class="position-absolute text-white">TRAVEL</h4>
              <img src="./assets/img/best-places.webp" class="card-img-top position-relative" alt="...">
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
  <AppFooter></AppFooter>
</template>

<style lang="scss" scoped>
.font-sm {
  font-size: 12px;
}

.position-absolute {
  z-index: 10000;
  top: 10px;
  left: 50%;
  transform: translate(-50%, 0)
}


main {
  & .carousel {
    padding: 1.5rem;
    background-color: #f3f3f3;

    & .badge {
      background-color: white;
      color: black;
      margin: 0 1rem;
    }
  }

  & .jumbo {
    padding: 4rem 0;

    & .badge {
      background-color: white;
      color: black;
      margin: 0 0.4rem;
    }
  }

  & .lifestyle {
    & .col-7 {
      & .position-absolute {
        z-index: 10000;
        top: 10px;
        left: 5%;
        transform: translate(-50%, 0)
      }

      & .col-5 {
        & .position-absolute {
          z-index: 10000;
          top: 10px;
          left: 15%;
          transform: translate(-50%, 0)
        }
      }

      & .badge {
        background-color: #555353;
      }

      & .card {
        & .badge {
          background-color: white;
          color: black;
        }




      }
    }
  }

  .col-5 .badge {
    background-color: white;
    color: black;
    margin: 0 0.5rem;
    left: 20px;
  }

  & .banner {
    background-color: #f3f3f3;
    margin: 2rem 0;
  }

  & .featured {
    & .card-body {
      background-color: #f3f3f3;
    }

    & .badge {
      background-color: white;
      color: black;
      margin: 0 0.5rem;
    }

    & .btn_bg {
      background-color: #bf1d2e;
      color: white;
      padding: 0.4rem 3rem;
      border-radius: 1.5rem;
      margin-top: 0.5rem;
    }
  }

  & .categories {
    & img {
      filter: brightness(0.6);
    }

    & .position-absolute {
      top: 40%;
    }

    & .row {
      width: 99vw;
    }

    & .col_2 {
      width: calc(100% / 7);

    }
  }
}
</style>
