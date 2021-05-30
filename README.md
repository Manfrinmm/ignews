## Dev

### Stripe

Run stripe webhook on localhost:
`docker run --rm -it stripe/stripe-cli listen --forward-to host.docker.internal:3000/api/webhooks --api-key your_api_key`
