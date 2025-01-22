
# UHC Minecraft Server

A fully-featured **UHC Server** running on **Paper 1.8.8** (formerly Spigot). This project includes exciting features like UHC with teams and scenarios, proximity voice chat, a practice arena, duels, parkour, and much more!

---

## Features
- **UHC Gameplay**: Teams, scenarios, and more.
- **Proximity Voice Chat**: Powered by [Skoice](https://skoice.garminho.dev/).
- **Main Lobby**: A central hub for players to gather.
- **Practice Arena**: Hone your skills before the big match.
- **Duels**: Face off against friends or foes in 1v1 battles.
- **Parkour**: Test your agility and patience.
- Additional custom features are waiting for you to explore!

---

## Dependencies
Before running the server, ensure you have the following dependencies set up:
1. **FateUHC License**: Required for UHC features.
2. **Skoice Bot**: For proximity voice chat.
3. **Database Setup**: Either **MySQL** or **MongoDB**.

---

## Quick Setup

### Step 1: Clone the Repository
First, clone this repository to your local machine:
```bash
git clone https://github.com/Dylouwu/MC_Server.git
cd MC_Server
```

### Step 2: Install Dependencies
1. Obtain the **FateUHC License** [here](https://builtbybit.com/resources/fateuhc-uhc-plugin-80-scenarios.9081/) and configure it as instructed in its documentation.
2. Set up the **Skoice Bot** for proximity chat. Follow the [Skoice setup guide](https://skoice.garminho.dev/).
3. Configure your **MySQL/MongoDB database** connection in the server settings.

### Step 3: Start the Server
Run the server by executing the `run.bat` file:
1. Open the project directory.
2. Double-click the `run.bat` file.

Ensure you have configured the `run.bat` file with the appropriate RAM allocation. By default, it is set to **16GB** of RAM. For example, set `-Xmx8G` to allocate 8GB of RAM.
I do not recommend allocating less than 8GB for the server.

### Step 4: Configure the Server
- Customize server properties and plugins as needed.
- Set up UHC scenarios, teams, and other gameplay configurations.
- [FateUHC Documentation](https://fateuhc.bghddevelopment.com/) 

---

## Contributing
Contributions are welcome! If you have any ideas for improvements or new features, feel free to submit a pull request, open an issue, or fork this project if you want to make your own server.

---

## Contact
If you need help setting up the server or have any questions, feel free to contact me on Discord: **pur1rin**.

---

Special thanks to the **FateUHC Plugin Team** and all contributors for making this server possible!
