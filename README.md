# Sticker Generator App

A Next.js application for generating and managing stickers with features like:
- Add stickers with custom text
- Delete individual stickers
- Delete all stickers
- Print grid layout
- Download as PNG
- Data persistence using localStorage
- Modern UI with Tailwind CSS

## Features
- Modern, responsive UI with Tailwind CSS
- Back button navigation
- Print and download functionality
- Local storage for data persistence
- Google Fonts integration
- Customizable sticker layout

## Tech Stack
- Next.js
- TypeScript
- Tailwind CSS
- HTML5 Canvas (for PNG export)
- Local Storage API

## Getting Started

1. Clone the repository
```bash
git clone [repository-url]
```

2. Install dependencies
```bash
npm install
```

3. Run the development server
```bash
npm run dev
```

4. Open [http://localhost:8000](http://localhost:8000) with your browser to see the result.

## Usage
1. Navigate to the sticker generator page
2. Enter text for your sticker(s)
3. Add single or multiple stickers (comma-separated)
4. Use the control buttons to:
   - Delete individual stickers
   - Clear all stickers
   - Print the grid
   - Download as PNG

## Project Archive
To create a zip archive of the project (excluding node_modules and .next directories):

```bash
npm run zip
```

This will create a `project.zip` file in the root directory containing all project files and directories. The archive excludes:
- node_modules directory
- .next directory (build output)

The zip file can be used for:
- Project backup
- Sharing code
- Deployment packages

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
