1. Create XSUAA: `cf create-service xsuaa mysample-auth -c ./xs-security.json`
2. Locally bind XSUAA: `cf bind-local -path .env -service-names mysample-auth`
3. Run using approuter: `npm run dev-approuter`
4. Open locahost:5000 to test.