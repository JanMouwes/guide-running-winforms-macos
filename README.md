### Running WinForms applications on MacOS
 1. Make sure you're [running in a mono-environment](https://www.mono-project.com/docs/getting-started/mono-basics/).
 2. Set `--arch=32` as an environment variable. WinForms' driver only supports 32-bit environments.
 3. Be patient. When you're running the application for the first time it can take a while to initialise. See also: https://stackoverflow.com/a/19762093/11047164
 
 Note: this was tested on MacOS Mojave, version 10.14.6.
