# Seek models

Model files downloaded by the Seek app on first run.

## SeekImageModel (v1)

Google's [SigLIP Base (patch16-224)](https://huggingface.co/google/siglip-base-patch16-224), converted to Core ML
(half precision) for on-device photo search on Apple silicon. Contents of `SeekImageModel.zip`:

- `ImageEncoder.mlpackage` — 224×224 image → 768-d unit vector
- `TextEncoder.mlpackage` — 64 token ids → 768-d unit vector
- `tokenizer.json`, `model.json`

SHA-256 of `SeekImageModel.zip` is published with each release. The original model is © Google, released under the
Apache License 2.0 (see `LICENSE`); this repository redistributes a converted form under the same licence.
