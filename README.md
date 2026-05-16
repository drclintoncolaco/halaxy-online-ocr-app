# Halaxy Online Sticker OCR App

This is a Vercel-ready web app for extracting patient details from a sticker/photo into Halaxy-ready JSON.

## Easiest local test

1. Install Node.js.
2. Unzip this folder.
3. Open the folder in VS Code.
4. Copy `.env.example` to `.env.local`.
5. Add your OpenAI API key:

```env
OPENAI_API_KEY=your_key_here
```

6. Run:

```bash
npm install
npm run dev
```

7. Open:

```text
http://localhost:3000/sticker-upload
```

## Deploy to Vercel

1. Upload this folder to GitHub.
2. Import the GitHub repo into Vercel.
3. Add environment variable:

```text
OPENAI_API_KEY = your_key_here
```

4. Deploy.
5. Open `/sticker-upload` on your Vercel app.

## Privacy and safety

- Do not store patient stickers unless you have a compliant storage and retention policy.
- Always check the extracted fields before copying to Halaxy.
- Do not auto-save Halaxy patient records.
