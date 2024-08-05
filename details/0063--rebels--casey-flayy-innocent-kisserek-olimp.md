### Roster Details<br />
Team Name: Rebels<br />
Roster: casey, Flayy, innocent, kisserek, olimp<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  996.2<br />
<br />
Final Rank Value (996.2) = Starting Rank Value (989.5) + Head To Head Adjustments (6.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.413[<sup>1</sup>](#table2)
- Bounty Collected: 0.392[<sup>2</sup>](#table1)
- Opponent Network: 0.224[<sup>2</sup>](#table1)
- LAN Wins: 0.120[<sup>2</sup>](#table1)

The average of these factors is 0.287<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 989.5
- 400 + ( ( 0.287 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 989.5


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
|           45 |        1 | 2024-08-05 | SINNERS           | L   | 1.000      | -            | -                | -                | -         |   -16.67 | casey, Flayy, innocent, kisserek, olimp |
|           44 |      225 | 2024-07-30 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.55 | casey, Flayy, innocent, kisserek, olimp |
|           43 |      423 | 2024-07-24 | SAW               | W   | 1.000      | 0.500        | 0.105 (0.052)    | 0.530 (0.265)    | 0 (0.000) |    22.57 | casey, Flayy, innocent, kisserek, olimp |
|           42 |      434 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -18.24 | casey, Flayy, innocent, kisserek, olimp |
|           41 |      477 | 2024-07-23 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.616 (0.228)    | 0 (0.000) |    11.88 | casey, Flayy, innocent, kisserek, olimp |
|           40 |      494 | 2024-07-22 | Insilio           | W   | 1.000      | 0.371        | -                | 0.553 (0.205)    | 0 (0.000) |    13.84 | casey, Flayy, innocent, kisserek, olimp |
|           39 |      595 | 2024-07-19 | B8                | L   | 1.000      | -            | -                | -                | -         |    -9.13 | casey, Flayy, innocent, kisserek, olimp |
|           38 |      660 | 2024-07-18 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.92 | casey, Flayy, innocent, kisserek, olimp |
|           37 |      721 | 2024-07-17 | 9INE              | W   | 1.000      | 0.500        | 0.022 (0.011)    | 0.533 (0.266)    | 0 (0.000) |    12.02 | casey, Flayy, innocent, kisserek, olimp |
|           36 |      809 | 2024-07-15 | brazylijski luz   | L   | 1.000      | -            | -                | -                | -         |   -22.91 | casey, Flayy, innocent, kisserek, olimp |
|           35 |      816 | 2024-07-15 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -7.87 | casey, Flayy, innocent, kisserek, olimp |
|           34 |      856 | 2024-07-12 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.616 (0.228)    | 0 (0.000) |    12.99 | casey, Flayy, innocent, kisserek, olimp |
|           33 |      893 | 2024-07-10 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.09 | casey, Flayy, innocent, kisserek, olimp |
|           32 |      905 | 2024-07-09 | 500               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.07 | casey, Flayy, innocent, kisserek, olimp |
|           31 |      941 | 2024-07-08 | Verdant           | W   | 1.000      | -            | -                | -                | -         |     9.82 | casey, Flayy, innocent, kisserek, olimp |
|           30 |     1130 | 2024-06-13 | Sampi             | L   | 0.846      | -            | -                | -                | -         |   -17.84 | casey, Flayy, innocent, kisserek, olimp |
|           29 |     1153 | 2024-06-12 | PERA              | L   | 0.840      | -            | -                | -                | -         |   -15.03 | casey, Flayy, innocent, kisserek, olimp |
|           28 |     1197 | 2024-06-10 | Permitta          | W   | 0.827      | 0.379        | -                | 0.863 (0.270)    | -         |    10.19 | casey, Flayy, innocent, kisserek, olimp |
|           27 |     1235 | 2024-06-09 | Rhyno             | L   | 0.820      | -            | -                | -                | -         |   -14.28 | casey, Flayy, kisserek, olimp, SZPERO   |
|           26 |     1360 | 2024-06-07 | BLEED             | W   | 0.807      | 0.500        | 0.126 (0.051)    | 0.511 (0.206)    | -         |    22.43 | casey, Flayy, innocent, kisserek, olimp |
|           25 |     1485 | 2024-06-05 | 9INE              | W   | 0.794      | 0.500        | -                | 0.533 (0.211)    | -         |     9.29 | casey, Flayy, innocent, kisserek, olimp |
|           24 |     1675 | 2024-05-30 | PERA              | W   | 0.754      | 0.379        | 0.048 (0.014)    | -                | -         |    10.49 | casey, Flayy, innocent, kisserek, olimp |
|           23 |     1712 | 2024-05-29 | UNiTY             | L   | 0.745      | -            | -                | -                | -         |   -13.86 | casey, Flayy, innocent, kisserek, olimp |
|           22 |     1799 | 2024-05-25 | kONO              | W   | 0.718      | -            | -                | -                | -         |     6.69 | casey, Flayy, innocent, kisserek, olimp |
|           21 |     1913 | 2024-05-21 | UNiTY             | L   | 0.691      | -            | -                | -                | -         |   -12.19 | casey, Flayy, innocent, kisserek, olimp |
|           20 |     1936 | 2024-05-20 | The Prodigies     | W   | 0.687      | -            | -                | -                | -         |     1.45 | casey, Flayy, innocent, kisserek, olimp |
|           19 |     2004 | 2024-05-18 | B8                | L   | 0.671      | -            | -                | -                | -         |    -7.09 | casey, Flayy, innocent, kisserek, olimp |
|           18 |     2032 | 2024-05-17 | Gaimin Gladiators | W   | 0.665      | -            | -                | -                | -         |    10.55 | casey, Flayy, innocent, kisserek, olimp |
|           17 |     2527 | 2024-04-27 | Aurora            | L   | 0.537      | -            | -                | -                | -         |    -0.53 | casey, Flayy, innocent, kisserek, olimp |
|           16 |     2577 | 2024-04-26 | MIBR              | W   | 0.524      | 0.500        | 0.208 (0.055)    | 0.649 (0.170)    | 1 (0.524) |    15.31 | casey, Flayy, innocent, kisserek, olimp |
|           15 |     2579 | 2024-04-25 | Rooster           | W   | 0.523      | -            | -                | -                | 1 (0.523) |     4.23 | casey, Flayy, innocent, kisserek, olimp |
|           14 |     2727 | 2024-04-19 | brazylijski luz   | L   | 0.480      | -            | -                | -                | -         |   -10.94 | casey, Flayy, innocent, kisserek, olimp |
|           13 |     2912 | 2024-04-13 | Monte             | L   | 0.439      | -            | -                | -                | -         |    -7.05 | casey, Flayy, innocent, kisserek, olimp |
|           12 |     3046 | 2024-04-09 | B8                | W   | 0.414      | 0.500        | 0.165 (0.034)    | 0.935 (0.193)    | -         |     7.76 | casey, Flayy, innocent, kisserek, olimp |
|           11 |     3188 | 2024-04-04 | ALTERNATE aTTaX   | W   | 0.379      | -            | -                | -                | -         |     5.61 | casey, Flayy, innocent, kisserek, olimp |
|           10 |     3238 | 2024-04-03 | SINNERS           | L   | 0.371      | -            | -                | -                | -         |    -3.44 | casey, Flayy, innocent, kisserek, olimp |
|            9 |     3319 | 2024-03-28 | ex-Sprout         | W   | 0.333      | -            | -                | -                | -         |     0.65 | casey, Flayy, innocent, kisserek, olimp |
|            8 |     3353 | 2024-03-27 | B8                | L   | 0.327      | -            | -                | -                | -         |    -3.76 | casey, Flayy, innocent, kisserek, olimp |
|            7 |     3362 | 2024-03-27 | Sashi             | W   | 0.327      | -            | -                | -                | -         |     7.22 | casey, Flayy, innocent, kisserek, olimp |
|            6 |     3392 | 2024-03-25 | Aurora            | L   | 0.313      | -            | -                | -                | -         |    -0.21 | casey, Flayy, innocent, kisserek, olimp |
|            5 |     3591 | 2024-03-14 | brazylijski luz   | L   | 0.241      | -            | -                | -                | -         |    -5.67 | casey, Flayy, kisserek, olimp, SZPERO   |
|            4 |     3859 | 2024-03-04 | BLEED             | L   | 0.174      | -            | -                | -                | -         |    -3.01 | casey, Flayy, kisserek, olimp, sNx      |
|            3 |     3893 | 2024-03-03 | Sangal            | W   | 0.166      | 0.500        | 0.219 (0.018)    | -                | -         |     3.73 | casey, Flayy, kisserek, olimp, sNx      |
|            2 |     3908 | 2024-03-02 | Aurora            | L   | 0.160      | -            | -                | -                | -         |    -0.11 | casey, Flayy, kisserek, olimp, sNx      |
|            1 |     3941 | 2024-02-29 | Sangal            | W   | 0.146      | 0.500        | 0.219 (0.016)    | -                | -         |     3.32 | casey, Flayy, kisserek, olimp, sNx      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,286.74)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-13 |      0.847 | $1,089.00      | $922.52         |
| 2024-06-09 |      0.820 | $2,000.00      | $1,639.31       |
| 2024-05-18 |      0.673 | $2,000.00      | $1,346.67       |
| 2024-04-28 |      0.538 | $10,000.00     | $5,378.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
