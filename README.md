# mblog
A mobile blog app built with React Native and Express.js.

## Description
mblog is a mobile blog application that lets you create, read, update, and delete blog posts from your phone. The client is built with React Native and communicates with an Express.js backend connected to a MySQL database. The UI is based on a Figma design and the entire application was developed from scratch.

## Screenshots
| Home Screen | Post Details |
|---|---|
| ![Home Screen](screenshots/screenshot_1.png) | ![Post Details](screenshots/screenshot_2.png) |

## Getting Started

### Dependencies
* Node.js and npm or yarn
* MySQL database
* React Native development environment ([setup guide](https://reactnative.dev/docs/environment-setup))

### Installing

* Clone the repository:
```
git clone https://github.com/dincertekin/mblog.git
```

* Install client dependencies:
```
cd mblog/client
npm install
```

* Install server dependencies:
```
cd mblog/server
npm install
```

* Configure MySQL by editing `app.js` in the `server` directory:
```js
host: 'your_mysql_host'
user: 'your_mysql_user'
password: 'your_mysql_password'
database: 'your_database_name'
```

### Executing program

* Start the server:
```
cd mblog/server
npm run start
```

* Start the client:
```
cd mblog/client
npm run start
```

* Open the app on your mobile device or emulator and start creating, editing, and reading blog posts.

## Help
Make sure your MySQL database is running before starting the server, otherwise the app will fail to connect.

## Contributing
Contributions are welcome! To get started:
1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

Please open an issue first for major changes to discuss what you'd like to change.

## License
This project is licensed under the [MIT](LICENSE) License, see the LICENSE.md file for details

## Acknowledgments
* Figma UI design inspiration
* [React Native](https://reactnative.dev)
* [Express.js](https://expressjs.com)
