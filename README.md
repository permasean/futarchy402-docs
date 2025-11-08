# Futarchy402 Documentation

Documentation for Futarchy402 - AI-native futarchy governance platform on Solana with gasless voting.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview the documentation locally:

```bash
npm i -g mint
```

Run the following command at the root of the documentation:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Structure

```
├── docs.json                    # Navigation configuration
├── index.mdx                    # Homepage
└── concepts/
    ├── dynamic-pricing.mdx      # Pricing mechanics
    └── x402-payment.mdx         # Payment protocol
```

## Publishing Changes

Changes pushed to the main branch are automatically deployed to production via Mintlify's GitHub app.

## Resources

- [Futarchy402 GitHub](https://github.com/futarchy402)
- [x402 Protocol](https://x402.org)
- [Mintlify Documentation](https://mintlify.com/docs)
