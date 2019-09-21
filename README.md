Private Blog Writing with Scalable Image Upload using AWS, Node, React, Redis, Mongo, Jest, Puppeteer
To run in dev mode create a dev.js file in config folder in the format
module.exports = {
  googleClientID:<GoogleID>,
  googleClientSecret: <Google Secret>,
  mongoURI: <MONGO_DB_URL>,
  cookieKey: "123123123",
  redisUrl: "redis://127.0.0.1:6379"
};
