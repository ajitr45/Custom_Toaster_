# Custom Toaster JS 🔔

A simple configurable toast notification system using JavaScript & Tailwind CSS.

## Features
- Custom position (top-right, bottom-left)
- Light / Dark theme
- Auto remove
- Stack multiple toasts

## Usage

const toaster = createToaster({
  positionX: "right",
  positionY: "top",
  theme: "dark",
  duration: 3,
});

toaster("Download Done!");
