
# AutoGrade

AI-powered color grading for videos and photos. Uses SAM for subject isolation and HDRNet for cinematic color grading, all running on CUDA/PyTorch. Save money on expensive plugins and apps.

## What is this

AutoGrade is a tool I built because I got tired of paying for overpriced color grading plugins that don't even use AI properly. It isolates subjects using Meta's Segment Anything Model, then applies cinematic color grading through a HDRNet-based pipeline — all GPU-accelerated.

Think of it as DaVinci Resolve's color grading meets AI segmentation, but open source and running locally on your hardware.

## What it does

- Subject isolation using SAM (Segment Anything Model)
- AI-driven color grading via HDRNet bilateral learning
- CUDA-accelerated processing through PyTorch
- Works on both video and photos
- Batch processing support

## Requirements

- NVIDIA GPU with CUDA support
- Python 3.10+
- PyTorch with CUDA
- Enough VRAM to not cry (8GB minimum, 12GB+ recommended)

## Installation

```bash
under construction :(
```

## Why I built this

I do cinematic content creation and color grading is like 60% of making things look good. Every tool out there either costs a fortune, runs on CPU like it's 2005, or doesn't give you real control. So I built my own.

## License

GPL-3.0 — use it, learn from it, contribute to it. Just don't close-source it and sell it as your own thing.

