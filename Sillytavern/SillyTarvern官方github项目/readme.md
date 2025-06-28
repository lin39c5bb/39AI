## FROM HERE YOU CAN KNOW HOW TO DOWNLOAD SILLYTAVERN WHATEVER YOUR DEVICE IS
## 从这里找到sillytavern任意端的安装教程
[SillyTavern](https://github.com/SillyTavern/SillyTavern)


SillyTavern provides a single unified interface for many LLM APIs (KoboldAI/CPP, Horde, NovelAI, Ooba, Tabby, OpenAI, OpenRouter, Claude, Mistral and more), a mobile-friendly layout, Visual Novel Mode, Automatic1111 & ComfyUI API image generation integration, TTS, WorldInfo (lorebooks), customizable UI, auto-translate, more prompt options than you'd ever want or need, and endless growth potential via third-party extensions.

We have a Documentation website to answer most of your questions and help you get started.

What is SillyTavern?
SillyTavern (or ST for short) is a locally installed user interface that allows you to interact with text generation LLMs, image generation engines, and TTS voice models.

Beginning in February 2023 as a fork of TavernAI 1.2.8, SillyTavern now has over 200 contributors and 2 years of independent development under its belt, and continues to serve as a leading software for savvy AI hobbyists.

Our Vision
We aim to empower users with as much utility and control over their LLM prompts as possible. The steep learning curve is part of the fun!
We do not provide any online or hosted services, nor programmatically track any user data.
SillyTavern is a passion project brought to you by a dedicated community of LLM enthusiasts, and will always be free and open sourced.
Branches
SillyTavern is being developed using a two-branch system to ensure a smooth experience for all users.

release -🌟 Recommended for most users. This is the most stable and recommended branch, updated only when major releases are pushed. It's suitable for the majority of users. Typically updated once a month.
staging - ⚠️ Not recommended for casual use. This branch has the latest features, but be cautious as it may break at any time. Only for power users and enthusiasts. Updates several times daily.
If you're not familiar with using the git CLI or don't understand what a branch is, don't worry! The release branch is always the preferable option for you.

What do I need other than SillyTavern?
Since SillyTavern is only an interface, you will need access to an LLM backend to provide inference. You can use AI Horde for instant out-of-the-box chatting. Aside from that, we support many other local and cloud-based LLM backends: OpenAI-compatible API, KoboldAI, Tabby, and many more. You can read more about our supported APIs in the Docs.

Do I need a powerful PC to run SillyTavern?
The hardware requirements are minimal: it will run on anything that can run NodeJS 18 or higher. If you intend to do LLM inference on your local machine, we recommend a 3000-series NVIDIA graphics card with at least 6GB of VRAM. Check your backend's documentation for more details.

Suggested Backends (not affiliated)
AI Horde - use models hosted by volunteers. Requires no further setup
KoboldCpp - a community's favorite for running GGUF models locally
tabbyAPI - a popular, lightweight, locally-hosted exl2 inference API
OpenRouter - a single API for many cloud providers (OpenAI, Claude, Meta Llama, etc.) as well as popular community models.
Questions or suggestions?
Discord server
	Join our Discord community! Get support, share favorite characters and prompts.
Or get in touch with the developers directly:

Discord: cohee, rossascends, wolfsblvt
Reddit: /u/RossAscends, /u/sillylossy, u/Wolfsblvt
Post a GitHub issue
I like your project! How do I contribute?
Send pull requests. Learn how to contribute: CONTRIBUTING.md
Send feature suggestions and issue reports using the provided templates.
Read this entire readme file and check the documentation website first, to avoid sending duplicate issues.
Screenshots
image image
Character Cards
SillyTavern is built around the concept of "character cards". A character card is a collection of prompts that set the behavior of the LLM and is required to have persistent conversations in SillyTavern. They function similarly to ChatGPT's GPTs or Poe's bots. The content of a character card can be anything: an abstract scenario, an assistant tailored for a specific task, a famous personality or a fictional character.

To have a quick conversation without selecting a character card or to just test the LLM connection, simply type your prompt input into the input bar on the Welcome Screen after opening SillyTavern. This will create an empty "Assistant" character card that you can customize later.

To get a general idea on how to define character cards, see the default character (Seraphina) or download selected community-made cards from the "Download Extensions & Assets" menu.

Key Features
Advanced text generation settings with many community-made presets
World Info support: create rich lore or save tokens on your character card
Group chats: multi-bot rooms for characters to talk to you and/or each other
Rich UI customization options: theme colors, background images, custom CSS, and more
User personas: let the AI know a bit about you for greater immersion
Built-in RAG support: add documents to your chats for the AI to reference
Extensive chat commands subsystem and own scripting engine
Extensions
SillyTavern has extensibility support.

Character emotional expressions (sprites)
Auto-Summary of the chat history
Automatic UI and chat translation
Stable Diffusion/FLUX/DALL-E image generation
Text-to-speech for AI response messages (via ElevenLabs, Silero, or the OS's System TTS)
Web Search capabilities for adding additional real world context to your prompts
Many more are available to download from the "Download Extensions & Assets" menu.
Tutorials on how to use them can be found in the Docs.

⌛ Installation
🪟 Windows
Warning

DO NOT INSTALL INTO ANY WINDOWS CONTROLLED FOLDER (Program Files, System32, etc).
DO NOT RUN START.BAT WITH ADMIN PERMISSIONS
INSTALLATION ON WINDOWS 7 IS IMPOSSIBLE AS IT CAN NOT RUN NODEJS 18.16
Installing via Git (recommended)
Install NodeJS (latest LTS version is recommended)
Install Git for Windows
Open Windows Explorer (Win+E)
Browse to or Create a folder that is not controlled or monitored by Windows. (ex: C:\MySpecialFolder)
Open a Command Prompt inside that folder by clicking in the 'Address Bar' at the top, typing cmd, and pressing Enter.
Once the black box (Command Prompt) pops up, type ONE of the following into it and press Enter:
for Release Branch: git clone https://github.com/SillyTavern/SillyTavern -b release
for Staging Branch: git clone https://github.com/SillyTavern/SillyTavern -b staging
Once everything is cloned, double-click Start.bat to make NodeJS install its requirements.
The server will then start, and SillyTavern will pop up in your browser.
Installing via GitHub Desktop
(This allows git usage only in GitHub Desktop, if you want to use git on the command line too, you also need to install Git for Windows)

Install NodeJS (latest LTS version is recommended)
Install GitHub Desktop
After installing GitHub Desktop, click on Clone a repository from the internet.... (Note: You do NOT need to create a GitHub account for this step)
On the menu, click the URL tab, enter this URL https://github.com/SillyTavern/SillyTavern, and click Clone. You can change the Local path to change where SillyTavern is going to be downloaded.
To open SillyTavern, use Windows Explorer to browse into the folder where you cloned the repository. By default, the repository will be cloned here: C:\Users\[Your Windows Username]\Documents\GitHub\SillyTavern
Double-click on the start.bat file. (Note: the .bat part of the file name might be hidden by your OS, in that case, it will look like a file called "Start". This is what you double-click to run SillyTavern)
After double-clicking, a large black command console window should open and SillyTavern will begin to install what it needs to operate.
After the installation process, if everything is working, the command console window should look like this and a SillyTavern tab should be open in your browser:
Connect to any of the supported APIs and start chatting!
🐧 Linux & 🍎 MacOS
For MacOS / Linux all of these will be done in a Terminal.

Install git and nodeJS (the method for doing this will vary depending on your OS)
Clone the repo
for Release Branch: git clone https://github.com/SillyTavern/SillyTavern -b release
for Staging Branch: git clone https://github.com/SillyTavern/SillyTavern -b staging
cd SillyTavern to navigate into the install folder.
Run the start.sh script with one of these commands:
./start.sh
bash start.sh
🐋 Installing via Docker
These instructions assume you have installed Docker, are able to access your command line for the installation of containers, and familiar with their general operation.

Using the GitHub Container Registry
Docker Compose (easiest)
Grab the docker-compose.yml file from the GitHub Repository and run the following command in the directory where the file is located. This will pull the latest release image from the GitHub Container Registry and start the container, automatically creating the necessary volumes.

docker-compose up
Customize the docker-compose.yml file to your needs. The default port is 8000. If you want to adjust the server configuration using environment variables, read the documentation here.

Docker CLI (advanced)
You will need two mandatory directory mappings and a port mapping to allow SillyTavern to function. In the command, replace your selections in the following places:

Container Variables
Volume Mappings
CONFIG_PATH - The directory where SillyTavern configuration files will be stored on your host machine
DATA_PATH - The directory where SillyTavern user data (including characters) will be stored on your host machine
PLUGINS_PATH - (optional) The directory where SillyTavern server plugins will be stored on your host machine
EXTENSIONS_PATH - (optional) The directory where global UI extensions will be stored on your host machine
Port Mappings
PUBLIC_PORT - The port to expose the traffic on. This is mandatory, as you will be accessing the instance from outside of its virtual machine container. DO NOT expose this to the internet without implementing a separate service for security.
Additional Settings
SILLYTAVERN_VERSION - On the right-hand side of this GitHub page, you'll see "Packages". Select the "sillytavern" package and you'll see the image versions. The image tag "latest" will keep you up-to-date with the current release. You can also utilize "staging" that points to the nightly image of the respective branch.
Running the container
Open your Command Line
Run the following command in a folder where you want to store the configuration and data files:
SILLYTAVERN_VERSION="latest"
PUBLIC_PORT="8000"
CONFIG_PATH="./config"
DATA_PATH="./data"
PLUGINS_PATH="./plugins"
EXTENSIONS_PATH="./extensions"

docker run \
  --name="sillytavern" \
  -p "$PUBLIC_PORT:8000/tcp" \
  -v "$CONFIG_PATH:/home/node/app/config:rw" \
  -v "$DATA_PATH:/home/node/app/data:rw" \
  -v "$EXTENSIONS_PATH:/home/node/app/public/scripts/extensions/third-party:rw" \
  -v "$PLUGINS_PATH:/home/node/app/plugins:rw" \
  ghcr.io/sillytavern/sillytavern:"$SILLYTAVERN_VERSION"
By default the container will run in the foreground. If you want to run it in the background, add the -d flag to the docker run command.

Building the image yourself
We have a comprehensive guide on using SillyTavern in Docker here which covers installations on Windows, macOS and Linux! Give it a read if you wish to build the image yourself.

Common issues with Docker
SELinux Permission Issues with Mounted Volumes
Linux distributions with SELinux enabled (such as RHEL, CentOS, Fedora, etc.) may prevent Docker containers from accessing mounted volumes due to security policies. This can result in permission denied errors when the container tries to read or write to the mounted directories.

Two suffixes :z or :Z can be added to the volume mount. These suffixes tell Docker to relabel file objects on the shared volumes.

The z option is used when the volume content will be shared between containers.
The Z option is used when the volume content should only be used by the current container.
Example:

# docker-compose.yml
volumes:
  ## Shared volume
  - ./config:/home/node/app/config:z
  ## Private volume
  - ./data:/home/node/app/data:Z
⚡ Installing via SillyTavern Launcher
SillyTavern Launcher is an installation wizard that will help you get setup with many options, including installing a backend for local inference.

For Windows users
On your keyboard: press WINDOWS + R to open Run dialog box. Then, run the following command to install git:
cmd /c winget install -e --id Git.Git
On your keyboard: press WINDOWS + E to open File Explorer, then navigate to the folder where you want to install the launcher. Once in the desired folder, type cmd into the address bar and press enter. Then, run the following command:
git clone https://github.com/SillyTavern/SillyTavern-Launcher.git && cd SillyTavern-Launcher && start installer.bat
For Linux users
Open your favorite terminal and install git
Git clone the Sillytavern-Launcher with:
git clone https://github.com/SillyTavern/SillyTavern-Launcher.git && cd SillyTavern-Launcher
Start the installer.sh with:
chmod +x install.sh && ./install.sh
After installation start the launcher.sh with:
chmod +x launcher.sh && ./launcher.sh
For Mac users
Open a terminal and install brew with:
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
Install git with:
brew install git
Git clone the Sillytavern-Launcher with:
git clone https://github.com/SillyTavern/SillyTavern-Launcher.git && cd SillyTavern-Launcher
Start the installer.sh with:
chmod +x install.sh && ./install.sh
After installation start the launcher.sh with:
chmod +x launcher.sh && ./launcher.sh
📱 Installing via Termux on Android OS
Note

SillyTavern can be run natively on Android devices using Termux, but we do not provide official support for this use case.

Please refer to this guide by ArroganceComplex#2659:

https://rentry.org/STAI-Termux
Unsupported platform: android arm LEtime-web. 32-bit Android requires an external dependency that can't be installed with npm. Use the following command to install it: pkg install esbuild. Then run the usual installation steps.

Command-line arguments
You can pass command-line arguments to SillyTavern server startup to override some settings in config.yaml.

Examples
node server.js --port 8000 --listen false
# or
npm run start -- --port 8000 --listen false
# or (Windows only)
Start.bat --port 8000 --listen false
Supported arguments
Tip

None of the arguments are required. If you don't provide them, SillyTavern will use the settings in config.yaml.

Option	Description	Type
--version	Show version number	boolean
--configPath	Override the path to the config.yaml file	string
--dataRoot	Root directory for data storage	string
--port	Sets the port under which SillyTavern will run	number
--listen	SillyTavern will listen on all network interfaces	boolean
--whitelist	Enables whitelist mode	boolean
--basicAuthMode	Enables basic authentication	boolean
--enableIPv4	Enables IPv4 protocol	boolean
--enableIPv6	Enables IPv6 protocol	boolean
--listenAddressIPv4	Specific IPv4 address to listen to	string
--listenAddressIPv6	Specific IPv6 address to listen to	string
--dnsPreferIPv6	Prefers IPv6 for DNS	boolean
--ssl	Enables SSL	boolean
--certPath	Path to your certificate file	string
--keyPath	Path to your private key file	string
--browserLaunchEnabled	Automatically launch SillyTavern in the browser	boolean
--browserLaunchHostname	Browser launch hostname	string
--browserLaunchPort	Overrides the port for browser launch	string
--browserLaunchAvoidLocalhost	Avoids using 'localhost' for browser launch in auto mode	boolean
--corsProxy	Enables CORS proxy	boolean
--requestProxyEnabled	Enables a use of proxy for outgoing requests	boolean
--requestProxyUrl	Request proxy URL (HTTP or SOCKS protocols)	string
--requestProxyBypass	Request proxy bypass list (space separated list of hosts)	array
--disableCsrf	Disables CSRF protection (NOT RECOMMENDED)	boolean
Remote connections
Most often this is for people who want to use SillyTavern on their mobile phones while their PC runs the ST server on the same Wi-Fi network. However, it can be used to allow remote connections from anywhere as well.

Read the detailed guide on how to set up remote connections in the Docs.

You may also want to configure SillyTavern user profiles with (optional) password protection: Users.

License and credits
This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.

TavernAI 1.2.8 by Humi: MIT License
Portions of CncAnon's TavernAITurbo mod used with permission
Visual Novel Mode inspired by the work of PepperTaco (https://github.com/peppertaco/Tavern/)
Noto Sans font by Google (OFL license)
Icon theme by Font Awesome https://fontawesome.com (Icons: CC BY 4.0, Fonts: SIL OFL 1.1, Code: MIT License)
Default content by @OtisAlejandro (Seraphina character and lorebook) and @kallmeflocc (10K Discord Users Celebratory Background)
Docker guide by @mrguymiah and @Bronya-Rand
kokoro-js library by @hexgrad (Apache-2.0 License)