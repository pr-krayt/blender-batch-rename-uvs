# Batch Rename UV Maps v0.0.1

First of all I've no idea about coding at all. This is completely vibe-coded using Google Gemini.
A lightweight, powerful workflow tool for Blender (5.1+) designed to handle bulk UV map renaming. Perfect for game engine pipelines (Unreal, Unity) where consistent naming is mandatory.

## Features
- **Two Renaming Modes:**
    - **Active UV Only:** Quickly rename the currently active UV layer on all selected objects, regardless of its original name.
    - **Specific Name Targeting:** Search for a specific UV map name and rename only that instance across your selection.
- **Modern Extension Support:** Built for the Blender 5.1+ extension framework.
- **Fail-safe:** Skips objects that don't match criteria to prevent errors.
- **Easy UI:** Access the tool instantly from the 3D Viewport Sidebar (`N` panel) under the **Edit** tab.

## Installation
Since this is a modern Blender extension, it is installed through the built-in Extensions system:

1. **Download:** Get the latest `batch_rename_uvs.zip` version from the [Releases](https://github.com/pr-krayt/blender-batch-rename-uvs/releases/tag/v0.0.1) page.
2. **Open Blender:** Navigate to **Edit > Preferences**.
3. **Get Extensions:** Click the **Get Extensions** tab in the sidebar.
4. **Install:** Click the **dropdown arrow** in the top-right corner of the window and select **Install from Disk...**
5. **Select Archive:** Choose the `batch_rename_uvs.zip` file you downloaded.
6. **Enable:** Ensure the addon is enabled in your list of extensions.

## Usage
1. Select all the mesh objects you wish to modify in the 3D Viewport.
2. Press **N** to open the Sidebar and click the **Edit** tab.
3. Locate the **Batch Rename UVs** panel and click **Rename Selected UVs**.
4. **Choose your mode:**
    - **Check "Rename Active UV Only":** Simply set the "New Name" and click OK. All selected objects will have their active UV layer renamed.
    - **Uncheck "Rename Active UV Only":** Use the "Target Name" field to define the existing name you are looking for, and the "New Name" to set the replacement.

## Contributing
Feedback and pull requests are welcome! If you encounter any issues, please open an issue in the **Issues** tab.

## License
This project is licensed under the MIT License.
