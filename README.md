# HackWPI Official Website

## Getting Started
### Prerequisites

- Node.js

### Installation

1. Run `npm install` to install the required dependencies.
2. Add `HACKATHON_SECRET` environment variable for JWT token signing and verification.
3. Create `data` folder under root directory.
4. Create `users.data.js` inside `data` folder and add example users with the following format:
```
javascript
module.exports = [
    {
        email: 'hack@wpi.edu',
        password: 'password',
        role: 'admin',
    }
];
```

## License

This repo is maintained user MIT license.