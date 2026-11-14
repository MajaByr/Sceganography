# :confetti_ball: Sceganography :confetti_ball:

*Practical implementations of steganographic and watermarking algorithms in Python.*

## Prerequisites

### Uv

Verify if `uv` is installed in your environment, eg. by:

```bash
uv --version
```

If `uv` is not installed, you may install it with `pip`:

```bash
pip3 install uv
```

or with your system:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

## Set up

Set up the environment with:

```bash
uv sync
```

## Implemented Algorithms

* [Reversible data hiding, 2006](02_reversible_data_hiding/reversible_data_hiding.ipynb)
* [An Image Steganographic Scheme Based on Pixel-Value Differencing and LSB Replacement Methods, 2004](03_pixel_value_differencing/pixel_value_differencing.ipynb)
* [Edge Adaptive Image Steganography Based on LSB Matching Revisited, 2010](05_edge_adaptive_lsb/edge_adaptive_image_lsb.ipynb)
