<p align="center">
  <img src="https://ibb.co/G3FCQrj8"><img src="https://i.ibb.co/5x2shJVS/crafthostlogo.jpg" alt="CraftHostBanner"
</p>

<h1 align="center">CraftHostDaemon</h1>
## Overview
CraftHost Daemon is the daemon for the CraftHost Panel.

## Installation
1. Clone the repository:
`git clone https://github.com/hydren-dev/HydraDAEMON`

2. Install dependencies:
`npm install`

3. Configure CraftHostDAEMON:
- Get your Panel's access key from the Hydra panel's config.json file and set it as 'remoteKey'. Do the same for the other way, set your CraftHostDaemon access key and configure it on the Panel.

4. Start the Daemon:
`node . # or use pm2 to keep it online`

## Configuration
Configuration settings can be adjusted in the `config.json` file. This includes the authentication key for API access.

## Usage
The daemon runs as a background service, interfacing with the CraftHost Panel for operational commands and status updates. It is not typically interacted with directly by end-users.

## Contributing
Contributions to enhance the functionality or performance of the CraftHost Daemon are encouraged. Please submit pull requests for any enhancements.

## License
(c) 2024 MJ and contributors. This software is licensed under the MIT License.


## Credits
SRYDEN
Skyport
