# 3D models

A collection of 3D models, designed in Fusion 360 and exported as STL for 3D
printing.

## Models

| Model | Description |
| --- | --- |
| [Philips OneBlade Pro 360 comb](philips-oneblade-pro-360-comb/) | Replacement sliding comb for the OneBlade Pro 360 adjustable beard comb (CP2176/01) |

## Layout

Each model lives in its own directory, named in lowercase with hyphens:

```
<model-name>/
├── README.md                   # what it is, what it fits, how to print it
├── <model-name>.stl            # print-ready mesh (required)
├── <model-name>-<variant>.stl  # alternative versions, e.g. split (optional)
├── <model-name>.f3d            # Fusion 360 source or STEP export (optional)
└── images/                     # photos and renders (optional)
```

## Adding a model

1. Create a directory named after the model.
2. Export the body from Fusion 360 as STL into it.
3. Copy the README of an existing model and fill it in.
4. Add a row to the table above.

## License

The models are licensed under
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You may share,
print, remix and sell them as long as you credit Otto Siikasmaa and link back
to this repository. See [LICENSE](LICENSE).
