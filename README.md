# armbian-builder

Automated Armbian OS image builder for Banana Pi M2 Ultra.

## Features

- Automated builds using GitHub Actions
- Minimal image without desktop environment
- Based on Ubuntu Jammy (22.04 LTS)
- Compressed output images
- Automatic releases on tags

## Usage

To trigger a new build:

1. Create and push a new tag:
   ```bash
   git tag -a v1.0.0 -m "Release v1.0.0"
   git push origin v1.0.0
   ```

2. Or manually trigger the workflow through GitHub Actions interface.

## License

This project is released into the public domain - see the [LICENSE](LICENSE) file for details.