# Split3D Print: Automatic Tools data

The data files that the Automatic Tools of [Split3D Print](https://superhivemarket.com/products/split-3dprint) download once. Split3D Print is a Blender add-on that cuts 3D models into printable pieces.

Nothing here needs to be downloaded by hand: the Install button of the add-on does it and checks the files.

## Files

They are attached to the [latest release](../../releases/latest).

| File | Size (bytes) | SHA-256 |
|---|---|---|
| `split3d_auto_encoder.onnx` | 889104812 | `51b209927eade293da6ae288837133dcc0fc8681183b8f88b6911b01575045b9` |
| `split3d_auto_decoder.onnx` | 16595075 | `3ecc2a27c81c65977d98225d331cd583109c51c9ca97dd20e643cab860239c54` |

## Origin and license

Both files are the Segment Anything Model 2.1 (SAM 2.1, "hiera large") by Meta Platforms, Inc., converted to the ONNX format. The model was not retrained and what it computes is unchanged.

SAM 2.1 is released under the Apache License 2.0, and so are these files. See [LICENSE](LICENSE) and [NOTICE](NOTICE).

Original model: https://github.com/facebookresearch/sam2
