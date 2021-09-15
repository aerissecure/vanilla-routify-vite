This repo was created with the following steps:

1. `mkdir vanilla-routify-vite`
2. `npx @roxi/routify init`
3. `npm install -D  @smui/button`
4. Import and use `"@smui/button"` in `src/pages/example/index.svelte`

Then watch the console for errors, specifically:

~~~
Uncaught SyntaxError: The requested module '/node_modules/@smui/common/internal/index.js?v=819509fe' does not provide an export named 'ActionArray'
~~~
