# Node.js Hello World Application
This is a simple Node.js application using Express that dynamically greets the user based on URL parameters.

const express = require('express');
const app = express();
const port = 3000;

#app.get('/hello', (req, res) => {
#  const name = req.query.name || 'World';
#  res.send(`Hello, ${name}!`);
#});
#
#app.listen(port, () => {
#  console.log(`App listening at http://localhost:${port}`);
#});
