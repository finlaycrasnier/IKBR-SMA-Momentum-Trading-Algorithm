# IKBR-SMA-Momentum-Trading-Algorithm
A small SMA momentum trading algorithm I created following on from my contrarian algorithim. The strategy revolves around purchasing a chosen stock when it's SMA positively crosses it's LMA, or alternatively, shorting a stock when it's SMA falls beneath it's LMA. These figures can be entered manually, or optimised with a backtesting function. Alternatively, stock is shorted when SMA falls below LMA. Stock is bought/sold using IKBR. Further comments can be found in the notebook of the file. 

Whilst this algorithm was fun to program, I do not think it is effective. Even when the algorithm is optimised with SMA/LMA values, it severely underperforms long-only approaches when backtesting. I see this as more of a practice algorithm rather than a usable one. 

Either way, I had lots of fun creating the optimiser. I aim to adjust it for a future algorithm to create a balanced portfolio using alpha/beta backtesting. This will, hopefully, be more succesful. 
