# 404 Society — live Shopify catalog

This version removes all demo/mock products. The storefront loads products only from Shopify through `/api/products`.

Cloudflare runtime variables/secrets required:
- SHOPIFY_SHOP = py072z-6w
- SHOPIFY_CLIENT_ID
- SHOPIFY_CLIENT_SECRET (secret)
- CASHFREE_CLIENT_ID
- CASHFREE_CLIENT_SECRET (secret)

Cloudflare binding required:
- DB -> 404-society-db

Deploy command: `npx wrangler deploy`
