### Roster Details<br />
Team Name: Rebels<br />
Roster: casey, Flayy, innocent, kisserek, olimp<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  996.7<br />
<br />
Final Rank Value (996.7) = Starting Rank Value (990.0) + Head To Head Adjustments (6.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.413[<sup>1</sup>](#table2)
- Bounty Collected: 0.392[<sup>2</sup>](#table1)
- Opponent Network: 0.225[<sup>2</sup>](#table1)
- LAN Wins: 0.120[<sup>2</sup>](#table1)

The average of these factors is 0.288<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 990.0
- 400 + ( ( 0.288 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 990.0


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
|           45 |        2 | 2024-08-05 | SINNERS           | L   | 1.000      | -            | -                | -                | -         |   -16.68 | casey, Flayy, innocent, kisserek, olimp |
|           44 |      226 | 2024-07-30 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.57 | casey, Flayy, innocent, kisserek, olimp |
|           43 |      424 | 2024-07-24 | SAW               | W   | 1.000      | 0.500        | 0.104 (0.052)    | 0.530 (0.265)    | 0 (0.000) |    22.56 | casey, Flayy, innocent, kisserek, olimp |
|           42 |      435 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -18.25 | casey, Flayy, innocent, kisserek, olimp |
|           41 |      478 | 2024-07-23 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.616 (0.228)    | 0 (0.000) |    11.89 | casey, Flayy, innocent, kisserek, olimp |
|           40 |      495 | 2024-07-22 | Insilio           | W   | 1.000      | 0.371        | -                | 0.552 (0.205)    | 0 (0.000) |    13.87 | casey, Flayy, innocent, kisserek, olimp |
|           39 |      596 | 2024-07-19 | B8                | L   | 1.000      | -            | -                | -                | -         |    -9.14 | casey, Flayy, innocent, kisserek, olimp |
|           38 |      661 | 2024-07-18 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.91 | casey, Flayy, innocent, kisserek, olimp |
|           37 |      722 | 2024-07-17 | 9INE              | W   | 1.000      | 0.500        | 0.022 (0.011)    | 0.533 (0.266)    | 0 (0.000) |    12.01 | casey, Flayy, innocent, kisserek, olimp |
|           36 |      810 | 2024-07-15 | brazylijski luz   | L   | 1.000      | -            | -                | -                | -         |   -22.93 | casey, Flayy, innocent, kisserek, olimp |
|           35 |      817 | 2024-07-15 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -7.87 | casey, Flayy, innocent, kisserek, olimp |
|           34 |      857 | 2024-07-12 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.616 (0.228)    | 0 (0.000) |    13.02 | casey, Flayy, innocent, kisserek, olimp |
|           33 |      894 | 2024-07-10 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.09 | casey, Flayy, innocent, kisserek, olimp |
|           32 |      906 | 2024-07-09 | 500               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.06 | casey, Flayy, innocent, kisserek, olimp |
|           31 |      942 | 2024-07-08 | Verdant           | W   | 1.000      | -            | -                | -                | -         |     9.81 | casey, Flayy, innocent, kisserek, olimp |
|           30 |     1131 | 2024-06-13 | Sampi             | L   | 0.846      | -            | -                | -                | -         |   -17.82 | casey, Flayy, innocent, kisserek, olimp |
|           29 |     1154 | 2024-06-12 | PERA              | L   | 0.840      | -            | -                | -                | -         |   -15.04 | casey, Flayy, innocent, kisserek, olimp |
|           28 |     1198 | 2024-06-10 | Permitta          | W   | 0.827      | 0.379        | -                | 0.902 (0.282)    | -         |    10.34 | casey, Flayy, innocent, kisserek, olimp |
|           27 |     1236 | 2024-06-09 | Rhyno             | L   | 0.820      | -            | -                | -                | -         |   -14.28 | casey, Flayy, kisserek, olimp, SZPERO   |
|           26 |     1361 | 2024-06-07 | BLEED             | W   | 0.807      | 0.500        | 0.126 (0.051)    | 0.511 (0.206)    | -         |    22.41 | casey, Flayy, innocent, kisserek, olimp |
|           25 |     1486 | 2024-06-05 | 9INE              | W   | 0.793      | 0.500        | -                | 0.533 (0.211)    | -         |     9.27 | casey, Flayy, innocent, kisserek, olimp |
|           24 |     1676 | 2024-05-30 | PERA              | W   | 0.753      | 0.379        | 0.048 (0.014)    | -                | -         |    10.47 | casey, Flayy, innocent, kisserek, olimp |
|           23 |     1713 | 2024-05-29 | UNiTY             | L   | 0.745      | -            | -                | -                | -         |   -13.87 | casey, Flayy, innocent, kisserek, olimp |
|           22 |     1800 | 2024-05-25 | kONO              | W   | 0.717      | -            | -                | -                | -         |     6.68 | casey, Flayy, innocent, kisserek, olimp |
|           21 |     1914 | 2024-05-21 | UNiTY             | L   | 0.690      | -            | -                | -                | -         |   -12.20 | casey, Flayy, innocent, kisserek, olimp |
|           20 |     1937 | 2024-05-20 | The Prodigies     | W   | 0.686      | -            | -                | -                | -         |     1.44 | casey, Flayy, innocent, kisserek, olimp |
|           19 |     2005 | 2024-05-18 | B8                | L   | 0.671      | -            | -                | -                | -         |    -7.09 | casey, Flayy, innocent, kisserek, olimp |
|           18 |     2033 | 2024-05-17 | Gaimin Gladiators | W   | 0.665      | -            | -                | -                | -         |    10.54 | casey, Flayy, innocent, kisserek, olimp |
|           17 |     2528 | 2024-04-27 | Aurora            | L   | 0.537      | -            | -                | -                | -         |    -0.53 | casey, Flayy, innocent, kisserek, olimp |
|           16 |     2578 | 2024-04-26 | MIBR              | W   | 0.524      | 0.500        | 0.208 (0.055)    | 0.648 (0.170)    | 1 (0.524) |    15.29 | casey, Flayy, innocent, kisserek, olimp |
|           15 |     2580 | 2024-04-25 | Rooster           | W   | 0.523      | -            | -                | -                | 1 (0.523) |     4.22 | casey, Flayy, innocent, kisserek, olimp |
|           14 |     2728 | 2024-04-19 | brazylijski luz   | L   | 0.480      | -            | -                | -                | -         |   -10.95 | casey, Flayy, innocent, kisserek, olimp |
|           13 |     2913 | 2024-04-13 | Monte             | L   | 0.439      | -            | -                | -                | -         |    -7.05 | casey, Flayy, innocent, kisserek, olimp |
|           12 |     3047 | 2024-04-09 | B8                | W   | 0.413      | 0.500        | 0.165 (0.034)    | 0.935 (0.193)    | -         |     7.74 | casey, Flayy, innocent, kisserek, olimp |
|           11 |     3189 | 2024-04-04 | ALTERNATE aTTaX   | W   | 0.379      | -            | -                | -                | -         |     5.59 | casey, Flayy, innocent, kisserek, olimp |
|           10 |     3239 | 2024-04-03 | SINNERS           | L   | 0.371      | -            | -                | -                | -         |    -3.44 | casey, Flayy, innocent, kisserek, olimp |
|            9 |     3320 | 2024-03-28 | ex-Sprout         | W   | 0.333      | -            | -                | -                | -         |     0.65 | casey, Flayy, innocent, kisserek, olimp |
|            8 |     3354 | 2024-03-27 | B8                | L   | 0.327      | -            | -                | -                | -         |    -3.76 | casey, Flayy, innocent, kisserek, olimp |
|            7 |     3363 | 2024-03-27 | Sashi             | W   | 0.327      | -            | -                | -                | -         |     7.20 | casey, Flayy, innocent, kisserek, olimp |
|            6 |     3393 | 2024-03-25 | Aurora            | L   | 0.313      | -            | -                | -                | -         |    -0.21 | casey, Flayy, innocent, kisserek, olimp |
|            5 |     3592 | 2024-03-14 | brazylijski luz   | L   | 0.240      | -            | -                | -                | -         |    -5.67 | casey, Flayy, kisserek, olimp, SZPERO   |
|            4 |     3860 | 2024-03-04 | BLEED             | L   | 0.173      | -            | -                | -                | -         |    -3.00 | casey, Flayy, kisserek, olimp, sNx      |
|            3 |     3894 | 2024-03-03 | Sangal            | W   | 0.166      | 0.500        | 0.219 (0.018)    | -                | -         |     3.73 | casey, Flayy, kisserek, olimp, sNx      |
|            2 |     3909 | 2024-03-02 | Aurora            | L   | 0.159      | -            | -                | -                | -         |    -0.11 | casey, Flayy, kisserek, olimp, sNx      |
|            1 |     3942 | 2024-02-29 | Sangal            | W   | 0.146      | 0.500        | 0.219 (0.016)    | -                | -         |     3.31 | casey, Flayy, kisserek, olimp, sNx      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,280.45)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-13 |      0.847 | $1,089.00      | $922.07         |
| 2024-06-09 |      0.819 | $2,000.00      | $1,638.47       |
| 2024-05-18 |      0.673 | $2,000.00      | $1,345.83       |
| 2024-04-28 |      0.537 | $10,000.00     | $5,374.07       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
