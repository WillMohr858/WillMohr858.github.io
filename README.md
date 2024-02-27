# apokercalculator.com web application
Calculates the percentage that each player (up to 10 players) wins in a texas hold'em poker game. Includes pre flop, post flop, post turn and post river percentages.



### When is it useful?

  This calculator requires that the user knows the cards of their opponent(s) so it is only useful for after a hand. If you have ever had some bad luck on the hold'em table and wondered "what are the odds?..." this calculator is for you!

### How does it work?


   The calculator simulates every possible hand that could happen with the cards that are left, determining which starting hand won or tied for each. The wins for each hand are summed and then turned into a percentage in the end. For a 1v1 pre flop "heads up" scenario, there are 1,712,304 possible hands. This means the efficiency of the main javascript program was one of the most important functional requirements. The initial prototype was written in C to provide the best possible runtime, which was then converted to javascript. The entire GUI was created using HTML and CSS and was designed for mobile and desktop.
