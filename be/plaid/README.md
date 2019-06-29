### plaid-node quickstart

[Quickstart guide](https://plaid.com/docs/quickstart)

```bash
git clone https://github.com/plaid/quickstart.git
cd quickstart/node
npm install

# Start the Quickstart with your API keys from the Dashboard
# https://dashboard.plaid.com/account/keys
#
# PLAID_PRODUCTS is a comma-separated list of products to use when initializing
# Link. Note that this list must contain 'assets' in order for the app to be
# able to create and retrieve asset reports.
export PLAID_CLIENT_ID='CLIENT_ID' &&export PLAID_SECRET='SECRET' &&export PLAID_PUBLIC_KEY='PUBLIC_KEY' &&export PLAID_ENV='sandbox' &&export PLAID_PRODUCTS='transactions' &&export PLAID_COUNTRY_CODES='US,CA,GB,FR,ES' && node index.js
# Go to http://localhost:8000
```
