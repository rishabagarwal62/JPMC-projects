#Purpose

You will use perspective to generate a live graph that displays the data feed in a clear and visually appealing way for traders to monitor this trading strategy.

Recall that the purpose of this graph is to monitor and determine when a trading opportunity may arise as a result of the temporary weakening of a correlation between two stock prices. Given this graph, the trader should be able to quickly and easily notice when the ratio moves too far from the average historical correlation. In the first instance, we'll assume that threshold is +/-10% of the 12 month historical average ratio.

#Acceptance Criteria

This ticket is done when the numbers from the python script render properly in the live perspective graph. This means the ratio between the two stock prices is tracked and displayed. The upper and lower bounds must be shown on the graph too. And finally, alerts are shown whenever these bounds are crossed by the ratio (the guide below will also give more detail and visuals to help you understand these requirements better)
