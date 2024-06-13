# stripe-hono

## Running the project

Listen for Stripe webhooks:

```sh
stripe listen -e checkout.session.completed --forward-to http://localhost:3000/webhook
```

Copy `.env.example` -> `.env`, \
Enter Stripe API keys & other values.

Run the server:

```sh
npm install
npm run dev
```

Open: http://localhost:3000
