# AnimeMovieCamera model assets

Versioned, on-device Core ML model files for AnimeMovieCamera. The iOS 18+ app downloads the full model set during initial setup and only changed files after model updates. Downloaded files are pinned by SHA-256 in the app's ModelCatalog.json. No server-side inference is used.

Release assets are byte-for-byte copies of the previously bundled Core ML model files; this migration applies no additional quantization, precision conversion or generation-setting changes. Unchanged model locations remain stable across app updates. The application source, signing material and user photographs are not included.

## Model notices

Models retain their upstream licenses. DCTNet-LICENSE.txt and SPatchGAN-LICENSE.txt are included with the release. The MeinaMix V11 / Stable Diffusion components use CreativeML OpenRAIL-M; see the included license and the upstream model cards:

- https://huggingface.co/Meina/MeinaMix_V11
- https://huggingface.co/lllyasviel/control_v11p_sd15_lineart

The GitHub release files are the app's model data, not a new license grant over the underlying models.
