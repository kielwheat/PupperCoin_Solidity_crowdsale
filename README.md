# PupperCoin_wk21

PupperCoin is a ERC20 token that is going to leverage a Crowdsale contract from OpenZepplin Solidity to help raise funds for a stated goal, enable refunds once that goal is met, and have a time limit on the crowdsale fundraising.  

There are 2 solidity files, Crowdsale and PupperCoin, that are deployed in order to open this fundraiser to the public.  There are screenshots that show how the coin and crowdsale were deployed successfully.

Issues:
I could not get an address to successfully send ether to the token_address, token_sale_address or even directly to the PupperCoin itself that were created once PupperCoinSaleDeployer and PupperCoin were successfully deployed.  Because of this I could not test it on myCrypto and also push it through to test in Kovan.