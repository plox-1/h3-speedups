# MiniMax H3 speed-ups, measured

**A new comparison is in progress.** Every known way to make the MiniMax H3 audio-video model render faster is being
re-measured on one RTX 5090 against the raw model as ComfyUI's official template runs it: no LoRA, 25 steps (euler),
Comfy Kitchen int8 attention, 1344x768. LoRAs and distillations are candidates like every other method. Two test shots
(5 s and 15 s), and every method gets a cold start and a warm render.

The previous board, which measured everything against a turbo-LoRA baseline, has been retired.

**Live page: https://plox-1.github.io/h3-speedups/**

This repository is the generated site only (`index.html`, `media/`, `fonts/`).
