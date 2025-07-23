# Running A10i Landing Page Locally

## Quick Start

Start a local HTTP server in the project root:

```bash
# Using Python (recommended)
python3 -m http.server 8000

# Using Node.js
npx serve .

# Using PHP  
php -S localhost:8000
```

Open <http://localhost:8000> in your browser.

## Why HTTP Server?

The HTML file uses external CDNs (Tailwind CSS) that require proper HTTP protocol to load correctly.
