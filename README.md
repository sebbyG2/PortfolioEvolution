# PortfolioEvolution V.3

Now Login and download process from Degiro is fully automated, fill your data into the script.
This script uses Rselenium. I'm not responsible for whatever that library is doing.
Because your are sending sensitive information I recommend you to double check and understand what the script is doing before using it without supervision.

I'M NOT RESPONSIBLE FOR ANY WRONG DOING BY THIS SCRIPT WITH YOUR ACCOUNT.


# PortfolioEvolution V.2

* R Script that:
1) Imports your daily Portfolio export from DeGiro
2) Then saved it in Excel
3) Benchmark your performance against mayor EU Indexes and MultiAsset ETFs
4) Plot the evolution

* How is my Degiro's portfolio information loaded into this script?:

Login to your Degiro account as usual.

Go to Portfolio -> Export (Is on the upper right corner)

Select the date that you want to export.

Right click in CSV and select "Copy Link Address".

Run the R script. Important: you must be logged in or the script won't be able to download the CSV file


* To whom is benchmarked the Portfolio?: It is compared with (Yahoo format):

WLD.PA: MSCI World Index ETF in EUR (because the Portfolio is EUR, so I'm matching same currencies).

IUES.AS: SP500 ETF in EUR (because the Portfolio is EUR, so I'm matching same currencies).

STOXX50E: STOXX50 Index

XQUI.MI: The Xtrackers Portfolio index tracks a globally diversified portfolio consisting of equities and bond indices. The tactical allocation may change up to 8 times per year. Equity share: minimum 30%, maximum 70%. Bond share: minimum 30%, maximum 70%.

TOF.AS: The aim of the VanEck Vectors™ Multi-Asset Growth Allocation UCITS ETF is to follow the Multi-Asset Growth Allocation Index as closely as possible. This is a composite index made up in the ratios indicated here: - 60% Solactive Global Equity Index - 10% GPR Global 100 Index - 15% Markit iBoxx EUR Liquid Corporates Index - 15% Markit iBoxx EUR Liquid Sovereign Diversified 1-10 Index.

F703.DE: The ComStage Vermögensstrategie Offensiv index tracks a diversified ETF portfolio. The initial allocation is made up of the following asset classes: 80% of global equities spread across geographies and across sectors, 10% of bonds and 10% commodities. Annually, the index is rebalanced.\

* More info here: https://www.reddit.com/r/ETFs_Europe/comments/fgx5mx/a_portfolio_tracker_and_benchmark_for_degiro/

Screenshots:


![](Benchmark.jpg)\
Evolution and Benchmarking of your Portfolio

![](Portfolio_Evolution.jpg)\
Daily changes

![](plot.jpg)\
Plot

![](Cumul_Changes.jpeg)\
Cumulative Changes
