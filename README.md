# Project_FidentiaX

* start date (sd) = 575
* Tier 2 from sd + 2 = 550
* Tier 2 from sd + 5 = 500
* end date = sd + 30.

## Public Sale (fallback function)

* min purchase 0.001 ether
* max purchase None
* pre-authorised

## Private Sale (placeTokens)

* by fx user
* tokens minted on demand before or while sale is active.
* uses `placeTokens()` function

## Authorisation

* by fx user or cs user (cs is by the web API)
* can approve or block

## Finishing the sale (owner) - passes control of token back to the owner

* call finishSale 

## Starting Trading

* call startTrading on the TOKEN



