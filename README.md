# Sly Store Library

![Sly Store Library](https://i.imgur.com/kmEOKrU.png)

## Overview

Sly Store Library is a tool designed to help you get your Steam game collection efficiently. With features such as game library, active updates and huge collections of game, it provides a comprehensive solution for gamers who want to keep their games up-to-date.

## Features

- **Dedicated Game Libarary Server**: Huge library collections.
- **Automatic Updates**: Receive updates about new releases and discounts.
- **Library Statistics**: View detailed statistics about your game collection.
- **Backup & Restore**: Backup your game settings and restore them easily.
- **Cross-Platform**: Compatible with Windows, macOS, and Linux.

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or higher)
- [Steam API Key](https://steamcommunity.com/dev/apikey)

### Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/steam-game-library-manager.git
    ```

2. Navigate to the project directory:
    ```sh
    cd steam-game-library-manager
    ```

3. Install dependencies:
    ```sh
    npm install
    ```

4. Configure your Steam API key:
    ```sh
    cp .env.example .env
    ```
    Edit the `.env` file and add your Steam API key.

5. Run the application:
    ```sh
    npm start
    ```

## Usage

### Basic Commands

- **List Games**: Display all games in your library.
    ```sh
    npm run list-games
    ```

- **Add Category**: Add a new category to your library.
    ```sh
    npm run add-category "RPG"
    ```

- **View Statistics**: Display statistics of your game collection.
    ```sh
    npm run stats
    ```

### Configuration

You can customize the behavior of the Steam Game Library Manager by editing the `config.json` file. Here you can set preferences for categories, update intervals, and more.

## Contributing

We welcome contributions from the community! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
    ```sh
    git checkout -b feature-name
    ```
3. Commit your changes.
    ```sh
    git commit -m "Description of your feature or bugfix"
    ```
4. Push to your branch.
    ```sh
    git push origin feature-name
    ```
5. Create a pull request detailing your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

If you have any questions or need further assistance, feel free to reach out:

- **Email**: support@your-email.com
- **Discord**: [Join our community](https://discord.gg/your-invite-link)
- **Twitter**: [Follow us on Twitter](https://twitter.com/your-twitter-handle)

---

*Happy gaming!*
