I face issue to run the project and I make the following change
1. I update the package.json the section of script where I replace the the prevouise command of "watch" with new one to become like the following:
## old script of watch
` "watch": "npm run build && node_modules/http-server/bin/http-server dist -p 1234 " `
## new version of watch
` "watch": "npm run build && npx http-server dist -p 1234", `

## and run the following command
` npx http-server dist -p 1234 `
