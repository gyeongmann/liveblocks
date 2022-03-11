<p align="center">
  <a href="https://liveblocks.io">
    <img src="https://liveblocks.io/icon-192x192.png" height="96">
  </a>
</p>

# [Liveblocks](https://liveblocks.io) × [SvelteKit](https://kit.svelte.dev/).

This repo shows how to implement live avatars with Liveblocks and [SvelteKit](https://kit.svelte.dev/).

![live-avatars-screenshot](https://liveblocks.io/_next/image?url=%2Fimages%2Fexamples%2Fthumbnail-live-avatars.png&w=1200&q=90)

## Getting started

### Run examples locally

- Install all dependencies with `npm install`

- Create an account on [liveblocks.io](https://liveblocks.io/dashboard)

- Copy your secret key from the [administration](https://liveblocks.io/dashboard/apikeys)

- Create a file named `.env.local` and add your Liveblocks secret as environment variable `VITE_LIVEBLOCKS_SECRET_KEY=sk_test_yourkey`

### Run examples on CodeSandbox

- Open this repository on CodeSandbox with this [link](https://codesandbox.io/s/sveltekit-live-avatars-t4vetx)

- Create an account on [liveblocks.io](https://liveblocks.io/dashboard)

- Copy your secret key from the [administration](https://liveblocks.io/dashboard/apikeys)

- Create [secret](https://codesandbox.io/docs/secrets) named `VITE_LIVEBLOCKS_SECRET_KEY` with the secret key you just copied. You need to create an account on CodeSandbox to add an environment variable.

- Refresh your browser and you should be good to go!