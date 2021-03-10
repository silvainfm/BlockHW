# BlockHW

** make sure to cd in the directory where the info and files are on

Launching the 1st mining node: ./geth --datadir node1 --mine --minerthreads 1

Telling the 2nd node where to find the 2nd one: ./geth --datadir node2 --port 30304 --rpc --bootnodes "enode://<replace with node1 enode address>"

If you need more info I can send you links to detailed instructions
