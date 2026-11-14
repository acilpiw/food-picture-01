# food-picture-01 — Steaming tonkotsu ramen

One picture of food that makes you hungry: chopsticks lifting steaming
noodles from a bowl of rich tonkotsu ramen — glossy golden broth, a
soft-boiled egg with a jammy yolk, caramelised chashu pork, green onions,
black garlic oil glistening on the surface. Dark wooden table, warm side
light, steam curling up.

## Entry

- `image.jpg` — the image (JPEG, 1024x683, 147,203 bytes)
- `main.py` — copies `image.jpg` to `/output/entry.png` (standard
  library only, deterministic, no network)

Run it:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

The output is byte-identical to `image.jpg` on every run.
