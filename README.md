# Estadio

A minimal web app prototype for building and simulating tournament brackets.  
The MVP focuses purely on front-end bracket logic for a 16-team tournament—no accounts, databases, or hosting dependencies.

## Features

- Interactive 16-team single-elimination bracket
- Ability to select winners and advance them through rounds
- Local-only operation (runs entirely in browser)
- Simple HTML, CSS (Tailwind via CDN), and vanilla JavaScript setup

## Setup Instructions

1. Clone this repository:
```bash
   git clone https://github.com/<your-username>/EsteBracket.git
   cd EsteBracket
```

2. Create an `index.html` file with the initial structure.

3. Add Tailwind CSS via CDN in the `<head>` tag:
```html
   <script src="https://cdn.tailwindcss.com"></script>
```

4. Include a `<script>` block or file for your bracket logic.

No build tools or dependencies are required.

## Usage

Open `index.html` in any browser. Use the interface to select winners for each round. All logic runs client-side and resets on page reload.

## License

This project is licensed under the MIT License — see the LICENSE file for details.