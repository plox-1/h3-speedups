# MiniMax H3 speed-ups, measured

Every known way to make the MiniMax H3 audio-video model render faster, measured on one RTX 5090
with the same prompt and seed. Each method shows its real frames and clip.

**Live board: https://plox-1.github.io/h3-speedups/**

- Speed-up is the baseline's render time divided by the method's, both measured in the same session
  on the same machine. Differences under about 5% are noise.
- Quality pips are an AI's ratings of still frames. Nobody has rated motion, lip sync or sound yet:
  open a row and watch the clip.
- Every clip is the render exactly as ComfyUI saved it, with its workflow embedded: drag one into
  ComfyUI to get the graph that produced it.

This repository is the generated site only (`index.html`, `media/`, `fonts/`).
