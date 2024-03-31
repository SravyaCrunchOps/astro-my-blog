# Adding Integrations
------------------------

### Tailwind
--------------
npx astro add tailwind

 -> For manual install
    cmd => npm install @astrojs/tailwind tailwindcss

 -> In `astro.config.mjs`
    import { defineConfig } from 'astro/config';
    import tailwind from '@astrojs/tailwind';

    export default defineConfig({
    // ...
    integrations: [tailwind()],
    });

-> Create "tailwid.config.mjs" file in project's root directory
cmd => npx tailwindcss init

### Special Thanks
---------------------

I used "fakeAPI" and "norian's wordpress" for fake content