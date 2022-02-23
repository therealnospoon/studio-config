![image](https://miro.medium.com/max/1400/1*D4Q_5erHUdm8zXNaxPsEGQ.png)
# Svelte Template
```json
"scripts": {
    "dev": "vite",
    "build": "vite build",
    "serve": "vite preview"
},
```

#### Optional Configs + Base Styles
- [Styles Repo](https://github.com/qudo-code/template--scss)
- [Configs Repo](https://github.com/qudo-code/template--config-only)
1. Download base styles to `src/styles`:
   `npx degit github.com:qudo-code/template--scss src/styles`
2. Download configs to current directory:
   `npx degit github.com:qudo-code/template--config-only --force`
3. If downloaded styles, be sure to add
   `import "src/styles/main.scss` in your `main.js`.

