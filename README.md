# Lipstick Ladies

A static photo timeline for the Lipstick Ladies weekly call archive, established in 2020.

## Local Development

This site is plain HTML, CSS, and JavaScript. No build step is required.

Run a local static server from the repo root:

```sh
ruby -run -e httpd . -p 8000
```

Then open:

```text
http://localhost:8000
```

## Adding Photos

Photos live in `images/` and are referenced from the `YEARS` data array in `index.html`.

Use dated filenames:

```text
YYYY-MM-DD-a.jpg
YYYY-MM-DD-b.png
```

For multiple photos on the same date, continue the letter suffix in order.

## Notes

- `new-photos/` is a temporary import folder and should not be committed.
- `.DS_Store` should not be committed.
- The page renders image entries, quotes, milestones, vibes, and crushes from `index.html`.
