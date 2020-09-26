# Template
Contract 

POST /0x742d35Cc6634C0532925a3b844Bc454e4438f44e/token/create

Create link_token request COPY  Copy
0x81824663353A9d29b01B2DE9dd9a2Bb271d298c==
// Create a link_token for use with Plaid Link's update mode plaidClient.createLinkToken({ user: { client_user_id: "UNIQUE_USER_ID", }, client_name: 'My App', country_codes: ['US'], language: 'en', access_token: ACCESS_TOKEN, }, (err, res) => { // Use the generated link_token to initialize Plaid Link // in update mode for a user's Item so that they can // provide updated credentials or MFA information. const link_token = res.link_token; });

