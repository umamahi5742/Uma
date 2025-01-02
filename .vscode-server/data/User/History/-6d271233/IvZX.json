const express = require('express');
const app = express();

app.get('/', (req, res) => {
    res.send('Hello, World! Deployed with CI/CD Pipeline!');
});

const PORT = process.env.PORT || 3000; // Use environment variable for the port
app.listen(PORT, () => console.log(`Server running on port ${PORT}`));

