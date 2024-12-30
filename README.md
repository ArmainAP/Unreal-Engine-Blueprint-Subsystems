# Blueprint Subsystems Plugin

The **Blueprint Subsystems Plugin** is a tool for Unreal Engine developers, providing fully Blueprintable implementations of various subsystem types. 

## Features

- **Blueprintable Subsystems**: Create and manage subsystems directly in Blueprints.
- **Ease of Integration**: No coding required to define subsystems – just use Blueprints!
- **Centralized Configuration**: Manage blueprint subsystem initialization directly through the Unreal Engine project settings.

## Installation

1. **Download the Plugin**: Obtain the Blueprint Subsystems Plugin from your preferred source.
2. **Add to Your Project**: Copy the plugin into your Unreal Engine project's `Plugins` directory. If the directory does not exist, create it.
3. **Enable the Plugin**:
   - Open the Unreal Engine Editor.
   - Go to the **Plugins** section in the editor.
   - Search for and enable the **Blueprint Subsystems Plugin**.
   - Restart the editor to apply changes.

## Configuration

Blueprint-created subsystems require configuration in the project settings:

1. Open **Project Settings** in the Unreal Engine Editor.
2. Navigate to **Blueprint Subsystem Settings**.
3. Add your Blueprint subsystems to the appropriate categories:
   - **Blueprint Game Instance Subsystems**
   - **Blueprint Local Player Subsystems**
   - **Blueprint World Subsystems**

This ensures that your Blueprint subsystems are correctly instantiated and managed by the engine.

## Usage

1. **Create a Subsystem Blueprint**:
   - In the Content Browser, create a new Blueprint and select the desired subsystem type as the parent class (e.g., `UGameInstanceSubsystem`).
2. **Implement Custom Logic**:
   - Open the Blueprint and add custom logic and functionality as needed.
3. **Register the Subsystem**:
   - Add your Blueprint subsystem to the **Blueprint Subsystem Settings** in the Project Settings.

The plugin will handle the rest, ensuring your subsystems are instantiated and functional at the appropriate stages of your game's lifecycle.

## Contributing

We welcome contributions to enhance this plugin! Feel free to report bugs, suggest features, or submit pull requests. Together, we can make this plugin even more robust and useful.

## License

This plugin is released under the AGPL-3.0 license. For questions regarding licensing or alternative arrangements, please contact the development team.

## Credits

This plugin was designed and developed to empower Unreal Engine developers by simplifying subsystem creation and management in Blueprints. Thank you to the Unreal Engine community for the inspiration and feedback that made this plugin possible. 
