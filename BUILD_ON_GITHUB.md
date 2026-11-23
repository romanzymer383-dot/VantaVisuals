# Build Vanta Visuals automatically on GitHub

This project includes a GitHub Actions workflow in `.github/workflows/build.yml`.

1. Upload this folder to a GitHub repository (the repository should be named VantaVisuals and branch `main`).
2. Open the repository's **Actions** tab.
3. Select **Build Vanta Visuals**, then **Run workflow** (or push files to `main`).
4. Open the completed run and download the `VantaVisuals-JAR` artifact.
5. Place the downloaded `.jar` in the Minecraft `mods` folder of a Fabric 1.21.11 + Java 21 installation.

The build has not been tested in this environment. The workflow will report any build failure.
