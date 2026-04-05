# mblog

![Platform](https://img.shields.io/badge/platform-Android%20%7C%20iOS-blue)
![License](https://img.shields.io/badge/license-MIT-green)

mblog is a mobile blog app that lets you create, read, update, and delete blog posts from your phone. Built from scratch with a React Native client and an Express.js backend connected to MySQL.

## Screenshots

| Home Screen | Post Details |
|---|---|
| ![Home Screen](screenshots/screenshot_1.png) | ![Post Details](screenshots/screenshot_2.png) |

## Tech Stack

| Layer | Tool |
|---|---|
| Mobile Client | React Native |
| Backend | Express.js |
| Database | MySQL |
| UI Design | Figma |

## Installation

### Prerequisites

- Node.js and npm
- MySQL database
- React Native environment ([setup guide](https://reactnative.dev/docs/environment-setup))

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/dincertekin/mblog.git
   ```

2. Install dependencies for both client and server:
   ```bash
   cd mblog/client && npm install
   cd ../server && npm install
   ```

3. Configure your MySQL connection in `server/app.js`:
   ```js
   host: 'your_mysql_host',
   user: 'your_mysql_user',
   password: 'your_mysql_password',
   database: 'your_database_name'
   ```

## Usage

Start the server first, then the client:

```bash
cd mblog/server && npm run start
cd mblog/client && npm run start
```

Open the app on your device or emulator to start creating and reading posts.

## Troubleshooting

Make sure your MySQL database is running before starting the server, otherwise the connection will fail.

## Contributing

Contributions are welcome! To get started:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

For major changes, please open an issue first to discuss what you'd like to change.

## License

MIT License — see [LICENSE](./LICENSE) for details.
