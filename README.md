# READ

Please note the website sometimes take to long to respond due to ads, this could be solved by blacklisting a google ads but might need further investigation on which domain should be blacklisted for a better automation flow.

This project consists in 2 folders, one for HP and other for a sample subdomain which I choose Geographic Tools. This could then be replicated to the other subdomains following the structure.

- To test individually, add .only to the test.
  For intance: "it.only('Shares the location link', () => {"

- Footer is not consistent between the application, therefore footer test wont work on 
  '/User Login' page

- To install cypress: npm install cypress --save-dev

**Note:** If you run out of free trial, some tests wont work unless you have a paid subscription.
