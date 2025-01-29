# CHIPPED
open source NFC (think Chipped Social)


To get started:

1. First install the required packages:
```bash
npm install node-nfc crypto web-nfc
```

2. Create a `.env` file in your project root:
```
NFC_SECRET_KEY=your-very-secure-secret-key
```

3. File structure should look like:
```
project/
  ├── SecureNFCTag.js    (previous code)
  ├── NFCInterface.js    (new code)
  ├── .env
  └── package.json
```

This implementation provides:

1. Full NFC reader/writer interfaces
2. Secure data handling
3. Event-based reading
4. Error handling
5. Configuration options
