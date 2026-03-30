| Method | Robocasa (100 demos; %) | Training speed (BS 8; s/it) | Training speed (BS 32; s/it) |
|--------|--------------------------|------------------------------|-------------------------------|
| GR00T N1.5 (1-frame) | 62.3 | 0.73 | 2.10 |
| + HAMLET (4-frames, stride 16) | 65.4 | 1.45 | OOM (5.98 with grad accum) |
| + ContextVLA (4-frames, stride 16) | 65.2 | 0.89 | 2.44 |
