
# Biome Config

## What is Biome?

Biome is a performant toolchain for web projects that replaces both ESLint and Prettier. It's written in Rust and extremely fast.

## Installation

1. First, install Biome in your project:

    ```bash
    bun add -D @biomejs/biome
    ```

2. Install this configuration package:
   ```bash
   bun add -D @itsbroly/biome-config
   ```

3. Initialize Biome in your project:
    ```bash
    bunx biome init
    ```

4. Extend your `biome.json` file:
    ```json
    "extends": ["@itsbroly/biome-config"],
    ```


## Usage

### Using with VS Code

1. Install the Biome VS Code extension
2. Enable the extension in your workspace
3. The configuration will be automatically applied to your project

### Using from Command Line

Format your code:
```bash
npx biome format ./src
```

Lint your code:
```bash
npx biome lint ./src
```

Check formatting:
```bash
npx biome check ./src
```

## Configuration Details

This configuration includes:

- Standardized formatting rules
- Consistent code style guidelines
- Best practices for TypeScript development
- Custom rules specific to RayPeatLibrary repos

## Contributing

If you want to suggest changes to this configuration:

1. Fork the repository
2. Create a feature branch
3. Submit a Pull Request

## License

MIT

## Support

For issues or questions specific to this configuration, please open an issue in the repository.
