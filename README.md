<p align="center"><img width="150" alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://upload.wikimedia.org/wikipedia/commons/c/c9/PhpStorm_Icon.svg"></p>

<h1 align="center">PhpStorm Settings on Linux OS</h1>


#### :computer: Enable Tailwind autocomplete & Run commands >_ in PhpStorm terminal

- Download and unpack ***PhpStorm v2022.2.1*** package to **_/opt_** directory and running this installation should make commands available in the terminal.

#### Create PhpStorm shortcut in OS Applications (Start Bar)

- Create file in: ``/usr/share/applications/phpstorm.desktop``
- Inside **"phpstorm.desktop"** file:
 
  -   ```bash
      [Desktop Entry]
      Version=2022.2.1
      Name=PhpStorm-Tailwind
      Comment=Phpstorm
      Exec=/opt/PhpStorm-222.3739.61/bin/phpstorm.sh
      Icon=/opt/PhpStorm-222.3739.61/bin/phpstorm.svg
      Terminal=false
      Type=Application
      Categories=Utility;Application;
      ```

### PhpStorm change terminal:

-   Settings > Tools > Terminal > Shell path: /bin/bash -i
