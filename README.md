# cs2_arbbot

Before starting:
Main idea is to connect to multiple venues that buy/sell cs2 skins and find opportunities for easy money. 
Have to keep in mind the fees, trading timeouts and skin conditions etc to keep it realistic and not just a price compare simulator.
Venues provide api's so I'll make use of that, find/arrange the items I can extract from the api's and compare the prices, I will probably only look at higher value items ($50+), since including fees it probably is a lost cause to look at cheaper items and make profit of it.
There might even be a trading limit that Steam enforces? (Might have to confirm that), so making profit might be left for higher value items. (skin value's range from cents to thousands).

For now need to find api's, request their data and pull logic out of them. At first I'll do it in notebooks and when the logic is more complete I'll make scripts.