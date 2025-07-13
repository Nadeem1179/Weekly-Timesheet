# Weekly Timesheet

This project is a simple timesheet submission form built with plain HTML, CSS and JavaScript. It collects worker details and hours worked, then sends the data via EmailJS.

## Getting Started

1. Clone this repository or download the source files.
2. Open `index.html` in your web browser. You can double-click the file or drag it into an open browser window.

## Customizing Email Settings

The form uses EmailJS for email delivery. To use your own EmailJS account:

1. Open `index.html` in a text editor.
2. Replace the public key in `emailjs.init` around line 456.
3. Update the service ID and template ID in the `emailjs.send` call around lines 552–553.

These values should correspond to the keys in your EmailJS dashboard.
