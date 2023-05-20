# NFTValuation-Task

This exercise will use the sales and token metadata from the CryptoPunks NFT collection. The goal of the
exercise is to provide a valuation for each token in terms of the Ethereum (ETH) cryptocurrency. Your
evaluation metric should consider the error between the last sale the token was sold and the valuation that
you provide. However, you will encounter tokens that have not yet been sold or that have been sold
significantly less than similar tokens. An example would be for tokens with an “Alien” Type. The last sale
was at 8000 ETH, whereas the second to last was at 4200 ETH. In these cases, consider what factors have
contributed to those sales and whether these have changed now (and how that influences models producing
the valuation). In other words, your models should be able to adapt to the current market state and not
entirely dependent on last sales recorded.
