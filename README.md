
Pterodactyl Eggs with PalGuard for Palworld
This repository contains Pterodactyl eggs that include PalGuard, a comprehensive anti-cheat solution for Palworld servers.

About PalGuard
PalGuard is a powerful anti-cheat plugin designed specifically for Palworld servers. It provides advanced protection against various types of cheats, hacks, and exploits, ensuring a fair and enjoyable gaming experience for all players.

Pterodactyl Eggs
The Pterodactyl eggs in this repository are pre-configured with PalGuard, making it easy to set up and manage a secure Palworld server. Simply follow the instructions below to get started.

Instructions
Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/pterodactyl-eggs.git
Navigate to the pterodactyl-eggs directory:

bash
Copy code
cd pterodactyl-eggs
Copy the PalGuard directory to your Pterodactyl egg directory:

bash
Copy code
cp -r PalGuard /path/to/pterodactyl/eggs/
Log in to your Pterodactyl panel and navigate to Admin > Nests > Eggs.

Click on Create New Egg and fill in the required details:

Name: PalGuard
Description: A powerful anti-cheat plugin for Palworld servers.
Docker Image: Your preferred Palworld server image.
Startup Command: The startup command for your Palworld server.
Under Configuration, select PalGuard from the dropdown menu.

Save the egg and navigate to Admin > Nests > Servers.

Click on Create New Server and fill in the required details:

Name: Your server name
Description: Your server description
Owner: Your Pterodactyl account
Nest: PalGuard
Egg: PalGuard
Docker Image: Your preferred Palworld server image.
Startup Command: The startup command for your Palworld server.
Configure any additional settings as needed and click on Create.

Your server is now set up with PalGuard! You can start and manage it from the Pterodactyl panel.

Support
For support or inquiries, please contact the PalGuard team at support@palguard.com.

License
This project is licensed under the MIT License - see the LICENSE file for details.
