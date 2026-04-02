Week 4 AI Simulator - Vercel Ready
Suggested simulator name: Leadership Conversations Lab
This package is ready for GitHub and Vercel.
Files
`index.html`
`api/chat.js`
`vercel.json`
`package.json`
Deploy
Upload all files to the root of your GitHub repo
Import the repo into Vercel
Add environment variable:
`ANTHROPIC_API_KEY`
Redeploy
Notes
Frontend calls `/api/chat`
Anthropic key stays server-side
Speaker playback uses browser speech synthesis
Microphone stays on until clicked again to stop
