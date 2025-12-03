# image_gallery_saver - Fixed Fork

This is a fixed fork of the `image_gallery_saver` Flutter plugin with compatibility fixes for modern Android build tools.

## Quick Start

### Using This Fork

Add to your `pubspec.yaml`:

```yaml
dependencies:
  image_gallery_saver:
    git:
      url: https://github.com/YOUR_USERNAME/image_gallery_saver.git
      ref: main
```

Then run:
```bash
flutter pub get
```

## What's Fixed?

This fork includes fixes for:
- ✅ Android Gradle Plugin 8.2.1+ compatibility
- ✅ Java 21 compatibility
- ✅ Kotlin 1.9.0+ support
- ✅ Android SDK 34 support
- ✅ Namespace declaration for AGP 8.0+

See [compatibility-fixes.md](./compatibility-fixes.md) for detailed information about all fixes.

## Documentation

- **[Compatibility Fixes](./compatibility-fixes.md)** - Detailed explanation of all fixes applied
- **[Original README](../README.md)** - Original plugin documentation

## Original Plugin

This is a fork of: https://github.com/hui-z/image_gallery_saver

Original package: https://pub.dev/packages/image_gallery_saver

## License

Same license as the original plugin (see [LICENSE](../LICENSE))


