## Dev

### Stripe

Run stripe webhook on localhost:
`docker run --rm -it stripe/stripe-cli listen --forward-to host.docker.internal:3000/api/webhooks --api-key sk_test_51IwAYzHoTTWOrF6jnCBbPvT1RJCv8dSekFK4XQOcMiXjoiGhDaSzezfgbATfKv7gokSgmnuh7uqgDSBnGYigIZMb006B9l6Ul6`
