# playwright-test

//delete from package.json
//"type": "commonjs" 


//----data from package.json---
{
"name": "aqa-playwright-test",
"version": "1.0.0",
"description": "",
"main": "index.js",
"scripts": {
"test": "npx playwright test",
"test:api": "npx playwright test -c playwright.config.api.js",
"test:smoke": "npx playwright test -c playwright.config.smoke.js",
"test:regression": "npx playwright test -c playwright.config.regression.js",
"test:ui": "npx playwright test --ui",
"report": "npx playwright show-report"
},
"keywords": [],
"author": "",
"license": "ISC",
"type": "module",
"devDependencies": {
"@playwright/test": "^1.39.0",
"@types/node": "^20.8.10"
},
"dependencies": {
"axios": "^1.6.2",
"axios-cookiejar-support": "^4.0.7",
"dotenv": "^16.3.1",
"got": "^14.0.0",
"tough-cookie": "^4.1.3"
}
}