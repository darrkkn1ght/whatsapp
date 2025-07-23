# OtakuFest Volunteer WhatsApp Bulk Outreach Tool

## Overview
This web-based tool helps event organizers efficiently manage and communicate with volunteers for OtakuFest via WhatsApp. It provides features for bulk messaging, filtering volunteers, exporting data, and customizing outreach messages.

## Features
- **Bulk WhatsApp Messaging:** Open chats for all or filtered volunteers with personalized messages.
- **Message Template:** Easily customize the outreach message using placeholders (e.g., `{name}`, `{roles}`, `{hours}`).
- **Volunteer Filtering:** Filter volunteers by availability (April 26, Pre-Event, Both) and hour commitments.
- **Copy Numbers:** Copy all volunteer phone numbers to clipboard for quick use.
- **Export CSV:** Download volunteer data as a CSV file for external use.
- **Modern UI:** Responsive and visually appealing interface for easy management.

## How to Use
1. **Open `index.html` in your browser.**
2. **Customize the message template** as needed. Placeholders will be replaced with each volunteer's details.
3. **Filter volunteers** using the dropdowns to target specific groups.
4. **Use bulk actions** to open WhatsApp chats, copy numbers, or export data.
5. **Edit volunteer data** directly in the JavaScript array in `index.html` if needed.

## Message Template Placeholders
- `{name}`: First name of the volunteer
- `{fullname}`: Full name
- `{roles}`: Assigned roles
- `{hours}`: Hour commitment
- `{age}`: Age

## Requirements
- Modern web browser (Chrome, Edge, Firefox, etc.)
- No server or backend required

## Customization
- To add or edit volunteers, modify the `volunteers` array in `index.html`.
- You can change the UI styles in the `<style>` section of `index.html`.

## License
This project is provided for personal and event use. Feel free to modify and share as needed.
