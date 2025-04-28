# WhatsApp Blast Tool

Send bulk WhatsApp messages for free using your real WhatsApp account.

## Requirements
- Node.js installed (v16 or later)
- WhatsApp account

## Installation
```bash
npm install
```

## Running
```bash
npm start
```

- A QR Code will appear in the terminal.
- Scan the QR code using WhatsApp on your phone.
- Open `http://localhost:3000` in your browser.
- Upload a CSV file with a `number` column (Malaysian numbers, e.g., 60123456789).
- Type your message (supports text + emojis).
- Click "Send Blast".

## Important
- Do not spam! WhatsApp may block your account if you send too many messages too quickly.
- This tool introduces a random 2-5 seconds delay between each message to mimic human behavior.
