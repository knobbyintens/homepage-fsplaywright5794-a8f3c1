# Personal homepage

A tiny static site for my hand-maintained homepage.

## Layout

- `pages/about.md` — profile and curated picks (hand-written).
- `pages/teaching.md` — teaching notes (hand-written).
- `resources/index.md` — rendered resource list. Generated; do not edit by hand.
- `data/resources.csv` — sample input for the resource-list generator.
- `scripts/build_resource_list.py` — renders `resources/index.md` from `data/resources.csv`.
- `assets/style.css` — styles.

## Build

```bash
python scripts/build_resource_list.py
```

The generated resource list is kept separate from the hand-written pages.
