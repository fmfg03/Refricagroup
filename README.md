# Refricagroup
 38.5K .edu and 104 .gov backlinks 
# README.md
# Refricagroup Research Portal

Academic research and educational resources portal preserving valuable institutional connections.

## Structure
```
refricagroup/
├── public/          # Static assets and pages
├── _headers         # Cloudflare security headers
└── _redirects       # URL preservation rules
```

## Local Development
1. Clone the repository
2. Install dependencies (if any are added in future)
3. Run local server

## Deployment
- Automatically deploys to GitHub Pages
- Cloudflare handles DNS and CDN
- URL preservation rules maintain academic links

## URL Structure
- /academics/* - Academic resources and research
- /research/* - Research publications
- /gov/* - Government resources
- /resources/* - General educational materials

---

# .gitignore
# Dependencies
node_modules/

# Build files
dist/
build/

# Environment variables
.env
.env.local
.env.*.local

# IDE/Editor files
.vscode/
.idea/
*.swp
*.swo

# OS files
.DS_Store
Thumbs.db

# Log files
*.log
npm-debug.log*
yarn-debug.log*
yarn-error.log*

---

# LICENSE
MIT License

Copyright (c) 2025 Refricagroup

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
