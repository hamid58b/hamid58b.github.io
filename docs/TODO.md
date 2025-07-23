# A10i Landing Page TODO

## DNS & Domain Setup

### demo.a10i.io Configuration

Temporarily using ip address for demo.a10i.io: <http://18.224.39.187>

- **Buy domain**: a10i.io (if not owned)
- **Create CNAME**: `demo.a10i.io` → AWS JupyterHub IP/domain
- **SSL Certificate**: Let's Encrypt or AWS Certificate Manager
- **Alternative**: Use AWS ALB with custom domain

## Demo Request Forms

### Option 1: Google Forms (Recommended)

- Create form: Name, Email, Company, Use Case
- Response email: `info@a10i.io`
- Replace `mailto:` links with form URL

### Option 2: Typeform (Professional)

- Better UX, analytics
- Free tier available
- Custom branding

### Option 3: Simple Contact Form

- GitHub Pages + Formspree/Netlify Forms
- Static form submission

## GitHub Pages Deployment

- Set Pages source to your branch
- Custom domain: point GitHub Pages to `a10i.io`
- Enable HTTPS in GitHub settings
