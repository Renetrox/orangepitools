# EmulationStation Setup Script

This script automates the installation and configuration of EmulationStation on Linux systems. It is designed to work on various devices, including Orange Pi, Raspberry Pi, and generic Debian/Ubuntu systems.

---

## Features / Características

- Automatically installs and configures **EmulationStation** to run in **tty mode** (text mode).
- Installs the lightweight desktop environment **XFCE4**.
- Adds a launcher in RetroPie under the `Ports` section to start the desktop environment.
- Allows **EmulationStation** to start automatically on system boot without requiring a password.
- Configures the system to boot in **text mode** for optimal performance.

---

## Prerequisites / Requisitos

- A Linux-based operating system (Debian, Ubuntu, or similar).
- Sudo privileges for the user running the script.
- Internet access for downloading and installing packages.

---

## Usage / Uso

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/emulationstation-setup.git
   cd emulationstation-setup

    Make the script executable:

chmod +x emulationstation_setup.sh

Run the script:

    ./emulationstation_setup.sh

    Follow the on-screen instructions.

Notes / Notas

    EmulationStation will automatically start when the system boots into tty mode.
    To access the desktop environment, select "Desktop" in the RetroPie menu under the Ports section.
    This script is designed to work regardless of the username, as it dynamically detects the current user.

Contributions / Contribuciones

Feel free to fork this repository, submit pull requests, or report issues.

Siéntete libre de bifurcar este repositorio, enviar solicitudes de extracción o informar problemas.
License / Licencia

This project is licensed under the MIT License.


### **How to customize it:**
- Replace `https://github.com/yourusername/emulationstation-setup.git` with the URL of your GitHub repository.
- Add additional instructions or credits if necessary.

Let me know if you need further adjustments!

 
