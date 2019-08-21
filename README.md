# bitcoin_blockchain_explorer
'''
Take this program and you can use it in your command line to retrieve details about Bitcoin addresses and hashes.
(i.e. Balances, pending balances, sending/receiving addresses of a hash, etc) 
You will need the Requests library to use this program.

There are 2 classes within the Python program (Address, and Hash). Here are two examples of how you can use the classes:

from bitcoin_explorer import Address, Hash

a = Address('PUT SOME BITCOIN ADDRESS HERE')

a.address (to check address)
a.balance (to check balance)
a.pending (to check pending balance or unconfirmed coins)

tx = Hash('PUT SOME BITCOIN HASH HERE')

tx.tx (to check the Hash you are looking at)
tx.block (to check the block number of the hash)
tx.confirmations (to check how many confirmations the block has)
...
tx.last_tx (to check the previous hashes the current hash is associated with)
tx.input (to check the sending bitcoin addresses of the hash)
tx.output (to check the receiving bitcoin addresses of the hash)

I hope this helps! =]
'''
