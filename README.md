# renovate-presets

A collection of Renovate configuration presets that works well with modern Python projects. Use these presets to standardize dependency update rules across your repositories.

## Usage

Include the presets in your Renovate configuration:

```json5
{
  "extends": [
    // https://github.com/ulgens/renovate-presets
    "github>ulgens/renovate-presets:all.json5",
  ],
}
```

## Presets

- `all` — sensible defaults for most repositories

## Contributing
Contributions are welcome! Feel free to open issues or pull requests to improve the presets.
