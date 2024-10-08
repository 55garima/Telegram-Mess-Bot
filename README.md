# AIT MESS BOT 🤖 Telegram Bot 
## College Mess Querying Telegram Bot

This Telegram bot project aims to provide students with information on daily menus for college mess and different canteens. It allows users to query the available food options and obtain detailed menu information. The bot is developed using TypeScript and the Telegraf library, built on top of the Telegram API 2.0.

## Features

- Query college mess menus and canteen options through a Telegram bot interface.
- Interactive inline keyboard options for easy selection of mess or canteen.
- Custom intent detection system based on a lite version of an inverted index map.
- Efficient indexing and search functionality to identify user intents from queries.
- Accurate and relevant responses by mapping user queries to specific menu items or information.
- Integration of Telegram API 2.0 functionalities for seamless communication.

Support Natural Language query | Inline Keyboard Support 
First Interaction - Bot Start | Food Court - OAC Menu  

## Getting Started

To get started with the College Mess Querying Telegram Bot, follow these steps:

1. Clone the repository: `git clone https://github.com/55garima/Telegram-Mess-Bot?tab=readme-ov-file`
2. Install dependencies: `npm install`
3. Configure the bot token: Replace `BOT_TOKEN` in `.env` file with your Telegram bot token.
4. Build the TypeScript code: `npm run build` or 'tsc'
5. Start the bot: `npm start`

## Usage

- Start a conversation with the bot on Telegram.
- Use the provided inline keyboard options to select a mess or canteen.
- Alternatively, type natural language queries to inquire about specific menu items.
- The bot will respond with relevant menu information or clarifying questions if required.

## Tech Stack

The AIT Mess Querying Telegram Bot is built using the following technologies and libraries:

- TypeScript: A statically typed superset of JavaScript that enhances code maintainability and scalability.
- Telegraf: A modern and powerful Telegram Bot API framework for Node.js.
- Telegram API: Version 2.0 of the Telegram Bot API, used for seamless communication between the bot and users.
- Lite Inverted Index Map: A custom lightweight version of an inverted index map, inspired by Elasticsearch, for efficient intent detection.
- Node.js: A JavaScript runtime environment that enables server-side execution of JavaScript code.
- npm: A package manager for installing and managing project dependencies.

## Backend Communication

The College Mess Querying Telegram Bot utilizes the long polling method for backend communication. 
In this approach, the main server will be Telegram's own server, which maintains a long queue to process messages by default. 
The bot's own server is responsible for handling incoming requests and processing them accordingly. 
This setup ensures efficient and reliable communication between the bot and Telegram users.

## License

This project is licensed under the [LICENSE](LICENSE).

## Acknowledgments

- The Telegraf library for simplifying Telegram bot development.
- Inspiration from Elasticsearch for the custom intent detection approach.
- The Telegram API documentation for valuable resources.
