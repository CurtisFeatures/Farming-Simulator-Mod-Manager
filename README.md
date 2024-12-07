# Farming-Simulator-Mod-Manager

Curato Mod Manager (CMM) - A Windows Application for Simplified Game Mod Management

**Overview:**\
The **Curato Mod Manager (CMM)** is a Windows desktop application designed to simplify the management and customization of game mods for users. It provides an intuitive graphical user interface (GUI) that allows users to configure game settings, manage mod directories, and handle secure configurations like passwords, all stored in the Windows Registry.

The tool supports multiple game configurations, integrates with remote JSON services for dynamic updates.

The **Curato Mod Manager (CMM)** includes a powerful **Download Feature** designed to streamline the process of fetching and applying game-specific configurations, mod files, or other resources directly into the user's gaming environment. This feature is aimed at providing an effortless way for users to stay up-to-date with the latest configurations and mod packages while ensuring compatibility and ease of use.

**Key Features:**

1.  **Game Mod Configuration Management:**

-   Allows users to configure game settings for different saves/servers.
-   Supports dynamic loading and saving of game settings based on pre-defined configurations stored in the Windows Registry.

2.  **Download of Mods:**

-   New mods (not already available locally) are automatically downloaded to the specified local folder from a remote FTP server
-   Downloads are automatically saved to the appropriate directories within the user's gaming environment.
-   Ensures that mod files or configurations are correctly placed for immediate use without manual intervention.

3.  **Password Management:**

-   Passwords for each configuration are retrieved from the Windows Registry.
-   Updates specific XML configuration files with the password when applicable.
-   Uses checkboxes to determine whether passwords should be applied during specific configuration updates.

4.  **Dynamic Remote Configuration:**

-   Retrieves configuration data dynamically from JSON endpoints to prepopulate fields (This is password protected and only for use by Curato Farms members -- The Community server settings are available to all users excluding the server password)

5.  **Custom XML Handling:**

-   Updates game settings in XML files (gameSettings.xml) based on user input or selected mod directories.
-   Modifies specific XML attributes to enable or override directory settings dynamically.

6.  **Registry-Based Storage:**

-   Stores and retrieves user settings such as hostnames, ports, directories, usernames, and flags (e.g., setpassword checkboxes) from the Windows Registry.
-   Supports multiple configurations for up to 5 additional mod folders

7.  **User-Friendly Interface:**

-   Designed with ease of use in mind, offering intuitive checkboxes, buttons, and input fields.
-   Includes a "Reset" option to clear fields and start fresh.
-   Provides visual feedback (e.g., success or error messages) for user actions.

8. **Error Handling and Validation:**

-   Validates XML structure and remote endpoint responses for accuracy and integrity.
-   Ensures fallback mechanisms for scenarios where files or remote services are unavailable.
