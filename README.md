# Mobile Repair Service Report

This is a simple and efficient web-based application for tracking mobile repair services. It works entirely offline in the browser and helps maintain service records, calculate profits, and export data for accounting or backup.

## Features

- Add entries with:
  - Date
  - Description
  - Amount charged
  - Service Type (Combo, Battery Change, Battery Boost, or Other)
- Auto-calculates cost price and profit
- Custom cost entry for "Other" types
- Total summary at the bottom of the table
- Red “Add Entry” button for quick visual action
- Automatically exports data as `.json` every 24 hours
- "Last Exported" timestamp shown
- Import/export functionality for backup or transfer
- Mobile-friendly, fast, and offline-capable

## How to Use

1. Open the `index.html` file in your browser.
2. Add service entries using the form.
3. Click **Export** to download your data.
4. To restore data later, use the **Import** button.
5. Your data is stored locally in your browser (localStorage).

> Tip: Bookmark the page for daily use.

## Hosting

You can host this on:
- GitHub Pages
- Netlify
- Cloudflare Pages
- Or run directly from your local machine

## License

This project is licensed under the **MIT License**. See [LICENSE](./LICENSE) for details.

## Contributions

Pull requests and suggestions are welcome! If you find a bug or want a new feature, feel free to open an issue.
