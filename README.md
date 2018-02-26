# Bitcoin-Dataset

Project description:
Read data into Jupyter notebook, use pandas to import data into a data frame
preprocess data: explore data, address missing data, categorical data, if there is any, and data scaling. Justify the type of scaling used in this project.
train your dataset using all the linear regression models you've learned so far. If your model has a scaling parameter(s) use Grid Search to find the best scaling parameter. Use plots and graphs to help you get a better glimpse of the results.
Then use cross validation to find average training and testing score.
Your submission should have at least the following regression models: KNN repressor, linear regression, Ridge, Lasso, polynomial regression, SVM both simple and with kernels.
Finally find the best repressor for this dataset and train your model on the entire dataset using the best parameters and predict the market price for the test_set.
submit IPython notebook. Use markdown to provide an inline report for this project.


Date : Date of observation
btc_market_price : Average USD market price across major bitcoin exchanges.
btc_total_bitcoins : The total number of bitcoins that have already been mined.
btc_market_cap : The total USD value of bitcoin supply in circulation.
btc_trade_volume : The total USD value of trading volume on major bitcoin exchanges.
btc_blocks_size : The total size of all block headers and transactions.
btc_avg_block_size : The average block size in MB.
btc_n_orphaned_blocks : The total number of blocks mined but ultimately not attached to the main Bitcoin blockchain.
btc_n_transactions_per_block : The average number of transactions per block.
btc_median_confirmation_time : The median time for a transaction to be accepted into a mined block.
btc_hash_rate : The estimated number of tera hashes per second the Bitcoin network is performing.
btc_difficulty : A relative measure of how difficult it is to find a new block.
btc_miners_revenue : Total value of coinbase block rewards and transaction fees paid to miners.
btc_transaction_fees : The total value of all transaction fees paid to miners.
btc_cost_per_transaction_percent : miners revenue as percentage of the transaction volume.
btc_cost_per_transaction : miners revenue divided by the number of transactions.
btc_n_unique_addresses : The total number of unique addresses used on the Bitcoin blockchain.
btc_n_transactions : The number of daily confirmed Bitcoin transactions.
btc_n_transactions_total : Total number of transactions.
btc_n_transactions_excluding_popular : The total number of Bitcoin transactions, excluding the 100 most popular addresses.
btc_n_transactions_excluding_chains_longer_than_100 : The total number of Bitcoin transactions per day excluding long transaction chains.
btc_output_volume : The total value of all transaction outputs per day.
btc_estimated_transaction_volume : The total estimated value of transactions on the Bitcoin blockchain.
