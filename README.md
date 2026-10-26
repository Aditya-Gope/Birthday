# Rupa's 21st Birthday Website 💖🎂

A static, mobile-friendly birthday surprise website for Rupa.

## Deploy to Vercel

This is a plain static HTML site. No build command or framework is required.

### From GitHub
1. Push this folder to a GitHub repository.
2. In Vercel, select **Add New → Project** and import the repository.
3. Leave the framework preset as **Other** (or no framework), with no build command. The output is the repository root.
4. Deploy. Vercel will provide a public HTTPS URL.

### Microphone note
The microphone feature requires HTTPS and browser microphone permission. Test the deployed page directly in Chrome and allow microphone access. Browsers or third-party embeds may block microphone access; a directly opened Vercel URL is the best way to test it.

## Files
- `index.html` — the complete website.
- `vercel.json` — response headers, including a same-origin microphone permissions policy.
