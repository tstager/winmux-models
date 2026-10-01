# winmux-models

Speech model assets for [winmux](https://github.com/tstager/winmux)'s on-device dictation. winmux downloads a model
once, after the user consents at first use, and verifies it against SHA-256 pins compiled into the app.

**These assets are not covered by winmux's MIT licence.** Each release carries the licence that governs it, plus a
NOTICE file:

| Release tag | Model | Licence |
|---|---|---|
| `speech-model-zipformer-en-2023-06-26-int8` | streaming Zipformer, English, 2023-06-26, int8 (k2-fsa / sherpa-onnx) | Apache License 2.0 |
| `speech-model-nemotron-en-0.6b-560ms-int8` | NVIDIA Nemotron speech streaming, English, 0.6b, 560 ms, int8 (k2-fsa export) | NVIDIA Open Model License Agreement |

Licensed by NVIDIA Corporation under the NVIDIA Open Model License (Nemotron asset). Releases are immutable: a
corrected asset gets a new tag, never a re-upload. Every release is marked pre-release so no "latest" release exists here.
