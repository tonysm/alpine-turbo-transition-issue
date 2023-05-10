Repository to reproduce an issue with Turbo and Alpine's `[x-transition]` feature.

Steps to reproduce it:

- Setup the Laravel app however you want (I'm using Sail to run it locally, but any other setup can be used)
- Install and compile the assets with Alpine 3.10.2: `npm i && npm run build`
- Open DevTools and click around (I use Jetstream's Create Team and Team Settings pages)
- No console errors
- Install and compile the assets with Alpine 3.10.3: `npm install alpine@3.10.3 && npm run build`
- Open DevTools and click around (I use Jetstream's Create Team and Team Settings pages)
- You can see the error
