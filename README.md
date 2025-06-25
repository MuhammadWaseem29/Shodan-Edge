
# Shodan Edge

Shodan Edge is a Chrome extension for bug bounty hunters to streamline Shodan queries by combining a base query with multiple target domains and opening filtered results in new tabs.

## Features

- Combine Shodan base queries with domains (wildcards supported)
- Automatically open results in new tabs with delay control
- Glassmorphism UI with dark/light mode
- Accessibility features (ARIA, high contrast)
- Custom tab delay (500–5000 ms)
- Placeholder for recent query tracking

## Installation

Clone the repo:
```

git clone [https://github.com/MuhammadWaseem29/Shodan-Edge.git](https://github.com/MuhammadWaseem29/Shodan-Edge.git)
cd Shodan-Edge

```

Verify the following files exist:
- manifest.json
- popup.html
- popup.js
- style.css
- icon.png

Load extension:
- Go to chrome://extensions/
- Enable Developer mode
- Click "Load unpacked" and select the Shodan-Edge folder

## Troubleshooting

If icon.png error:
```

chmod 644 icon.png

```

If manifest.json error:
```

chmod 644 manifest.json

```

## Usage

- Click the Shodan Edge icon in Chrome
- Enter a Shodan query (e.g., cpe:"cpe:2.3:a:apache:http_server:2.4.*")
- Enter target domains (one per line)
- Click "Filter & Open" to launch result tabs
- Use gear icon to adjust tab delay
- Clear button is a placeholder (not implemented yet)

## Future Enhancements

- Implement clear input button
- Save/display recent queries using chrome.storage.local
- Add tooltips and settings persistence
- Export/import query presets

## License

MIT License

## Contact

Created by Muhammad Waseem  
Email: muhammadwaseem@bugcrowdninja.com  
LinkedIn: https://www.linkedin.com/in/muhammadwaseem11/  
Twitter: https://x.com/wgujjer11
```

