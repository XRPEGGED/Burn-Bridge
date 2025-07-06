xrpegged-burn-bridge/
├── backend/
│   ├── index.js             # Node.js listener service
│   ├── xrplListener.js      # XRP WebSocket connection + memo parsing
│   ├── solanaSender.js      # Sends XRPEGGED tokens
│   ├── utils/
│   │   └── logger.js        # Optional logging
│   └── .env.example         # Template for your secrets
├── frontend/
│   ├── index.html           # Simple UI with instructions and address
│   ├── style.css            # Optional styling
├── package.json
├── README.md
└── .gitignore
