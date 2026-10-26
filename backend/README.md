# Pantry Vault

A responsive, image-free Pantry Vault website for tracking ingredients, matching recipes, monitoring expiry dates, finding grocery stores, and using an optional AI kitchen assistant.

## Run locally
1. Install Node.js.
2. Open this project folder in VS Code.
3. Run `npm.cmd install` and then `npm.cmd start`.
4. Open http://localhost:3000.

## Optional AI features
The ingredient photo scanner and AI Kitchen Assistant need an OpenAI API key configured as a server environment variable named `OPENAI_API_KEY`. Do not put the key in `public/app.js`, HTML, or a public repository. The AI feature shows a setup message if the key is missing.

On Windows PowerShell, you can set the key for the current terminal session before starting the app with `$env:OPENAI_API_KEY="your-key-here"` and then `npm.cmd start`. Never share the key in screenshots or chat.

## Subscription plans
The Free, Pantry Plus, and AI Chef cards are front-end plan previews only. Payment/checkout is not connected; choosing a plan does not charge money. Connect a payment provider such as Razorpay or Stripe before launching paid subscriptions.

## Recipes and images
Recipe cards and missing-ingredient suggestions do not load food photos. They use clean layouts and small emoji accents instead. Recipe instructions show quantities and steps when available.
