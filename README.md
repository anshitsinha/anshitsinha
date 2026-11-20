I work on running AI and heavy software locally, in the browser or on your own GPU, so it doesn't need a server. Mostly WebGPU right now.

| | What it is | Result | |
|---|---|---|---|
| [kiln](https://github.com/anshitsinha/kiln) | Whisper inference engine on hand-written WGSL kernels | 5.3x faster than Transformers.js, same accuracy | [demo](https://kiln-brown-seven.vercel.app) |
| [cellforge](https://github.com/anshitsinha/cellforge) | Spreadsheet that runs fully in the browser | 100M rows; compiled formulas 6–22x faster | [demo](https://cellforge-six.vercel.app) |
| [lucent](https://github.com/anshitsinha/lucent) | Real-ESRGAN image upscaler on WebGPU | 3.1 TFLOP/s on a laptop GPU, 15 KB of JS | [demo](https://lucent-six-hazel.vercel.app) |
| Inkline | Photo-to-tattoo-stencil maker with on-device ML | Works offline, nothing uploaded | [demo](https://inkline-sigma.vercel.app) |

Every kernel is tested against a plain CPU version on a real GPU (about 270 tests in kiln), so the speedups are measured, not guessed.

I also build for clients. [Aazmaao](https://www.aazmaao.com) is a live fashion store, which I wrote most of, with slot-based delivery and live rider tracking. [MedIIT](https://momentum-ruby-alpha.vercel.app) is a coaching platform with live classes on self-hosted video. I also wrote a paper on verifying vision-language models for driving: on 2,000 held-out frames, it released zero unsafe actions.

I like C and knowing what's happening in memory.

[anshit.is-a.dev](https://anshit.is-a.dev) · [LinkedIn](https://www.linkedin.com/in/anshitsinha/) · [X](https://twitter.com/anstsnh)
