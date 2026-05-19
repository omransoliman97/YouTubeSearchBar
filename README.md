
# YouTube Search Bar

A single-file YouTube search page with a customizable retro/minimal/hand-drawn UI.

The project is built as a lightweight front-end experience around one HTML file: [index.html](https://github.com/omransoliman97/YouTubeSearchBar/blob/main/index.html). It lets you search YouTube quickly, keep recent searches locally on your device, and personalize the look and feel without any backend.

## Features

- Search YouTube directly from a centered landing page
- Three visual styles: `Retro`, `Minimal`, and `Hand-drawn`
- Light and dark mode
- Custom accent color
- Per-theme design color with reset to the original theme color
- Adjustable font size in `px`
- Optional background image upload
- Adjustable background blur
- Adjustable front overlay strength from `0` to `100`
- Recent search history with hide/show and clear-all controls
- Follow links in the settings panel
- Everything stored locally with `localStorage`

## How It Works

When you type a query and press Enter or click the search button, the page redirects to YouTube search results using:

`https://www.youtube.com/results?search_query=YOUR_QUERY`

The interface also stores recent searches so they can be reused from the history section under the search bar.

## Project Structure

- `index.html`  
  The full app: layout, styling, settings panel, persistence, and YouTube redirect logic

## Run Locally

Because this is a static front-end project, you can use it in either of these ways:

1. Open `index.html` directly in your browser.
2. Or serve the folder with any simple static server if you prefer.

No install step, build step, or backend is required.

## Settings

The settings panel lets you customize the page in real time:

- `Your Name`: shows a personalized greeting
- `Design Color`: changes the main color palette for the active theme
- `Reset`: restores that theme’s original default color
- `Accent Color`: changes highlight color and buttons
- `Font Size`: adjusts the UI text sizing in pixels
- `Background Image`: uploads a local image for the page background
- `Background Blur`: controls image blur amount
- `Front Overlay`: controls the overlay opacity above the background image

## Privacy

This project does not use a server or store user data remotely.

- Search history is saved in your browser only
- Theme and settings preferences are saved in your browser only
- Uploaded background images are stored locally in browser storage only

If you clear site storage or browser data, those saved preferences will be removed.

## Customization Notes

The project is designed to be easy to edit:

- Change the follow links inside the settings panel in `index.html`
- Tweak theme defaults in the script section
- Update typography, spacing, or colors directly in the CSS

## Why This Project

This project is meant to be:

- fast
- simple
- visually fun
- fully self-hosted
- easy to customize

## License / Usage

Use it, modify it, and adapt it for your own workflow or personal start page.


Made with claude and Codex ( from openAI ).