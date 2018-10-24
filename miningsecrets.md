



## Crypto mining thoughts ##

-----------------------------------------------------------------------------

## Here I will begin to formulate and structure a plan to mine cryptos so to 
## achieve a quick ROI with a reinvestment strategy

-----------------------------------------------------------------------------

## A few essential questions to ask first
# what coin to mine?
# what is best hardware for that algo?
# where can I find the best deal for that hardware
# what additional parts do I need to complete the rigs?

-----------------------------------------------------------------------------

## Three big choices
# ASIC
# GPU
# I/O

##ASIC 
#expensive
#restricted to one algo
#FAST
#limited supply / Must preorder
#high power consumption

##GPU
#Inexpensive
#Choose many differnt algo
#slower than ASIC
#Easy to buy in bulk
#less efficient than ASIC   Hash/W

##I/O
#experimental
#Inexpensive
#efficient Hash/W
#limited coin options
#easy to find
#can do in conjunction with GPU or ASIC mining

-----------------------------------------------------------------------------

## Formulation

# #1# I think it makes most sense to build GPU focused rigs with onboard NVMe 
# to maximize each rigs potential. Mining GPU & I/O algo on single rig. 
# Only need to make sure RAM & CPU are not bottleneck. So I will show an 
# build which maximizes Hash/w so acheive quick ROI and quicker reinvestment
# time. Mining is a speculative game and many things can go wrong. This plan
# must account for chances of suddenly losing everything... So to keep things
# kind of simple I will calculate yelid/kwh, in order to keep the volatility
# of the crypto market controlled for in the calculation. The GPUs will be 
# mounted on risers off of the MOBO so the rig will fit up to 4 GPU per MOBO

# #2# Another option would be to make use of new small formfactor boards such 
# as raspberry Pi or ODROID. This would allow us to keep the machines very
# compact and inexpensive. This would require some finesse and know-how to 
# set up. The CPU and bus speeds would bottleneck the hashrate from these 
# solutions but in turn, you could buy a much cheaper and slower SSD
-----------------------------------------------------------------------------

## Tradtitional rig build [formulation 1]
## -cost: ~$2.5k per 4 GPU rig
## -hash: GPU is algo dependent I/O is 200kh/s

## MOBO has 2+ m.2 + lots of pcie 
## GPU gtx 1070
## CPU more cores the better
## RAM 32gb preferalbly 
## PSU fully modular 
## SSD 2x1TB m.2 NVMe [fastest random read IOPS available{WD-SAMSUNG}]
## CASE flat formfactor or mid tower

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## ODROID rig build [formulation 2] Snowblossom Mining Only
## -cost: <$300 per unit
## -hash: 80-100kh/s

## BOARD ODROID-H2 [releasing early nov18]
## RAM 2x8gb SO-DIMM DDR3
## SSD 1x1TB m.2 NVMe [fastest random read IOPS available{WD-SAMSUNG}]
## CASE no case
## PSU ODROID psu

-----------------------------------------------------------------------------
