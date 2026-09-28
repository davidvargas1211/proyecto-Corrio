# Vercel deployment

1. Import this repository into Vercel.
2. Set **Root Directory** to `app`.
3. Use `npm run build` as the build command.
4. Set the output directory to `dist` if Vercel does not detect it.
5. Verify the preview as a signed-out visitor before sharing it with a reviewer.

No environment variables are required. A successful deployment does not turn the prototype into a payment service: the form remains local-only by design.
