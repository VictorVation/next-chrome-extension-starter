# next-chrome-extension-starter

This is a template for creating Chrome extensions with Next.js, Tailwind, and TypeScript.

## Getting Started

1. Develop using `npm run dev` and opening localhost:3000 to start the Next.js development server.
1. Pages are stored in `app/` directory. Modify `app/page.tsx` to start.
1. The extension manifest is in `public/manifest.json`.
1. Anything in the `public` directory will be copied to the root level of your extension, so you may want to stay organized, e.g. assets are stored in `public/next-assets`.

## Building

`npm run build` will build your unpacked chrome extension into `extension`. Chrome doesn't allow directories starting with `_`, so the build script will automatically rewrite the paths for you.

To test your extension, see the [Chrome Extension Docs](https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#load-unpacked)
