# Template
Contract 
POST /accounts/balance/get/
0xa910f92acdaf488fa6ef02174fb86208ad7722ba/token/create

Create link_token request COPY  Copy
0xa910f92acdaf488fa6ef02174fb86208ad7722ba==
// Create a link_token for use with Plaid Link's update mode plaidClient.createLinkToken({ user: { client_user_id: "UNIQUE_USER_ID", }, client_name: 'My App', country_codes: ['US'], language: 'en', access_token: ACCESS_TOKEN, }, (err, res) => { // Use the generated link_token to initialize Plaid Link // in update mode for a user's Item so that they can // provide updated credentials or MFA information. const link_token = res.link_token; });


// Create a link_token for use with Plaid Link's update mode plaidClient.createLinkToken({ user: { client_user_id: "Tombo ", }, client_name: 'JohnTambag, country_codes: ['US'], language: 'en', access_token: ACCESS_TOKEN, }, (err, res) => { // Use the generated link_token to initialize Plaid Link // in update mode for a user's Item so that they can // provide updated credentials or MFA information. const link_token = res.link_token; });
