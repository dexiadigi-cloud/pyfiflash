# Third-party notices

PyFiFlash is a single self-contained HTML file. It bundles or loads the
following third-party software at runtime:

## ts-fsrs (vendored, MIT License)

The FSRS spaced-repetition scheduler is vendored from
[ts-fsrs](https://github.com/open-spaced-repetition/ts-fsrs) (MIT License,
Copyright (c) 2023 open-spaced-repetition contributors). The MIT license text
is reproduced in full below; the original copyright notice is retained in the
vendored source.

```
MIT License

Copyright (c) 2023 open-spaced-repetition

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
```

## Pyodide (loaded from CDN, Mozilla Public License 2.0)

Real Python execution in the browser is provided by
[Pyodide](https://pyodide.org) (Copyright (c) 2019 Pyodide contributors,
Mozilla Public License 2.0). Pyodide is **not** bundled or distributed with
this repository; it is fetched at runtime from the jsDelivr CDN
(`https://cdn.jsdelivr.net/pyodide/`). It is used unmodified, so no
MPL-2.0 source-distribution obligations are triggered by this project.
See https://www.mozilla.org/en-US/MPL/2.0/ for the full license text.
