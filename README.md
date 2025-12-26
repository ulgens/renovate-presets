# renovate-presets

A collection of Renovate configuration presets that works well with modern Python projects. Use these presets to standardize dependency update rules across your repositories.

Renovate Docs - Presets: https://docs.renovatebot.com/key-concepts/presets/

## Usage

Include all presets in your Renovate configuration:

```json5
{
  "extends": [
    // https://github.com/ulgens/renovate-presets
    "github>ulgens/renovate-presets:all.json5#v0.0.1",
  ],
}
```

or you can use a group of them:

```json5
{
  "extends": [
    // https://github.com/ulgens/renovate-presets
    "github>ulgens/renovate-presets:misc.json5",
    "github>ulgens/renovate-presets:pre-commit.json5",
    "github>ulgens/renovate-presets:python.json5",
  ],
}
```

## Presets

- `all`: Sensible defaults for most repositories, includes all the presets below.
- `misc`: Miscellaneous settings that don't directly relate to a particular category or manager
- `ci`: CI related settings, including "CI Dependencies" group
- `docker`: Docker related settings, including "Docker Dependencies" group
- `pre-commit`: pre-commit / prek related settings, including "pre-commit Dependencies" group
- `python`: Python related settings, including "Python" and "Python Dependencies" groups

## Contributing

Contributions are welcome! Feel free to open issues or pull requests to improve the presets.

## Professional Support 📝

These presets are maintained as part of my ongoing work with dependency management and automation. If your organization needs help with

- Dependency management automation
- Code quality and linting standards
- CI/CD pipeline setup
- Backend development best practices

or other sort of assistance with a Python project, I'm available for consulting engagements. [Connect with me on LinkedIn](https://www.linkedin.com/in/ulgens/) and let's discover how I can help your team succeed!
