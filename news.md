Package: MarketMatching

Version: 1.1.4

MarketMacthing version 1.1.4
============================

-   Changed MAPE calculation to not re-scale the residuals.
-   Minor bug fixes.
-   test\_fake\_lift() does not refit underlying BSTS model at every
    step on the curve.
-   Added the parameter suggest\_market\_splits to best\_matchess() to
    provide a market split recommendations.
-   You can now pass just 2 markets (no longer a requirement of 3+
    markets).
-   Added more details on the numbers behind the distance calculations.

MarketMacthing version 1.1.3
============================

Added the function test\_fake\_lift() to calculate pseudo power curves.
Fixed minor bugs.

MarketMacthing version 1.1.2
============================

Fixed documentation errors.

Added additional input checks.

Refactored the code to handle errors with markets\_to\_be\_matched not
being in data. Check happens prior to the execution of the calc
distances loop now.

Modified calculate\_distances and best\_matches to allow for parallel
processing to be executed when the specifies markets for
markets\_to\_be\_matched.

MarketMacthing version 1.1.1
============================

Submit to CRAN.
