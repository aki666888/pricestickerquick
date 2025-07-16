# Price Sticker Quick

A simple desktop application for printing price labels on Zebra thermal printers (3.3" × 4.1" paper, 2" × 1.25" labels).

## Features

- Clean, easy-to-use interface
- Live preview of labels
- Print multiple labels at once
- Formatted price display with smaller cents
- Works with any printer, optimized for Zebra thermal printers

## Download

Download the latest Windows executable from the [Releases](https://github.com/aki666888/pricestickerquick/releases) page.

## Usage

1. Run `PriceStickerQuick.exe`
2. Enter the price (e.g., 14.99)
3. Enter the item name
4. Set the number of labels to print
5. Click "Print Labels" or press Ctrl+P
6. Select your Zebra printer in the print dialog

## Building from Source

### Prerequisites
- Node.js (v14 or higher)
- npm

### Installation
```bash
git clone https://github.com/aki666888/pricestickerquick.git
cd pricestickerquick
npm install
```

### Running in Development
```bash
npm start
```

### Building Windows Executable
```bash
npm run dist
```

The executable will be created in the `dist` folder.

## Printer Settings

For best results with Zebra printers:
- Set margins to 0 or minimal
- Choose "Actual size" or 100% scale
- Ensure paper size matches your label stock

## License

MIT License - see LICENSE file for details