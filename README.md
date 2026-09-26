# MiniMax H3 speed-ups, measured

Every known way to make the MiniMax H3 audio-video model render faster, measured on one RTX 5090 against the raw model
as ComfyUI's official template runs it: **no LoRA, 25 steps (euler)**, the pruned int8 model, Comfy Kitchen int8
attention, 1344x768. LoRAs and distilled models are candidates like every other method (they carry a LoRA stamp, and one
switch hides them). Each method runs in a fresh ComfyUI: one cold render, then the warm render the figure is based on.

Two test shots, as tabs: **Samurai in the rain · 5 s** (measured) and **Night market · 15 s** (being measured).

Quality pips are an AI's rating of still frames against the same tab's baseline; motion and sound are judged separately.

**Live page: https://plox-1.github.io/h3-speedups/**

This repository is the generated site only (`index.html`, `media/`, `fonts/`). The previous board, which measured
everything against a turbo-LoRA baseline, was retired on 2026-09-26; its history stays in this repository's commits.
