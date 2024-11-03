## MLBB Assistant Installation Guide

### Prerequisites
1. Android device running Android 6.0 or higher
2. Enable "Unknown Sources" in your device settings

### Installation Steps

1. Download the APK
   - Get the latest release APK from the releases page
   - Transfer it to your Android device

2. Install the App
   - Open the APK file on your device
   - Follow the installation prompts
   - Grant required permissions when asked

### Development Setup

1. Clone the repository
```bash
git clone <repository-url>
```

2. Install dependencies
```bash
npm install
```

3. Run in development mode
```bash
ns run android
# or
ns run ios
```

### Permissions Required
- Storage: For caching game data
- Internet: For updates and translations
- Overlay: For in-game overlay features

### Troubleshooting

If you encounter installation issues:
1. Ensure "Unknown Sources" is enabled
2. Check device compatibility
3. Clear cache and retry installation

For development issues:
1. Clear npm cache: `npm cache clean --force`
2. Remove node_modules: `rm -rf node_modules`
3. Reinstall dependencies: `npm install`