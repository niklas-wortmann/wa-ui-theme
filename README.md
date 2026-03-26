# WA Inspired UI Theme

Wes Anderson-inspired pastel UI themes for JetBrains IDEs using the Islands UI.

## Included Themes

- WA Dark (Balanced)
- WA Light (Balanced)
- WA Dark (Vibrant)
- WA Light (Vibrant)

## Compatibility

- Since build: `253` (IntelliJ Platform 2025.3+)
- Target IDE for development: `2025.3`

## Local Development

```bash
./gradlew verifyPluginProjectConfiguration verifyPluginStructure buildPlugin
```

The plugin ZIP is generated in `build/distributions/`.

## Publish Checklist

1. Set required environment variables:
   - `PUBLISH_TOKEN`
   - `CERTIFICATE_CHAIN`
   - `PRIVATE_KEY`
   - `PRIVATE_KEY_PASSWORD`
2. Run verification and packaging tasks.
3. Publish with:

```bash
./gradlew publishPlugin
```

4. Upload listing screenshots in JetBrains Marketplace `Media` section from:
   - `docs/marketplace/media/wa-theme-screenshot-1.png`
   - `docs/marketplace/media/wa-theme-screenshot-2.png`

Detailed steps: `docs/marketplace/UPLOAD_CHECKLIST.md`.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
