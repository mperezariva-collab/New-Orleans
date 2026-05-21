# HKG Fragrance Catalog

Static catalog prepared for GitHub Pages.

## Structure

```text
hkg-fragrance-catalog-github/
  index.html
  assets/
    products/
    logos/
    gallery/
  data/
```

## Product Images

Place product images in:

```text
assets/products/
```

For automatic matching, name each image like the product name in the catalog.

Example:

```text
assets/products/AZZ FOREVER WANTED ELIXIR 100ML (M).png
```

## Publish With GitHub Pages

1. Create a new GitHub repository.
2. Upload the full contents of this folder.
3. In GitHub, go to `Settings > Pages`.
4. Set source to `Deploy from a branch`.
5. Choose branch `main` and folder `/root`.
6. Open the GitHub Pages URL after it finishes deploying.

## Admin Note

The current admin login is a visual lock for the static catalog. Do not place GitHub API tokens directly in `index.html`.
