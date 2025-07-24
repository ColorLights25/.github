# 🚀 ColorLights25 - ChicBase Project

Build Flutter apps faster by sharing code across multiple applications.

## 🎯 Quick Setup

Get the clone tools and run the script for your workflow: [/clone-tools](/clone-tools/)

```
git clone git@github.com:Chic-Base/clone-tools.git
cd clone-tools
chmod +x *.sh

# Choose your workflow:
./clone_app.sh ColorLights25        # Full app development
./clone_skeleton.sh ColorLights25   # App development (the app itself)
./clone_superbase.sh ColorLights25  # Shared components development
```

## 📦 What Gets Cloned

**🎨 Skeleton Development** (App definition)
- **skeleton/** - The app itself: all screens, navigation, and features
- **metadata/** - App configuration, assets, and translations
- **sharedkernel/** - Shared utilities (read-only)

**🏗️ Superbase Development** (Shared components)
- **superbase/** - Reusable UI components for all apps
- **metadata/** - Test configurations
- **sharedkernel/** - Core utilities (read-only)

**🚀 Full App Development** (Everything)
- All 6 modules for complete app building

## ⚠️ Important

- Keep exact folder names (skeleton, metadata, etc.)
- Clone all repos in the same parent directory
- For SSH issues: [GitHub SSH Setup](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)

---

*ChicBase: Build once, use everywhere* ✨
