# base3jj
Tracking ETH Movement Without Token Transfers
eth_only = [tx for tx in block.transactions if tx.input == "0x"]
print("ETH-only txs:", len(eth_only))
