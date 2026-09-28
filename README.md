# Straiton payment-assessment landing

A responsive React/Vite/TypeScript challenge implementation for an illustrative Straiton payment-assessment journey: UAE businesses considering supplier payments to India.

The experience is deliberately local and non-transactional. It does not process payments, create accounts, collect documents, persist user data, call a backend or display live FX, fees, timing, regulatory claims or approval status.

## Run locally

```sh
cd app
npm ci
npm run dev
```

Build the production bundle:

```sh
cd app
npm run build
```

The built output is `app/dist`.

## Product decision

The landing follows a **Confidence before commitment** model:

1. State the UAE → India supplier-payment context.
2. Explain what an assessment clarifies before any commitment.
3. Make quote anatomy legible without simulating a live quote.
4. Offer one consistent assessment route with local validation and a clear demonstration-only confirmation.

## Documentation

- [Architecture](docs/ARCHITECTURE.md)
- [Design decisions](docs/DESIGN_DECISIONS.md)
- [Assumptions and limitations](docs/ASSUMPTIONS.md)
- [Vercel deployment](docs/DEPLOYMENT.md)

## License

No license has been granted. All rights reserved.
