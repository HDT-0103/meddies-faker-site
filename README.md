# meddies-faker site

The public showcase page of meddies-faker: synthetic patients and people sampled from sourced census, survey and
hospital statistics in 18 countries and 20 languages.

`index.html` is generated, not edited by hand. Rebuild it from the meddies-faker repository:

```bash
uv run --group bench python tools/showcase/build.py --bench <benchmark dir> --standalone --unreleased --out index.html
```

Country pack data shown on the page is CC BY-SA 4.0 with each source's attribution.
