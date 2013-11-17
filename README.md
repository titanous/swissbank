swissbank
=========

Allow users to share 1-way bank account details

Bank account details are sensitive information. Users should be able to advertise a token that allows other users to easily transfer funds to their account without exposing sensitive information.

1. Users submit their bank account details and credentials to a service with a tokenization api. 

2. After verifying test transfers from the service users can publish the token. 

3. Other users can submit a request to the payments API with the published token as the destination.

4. Multiple tokenization services can enter into peering arrangements removing the need to process each transfer (ledger-based transfers)
