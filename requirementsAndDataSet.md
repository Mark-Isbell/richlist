
Data set notes
# Note: numbers straight from the wallets, grouped by the device they open the xApp on, from the database. And put it in a percentile.
# Note Elaboration: 
## The stats are processed once a few days
## Individual Wallet balance
## Cross-wallet balance by device
## Percentile for (this) wallet or (all) wallets on this device
## Rich List amounts by percentile for comparison:
### Top .1 % 
### Top 1 % 
### Top 5 % 
### Top 10 % 
### Top 25 % 
### Top 50 % 

Requirements notes
# Requirement: playful design 
# Requirement Elaboration: 
## click-able GUI with large icons 
## easy to understand rankings
## Button for 'This Wallet Only' or 'All My Wallets' 
## make it easy for them to get more XAH or XRP 


# AI Prompts for initial prototype
can you create a 'plain vanilla' HTML and Javascript front end for a single page application called 'Rich List'?

The user will want to see where they rank among other wallet holders in a crypto network.  

For example, if a user owns 1,000 coins, and only 10 out of 100 people have wallet balances equal to, or above, that level, then they would be considered in the "top 10 percent" of holders.  

The single page application should display this ranking, and also show how many coins it takes to be in each listed percentile.  

For example, it should show how many coins it takes to be in the following categories: Top 50% of holders, top 25% of holdrs, top 10% of holders, top 5% of holders, top 1% of holders, and top .1% of holders.  

Just use spoofed data for now, for the initial front-end prototype.  For example, you can assume that the network is the "Xahau" network, and that it takes 50,000 coins to be in the 'top 1%' of holders.  And also assume that the current user viewing the single page app has 51,000 coins.  You can use various other coin amounts for the other categories.  

There should also be a button for 'buy more' that is at the bottom.  







