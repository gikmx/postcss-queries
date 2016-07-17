# postcss-queries

Media query presets for postcss.

# Installation

```bash
npm i -S postcss-queries
```

# Usage

Your project should arleady have postcss upand running with _custom-media_ support via
[postcss-custom-media](https://github.com/postcss/postcss-custom-media) and _import_
support via [postcss-import](https://github.com/postcss/postcss-import).

Once ready, just import it in your stylesheet.

```css
@import 'postcss-queries';
```
# What's included?

Every mobile and tablet query includes a `portrait` and `landscape` shorthand.

- mobile
  - iphone-4
  - iphone-5
  - iphone-6
  - iphone-6plus
  - galaxy-s3
  - galaxy-s4
  - galaxy-s5
  - htc-1
- tablet
  - ipad (mini, 1, 2)
  - ipad-retina (3, 4)
  - galaxy
  - nexus-7
  - kindle-fire
- desktop
- desktop-wide


## License

---

The MIT License (MIT)

Copyright (c) 2016 GIK

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
