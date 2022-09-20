# homeassistant-carnot
Integration to carnot.dk - energy price prediction

This integration fetches data from carnot.dk to setup an attribute sensor with prognosis data.
It is best used with apex chart.

I made this integration because I already get the spot pricing from the Nordpool integration and just need the prognosis.

There is another integration called Energi Data Service which integrates both Nordpool and Carnot, but I like pure sources and cannot see the reason for using an intermediary site.

All in all you are probably better off using the Energi Data Service integration which in turn replace both NordPool and this integration.
