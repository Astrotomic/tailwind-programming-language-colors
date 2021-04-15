# tailwind-programming-language-colors
This plugin adds the programming language colours to the Tailwind colour palette.

## Installation

```bash
yarn add Astrotomic/tailwind-programming-language-colors#main
```

**tailwind.config.js**
```javascript
module.exports = {
  plugins: [
      require('tailwind-programming-language-colors'),
  ],
};
```

## Usage

```html
<div class="space-y-6">
    <button class="bg-lang-html px-4 py-2 rounded text-white">
        HTML
    </button>
    <button class="bg-lang-css px-4 py-2 rounded text-white">
        CSS
    </button>
    <button class="bg-lang-php px-4 py-2 rounded text-white">
        PHP
    </button>
    <button class="bg-lang-visual-basic-net px-4 py-2 rounded text-white">
        VB.NET
    </button>
    <button class="bg-lang-sas px-4 py-2 rounded text-white">
        SAS
    </button>
    <button class="bg-lang-haskell px-4 py-2 rounded text-white">
        Haskell
    </button>
</div>
```

Will result in something similar to this:

<img width="557" alt="colours" src="https://user-images.githubusercontent.com/38976391/114849494-b8452200-9dd7-11eb-8401-3fb8721841be.png">
