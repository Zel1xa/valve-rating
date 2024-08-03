### Roster Details<br />
Team Name: Rebels<br />
Roster: casey, Flayy, innocent, kisserek, olimp<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [41]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1016.2<br />
<br />
Final Rank Value (1016.2) = Starting Rank Value (996.2) + Head To Head Adjustments (20.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.414[<sup>1</sup>](#table2)
- Bounty Collected: 0.394[<sup>2</sup>](#table1)
- Opponent Network: 0.236[<sup>2</sup>](#table1)
- LAN Wins: 0.122[<sup>2</sup>](#table1)

The average of these factors is 0.291<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 996.2
- 400 + ( ( 0.291 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 996.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |      142 | 2024-07-30 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -20.15 | casey, Flayy, innocent, kisserek, olimp |
|           41 |      340 | 2024-07-24 | SAW               | W   | 1.000      | 0.500        | 0.106 (0.053)    | 0.560 (0.280)    | 0 (0.000) |    22.20 | casey, Flayy, innocent, kisserek, olimp |
|           40 |      352 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -18.48 | casey, Flayy, innocent, kisserek, olimp |
|           39 |      394 | 2024-07-23 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.646 (0.239)    | 0 (0.000) |    11.58 | casey, Flayy, innocent, kisserek, olimp |
|           38 |      411 | 2024-07-22 | Insilio           | W   | 1.000      | 0.371        | -                | 0.581 (0.215)    | 0 (0.000) |    13.29 | casey, Flayy, innocent, kisserek, olimp |
|           37 |      512 | 2024-07-19 | B8                | L   | 1.000      | -            | -                | -                | -         |    -9.48 | casey, Flayy, innocent, kisserek, olimp |
|           36 |      577 | 2024-07-18 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.63 | casey, Flayy, innocent, kisserek, olimp |
|           35 |      636 | 2024-07-17 | 9INE              | W   | 1.000      | 0.500        | 0.022 (0.011)    | 0.553 (0.276)    | 0 (0.000) |    11.75 | casey, Flayy, innocent, kisserek, olimp |
|           34 |      723 | 2024-07-15 | brazylijski luz   | L   | 1.000      | -            | -                | -                | -         |   -23.13 | casey, Flayy, innocent, kisserek, olimp |
|           33 |      767 | 2024-07-12 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.646 (0.239)    | 0 (0.000) |    12.94 | casey, Flayy, innocent, kisserek, olimp |
|           32 |      802 | 2024-07-10 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.10 | casey, Flayy, innocent, kisserek, olimp |
|           31 |      814 | 2024-07-09 | 500               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.07 | casey, Flayy, innocent, kisserek, olimp |
|           30 |      850 | 2024-07-08 | Verdant           | W   | 1.000      | -            | -                | -                | -         |    10.10 | casey, Flayy, innocent, kisserek, olimp |
|           29 |     1019 | 2024-06-13 | Sampi             | L   | 0.860      | -            | -                | -                | -         |   -18.30 | casey, Flayy, innocent, kisserek, olimp |
|           28 |     1041 | 2024-06-12 | PERA              | L   | 0.854      | -            | -                | -                | -         |   -15.29 | casey, Flayy, innocent, kisserek, olimp |
|           27 |     1082 | 2024-06-10 | Permitta          | W   | 0.840      | 0.379        | -                | 0.887 (0.282)    | -         |     9.94 | casey, Flayy, innocent, kisserek, olimp |
|           26 |     1119 | 2024-06-09 | Rhyno             | L   | 0.834      | -            | -                | -                | -         |   -14.41 | casey, Flayy, kisserek, olimp, SZPERO   |
|           25 |     1239 | 2024-06-07 | BLEED             | W   | 0.820      | 0.500        | 0.126 (0.052)    | 0.534 (0.219)    | -         |    22.79 | casey, Flayy, innocent, kisserek, olimp |
|           24 |     1364 | 2024-06-05 | 9INE              | W   | 0.807      | 0.500        | -                | 0.553 (0.223)    | -         |     9.46 | casey, Flayy, innocent, kisserek, olimp |
|           23 |     1551 | 2024-05-30 | PERA              | W   | 0.767      | 0.379        | 0.048 (0.014)    | -                | -         |    10.63 | casey, Flayy, innocent, kisserek, olimp |
|           22 |     1588 | 2024-05-29 | UNiTY             | L   | 0.759      | -            | -                | -                | -         |   -14.20 | casey, Flayy, innocent, kisserek, olimp |
|           21 |     1674 | 2024-05-25 | kONO              | W   | 0.731      | -            | -                | -                | -         |     6.87 | casey, Flayy, innocent, kisserek, olimp |
|           20 |     1788 | 2024-05-21 | UNiTY             | L   | 0.704      | -            | -                | -                | -         |   -12.48 | casey, Flayy, innocent, kisserek, olimp |
|           19 |     1811 | 2024-05-20 | The Prodigies     | W   | 0.700      | -            | -                | -                | -         |     1.48 | casey, Flayy, innocent, kisserek, olimp |
|           18 |     1878 | 2024-05-18 | B8                | L   | 0.685      | -            | -                | -                | -         |    -7.27 | casey, Flayy, innocent, kisserek, olimp |
|           17 |     1906 | 2024-05-17 | Gaimin Gladiators | W   | 0.679      | -            | -                | -                | -         |    10.93 | casey, Flayy, innocent, kisserek, olimp |
|           16 |     2400 | 2024-04-27 | Aurora            | L   | 0.550      | -            | -                | -                | -         |    -0.55 | casey, Flayy, innocent, kisserek, olimp |
|           15 |     2449 | 2024-04-26 | MIBR              | W   | 0.537      | 0.500        | 0.210 (0.056)    | 0.682 (0.183)    | 1 (0.537) |    15.72 | casey, Flayy, innocent, kisserek, olimp |
|           14 |     2451 | 2024-04-25 | Rooster           | W   | 0.537      | -            | -                | -                | 1 (0.537) |     4.34 | casey, Flayy, innocent, kisserek, olimp |
|           13 |     2599 | 2024-04-19 | brazylijski luz   | L   | 0.494      | -            | -                | -                | -         |   -11.21 | casey, Flayy, innocent, kisserek, olimp |
|           12 |     2784 | 2024-04-13 | Monte             | L   | 0.453      | -            | -                | -                | -         |    -7.08 | casey, Flayy, innocent, kisserek, olimp |
|           11 |     2918 | 2024-04-09 | B8                | W   | 0.427      | 0.500        | 0.166 (0.035)    | 0.945 (0.202)    | -         |     8.07 | casey, Flayy, innocent, kisserek, olimp |
|           10 |     3060 | 2024-04-04 | ALTERNATE aTTaX   | W   | 0.393      | -            | -                | -                | -         |     5.86 | casey, Flayy, innocent, kisserek, olimp |
|            9 |     3110 | 2024-04-03 | SINNERS           | L   | 0.385      | -            | -                | -                | -         |    -4.40 | casey, Flayy, innocent, kisserek, olimp |
|            8 |     3191 | 2024-03-28 | ex-Sprout         | W   | 0.347      | -            | -                | -                | -         |     0.70 | casey, Flayy, innocent, kisserek, olimp |
|            7 |     3224 | 2024-03-27 | B8                | L   | 0.341      | -            | -                | -                | -         |    -3.87 | casey, Flayy, innocent, kisserek, olimp |
|            6 |     3261 | 2024-03-25 | Aurora            | L   | 0.327      | -            | -                | -                | -         |    -0.23 | casey, Flayy, innocent, kisserek, olimp |
|            5 |     3457 | 2024-03-14 | brazylijski luz   | L   | 0.254      | -            | -                | -                | -         |    -6.04 | casey, Flayy, kisserek, olimp, SZPERO   |
|            4 |     3723 | 2024-03-04 | BLEED             | L   | 0.187      | -            | -                | -                | -         |    -3.26 | casey, Flayy, kisserek, olimp, sNx      |
|            3 |     3756 | 2024-03-03 | Sangal            | W   | 0.180      | 0.500        | 0.219 (0.020)    | -                | -         |     3.95 | casey, Flayy, kisserek, olimp, sNx      |
|            2 |     3772 | 2024-03-02 | Aurora            | L   | 0.173      | -            | -                | -                | -         |    -0.12 | casey, Flayy, kisserek, olimp, sNx      |
|            1 |     3805 | 2024-02-29 | Sangal            | W   | 0.160      | 0.500        | 0.219 (0.017)    | -                | -         |     3.55 | casey, Flayy, kisserek, olimp, sNx      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,488.62)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-13 |      0.861 | $1,089.00      | $937.09         |
| 2024-06-09 |      0.833 | $2,000.00      | $1,666.06       |
| 2024-05-18 |      0.687 | $2,000.00      | $1,373.43       |
| 2024-04-28 |      0.551 | $10,000.00     | $5,512.04       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
