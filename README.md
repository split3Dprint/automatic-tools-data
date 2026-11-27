# Split3D Print: Automatic Tools data

The data files that the Automatic Tools of [Split3D Print](https://superhivemarket.com/products/split-3dprint) download once. Split3D Print is a Blender add-on that cuts 3D models into printable pieces.

Nothing here needs to be downloaded by hand: the Install button of the add-on does it and checks the files.

## Files

The add-on downloads one pair of files, chosen for the graphics card of the computer.

Release [v1](../../releases/tag/v1), the large AI (graphics cards with 6 GB of memory or more, and computers without DirectML):

| File | Size (bytes) | SHA-256 |
|---|---|---|
| `split3d_auto_encoder.onnx` | 889104812 | `51b209927eade293da6ae288837133dcc0fc8681183b8f88b6911b01575045b9` |
| `split3d_auto_decoder.onnx` | 16595075 | `3ecc2a27c81c65977d98225d331cd583109c51c9ca97dd20e643cab860239c54` |

Release [v2](../../releases/tag/v2), the light AI (graphics cards with less memory):

| File | Size (bytes) | SHA-256 |
|---|---|---|
| `split3d_auto_encoder_small.onnx` | 162676439 | `19439cbd767eb79a6396fe2097d38c33fed466e924a75e98fe2300cdfbf9b8ba` |
| `split3d_auto_decoder_small.onnx` | 16595021 | `f84369c762d30e1747c1c2457e69977ad5e5ce582194f027388d084b249ef75c` |

A release is never changed once published.

## Origin and license

These files are the Segment Anything Model 2.1 (SAM 2.1) by Meta Platforms, Inc., converted to the ONNX format: "hiera large" for the large AI, "hiera small" for the light one. The model was not retrained and what it computes is unchanged.

SAM 2.1 is released under the Apache License 2.0, and so are these files. See [LICENSE](LICENSE) and [NOTICE](NOTICE).

Original model: https://github.com/facebookresearch/sam2
