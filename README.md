# JobLens — AI Job Search Assistant

AI-powered job search tool that finds matching opportunities and generates personalized outreach messages, tailored resumes, and cover letters.

## Features
- Job discovery based on keywords, location, and experience level
- Match scoring (0-100) with honest gap analysis
- Personalized LinkedIn outreach messages
- Tailored resume bullet rewrites
- Full cover letter generation

## Deploy to Netlify

1. Push this folder to a GitHub repo
2. Connect repo to Netlify
3. Add environment variable in Netlify dashboard:
   - `ANTHROPIC_API_KEY` = your Anthropic API key
4. Deploy

That's it. The app uses a serverless proxy function to keep your API key secure.

## Local development

```bash
npm install -g netlify-cli
netlify dev
```

Then open http://localhost:8888
