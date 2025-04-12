# bitcoin-operated (bitcoinop.org)

## Build instructions

Initialize nodejs environment
```
winget install Schniz.fnm
fnm install 22
Set-ExecutionPolicy Bypass -scope currentuser
fnm env --use-on-cd --shell powershell | Out-String | Invoke-Expression
```

Initialize project (first time only)
`npx wrangler init`

Deploy to cloudflare
`npx wrangler deploy`

Launch local server
`npm run start`

## Utilities used
https://favicon.io/favicon-converter/
https://www.adobe.com/express/feature/image/resize
https://tinypng.com/
https://github.com/Blockstream/esplora/blob/master/API.md
https://docs.coingecko.com/v3.0.1/reference/simple-price
