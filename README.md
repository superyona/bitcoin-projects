# bitcoin-projects

toy projects and ideas regarding blockchain
some of them to be used at hackatons

1. rapid settlments:
a sketch of lighting network based 'stable coin', it is built on the premises that an oracle is not necessarily needed to establish price data, instead if you create very rapid settlements, both sides of the contract (long/stablecoin) will have be able to keep the contract running as long as they agree on the price. for simplicity I will describe the concept on a two way channel

a channel is created between both parties
both sides watch agreed price output [i.e. bitcoin average]
the contract is agreed upon [one side takes stable dollar, the other is long on bitcoin]
each second the two sides settle according to price output
each side is free to 'stop' the settlement at any point
now there is a small problem that the cost of forfeit to one side can create petty thefts of bitcoin by abusing connections, this can be solved by a penalty for forfeit here comes in the lighting protocol, the use of 3 party nodes to agree on who forfeited the contract can be a 'good enough' solution.
