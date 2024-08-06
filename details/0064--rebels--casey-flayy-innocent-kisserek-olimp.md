### Roster Details<br />
Team Name: Rebels<br />
Roster: casey, Flayy, innocent, kisserek, olimp<br />
Global Rank: [64](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  999.6<br />
<br />
Final Rank Value (999.6) = Starting Rank Value (992.3) + Head To Head Adjustments (7.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.413[<sup>1</sup>](#table2)
- Bounty Collected: 0.394[<sup>2</sup>](#table1)
- Opponent Network: 0.225[<sup>2</sup>](#table1)
- LAN Wins: 0.119[<sup>2</sup>](#table1)

The average of these factors is 0.288<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 992.3
- 400 + ( ( 0.288 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 992.3


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
|           45 |       26 | 2024-08-05 | SINNERS           | L   | 1.000      | -            | -                | -                | -         |   -16.62 | casey, Flayy, innocent, kisserek, olimp |
|           44 |      250 | 2024-07-30 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.59 | casey, Flayy, innocent, kisserek, olimp |
|           43 |      448 | 2024-07-24 | SAW               | W   | 1.000      | 0.500        | 0.104 (0.052)    | 0.516 (0.258)    | 0 (0.000) |    22.53 | casey, Flayy, innocent, kisserek, olimp |
|           42 |      459 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -18.24 | casey, Flayy, innocent, kisserek, olimp |
|           41 |      502 | 2024-07-23 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.641 (0.237)    | 0 (0.000) |    11.87 | casey, Flayy, innocent, kisserek, olimp |
|           40 |      519 | 2024-07-22 | Insilio           | W   | 1.000      | 0.371        | -                | 0.539 (0.200)    | 0 (0.000) |    13.89 | casey, Flayy, innocent, kisserek, olimp |
|           39 |      620 | 2024-07-19 | B8                | L   | 1.000      | -            | -                | -                | -         |    -9.11 | casey, Flayy, innocent, kisserek, olimp |
|           38 |      685 | 2024-07-18 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.97 | casey, Flayy, innocent, kisserek, olimp |
|           37 |      746 | 2024-07-17 | 9INE              | W   | 1.000      | 0.500        | -                | 0.523 (0.262)    | 0 (0.000) |    12.01 | casey, Flayy, innocent, kisserek, olimp |
|           36 |      834 | 2024-07-15 | brazylijski luz   | L   | 1.000      | -            | -                | -                | -         |   -23.02 | casey, Flayy, innocent, kisserek, olimp |
|           35 |      841 | 2024-07-15 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -7.46 | casey, Flayy, innocent, kisserek, olimp |
|           34 |      881 | 2024-07-12 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.641 (0.237)    | 0 (0.000) |    13.00 | casey, Flayy, innocent, kisserek, olimp |
|           33 |      918 | 2024-07-10 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.07 | casey, Flayy, innocent, kisserek, olimp |
|           32 |      930 | 2024-07-09 | 500               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.05 | casey, Flayy, innocent, kisserek, olimp |
|           31 |      966 | 2024-07-08 | Verdant           | W   | 1.000      | -            | -                | -                | -         |     9.96 | casey, Flayy, innocent, kisserek, olimp |
|           30 |     1155 | 2024-06-13 | Sampi             | L   | 0.840      | -            | -                | -                | -         |   -17.59 | casey, Flayy, innocent, kisserek, olimp |
|           29 |     1178 | 2024-06-12 | PERA              | L   | 0.834      | -            | -                | -                | -         |   -15.01 | casey, Flayy, innocent, kisserek, olimp |
|           28 |     1222 | 2024-06-10 | Permitta          | W   | 0.820      | 0.379        | 0.039 (0.012)    | 0.919 (0.286)    | -         |    10.57 | casey, Flayy, innocent, kisserek, olimp |
|           27 |     1260 | 2024-06-09 | Rhyno             | L   | 0.814      | -            | -                | -                | -         |   -14.07 | casey, Flayy, kisserek, olimp, SZPERO   |
|           26 |     1385 | 2024-06-07 | BLEED             | W   | 0.800      | 0.500        | 0.125 (0.050)    | 0.538 (0.215)    | -         |    22.26 | casey, Flayy, innocent, kisserek, olimp |
|           25 |     1510 | 2024-06-05 | 9INE              | W   | 0.787      | 0.500        | -                | 0.523 (0.206)    | -         |     9.22 | casey, Flayy, innocent, kisserek, olimp |
|           24 |     1700 | 2024-05-30 | PERA              | W   | 0.747      | 0.379        | 0.047 (0.013)    | -                | -         |    10.32 | casey, Flayy, innocent, kisserek, olimp |
|           23 |     1737 | 2024-05-29 | UNiTY             | L   | 0.739      | -            | -                | -                | -         |   -13.83 | casey, Flayy, innocent, kisserek, olimp |
|           22 |     1824 | 2024-05-25 | kONO              | W   | 0.711      | -            | -                | -                | -         |     6.67 | casey, Flayy, innocent, kisserek, olimp |
|           21 |     1938 | 2024-05-21 | UNiTY             | L   | 0.684      | -            | -                | -                | -         |   -12.18 | casey, Flayy, innocent, kisserek, olimp |
|           20 |     1961 | 2024-05-20 | The Prodigies     | W   | 0.680      | -            | -                | -                | -         |     1.42 | casey, Flayy, innocent, kisserek, olimp |
|           19 |     2029 | 2024-05-18 | B8                | L   | 0.665      | -            | -                | -                | -         |    -6.99 | casey, Flayy, innocent, kisserek, olimp |
|           18 |     2057 | 2024-05-17 | Gaimin Gladiators | W   | 0.659      | -            | -                | -                | -         |    10.34 | casey, Flayy, innocent, kisserek, olimp |
|           17 |     2552 | 2024-04-27 | Aurora            | L   | 0.531      | -            | -                | -                | -         |    -0.52 | casey, Flayy, innocent, kisserek, olimp |
|           16 |     2602 | 2024-04-26 | MIBR              | W   | 0.518      | 0.500        | 0.207 (0.054)    | 0.633 (0.164)    | 1 (0.518) |    15.08 | casey, Flayy, innocent, kisserek, olimp |
|           15 |     2604 | 2024-04-25 | Rooster           | W   | 0.517      | -            | -                | -                | 1 (0.517) |     4.12 | casey, Flayy, innocent, kisserek, olimp |
|           14 |     2752 | 2024-04-19 | brazylijski luz   | L   | 0.474      | -            | -                | -                | -         |   -10.86 | casey, Flayy, innocent, kisserek, olimp |
|           13 |     2937 | 2024-04-13 | Monte             | L   | 0.433      | -            | -                | -                | -         |    -6.97 | casey, Flayy, innocent, kisserek, olimp |
|           12 |     3071 | 2024-04-09 | B8                | W   | 0.407      | 0.500        | 0.170 (0.035)    | 0.912 (0.186)    | -         |     7.64 | casey, Flayy, innocent, kisserek, olimp |
|           11 |     3213 | 2024-04-04 | ALTERNATE aTTaX   | W   | 0.373      | -            | -                | -                | -         |     5.54 | casey, Flayy, innocent, kisserek, olimp |
|           10 |     3263 | 2024-04-03 | SINNERS           | L   | 0.365      | -            | -                | -                | -         |    -3.41 | casey, Flayy, innocent, kisserek, olimp |
|            9 |     3344 | 2024-03-28 | ex-Sprout         | W   | 0.327      | -            | -                | -                | -         |     0.61 | casey, Flayy, innocent, kisserek, olimp |
|            8 |     3378 | 2024-03-27 | B8                | L   | 0.321      | -            | -                | -                | -         |    -3.70 | casey, Flayy, innocent, kisserek, olimp |
|            7 |     3387 | 2024-03-27 | Sashi             | W   | 0.320      | -            | -                | -                | -         |     7.06 | casey, Flayy, innocent, kisserek, olimp |
|            6 |     3417 | 2024-03-25 | Aurora            | L   | 0.307      | -            | -                | -                | -         |    -0.21 | casey, Flayy, innocent, kisserek, olimp |
|            5 |     3616 | 2024-03-14 | brazylijski luz   | L   | 0.234      | -            | -                | -                | -         |    -5.55 | casey, Flayy, kisserek, olimp, SZPERO   |
|            4 |     3884 | 2024-03-04 | BLEED             | L   | 0.167      | -            | -                | -                | -         |    -2.90 | casey, Flayy, kisserek, olimp, sNx      |
|            3 |     3918 | 2024-03-03 | Sangal            | W   | 0.160      | 0.500        | 0.288 (0.023)    | -                | -         |     3.74 | casey, Flayy, kisserek, olimp, sNx      |
|            2 |     3933 | 2024-03-02 | Aurora            | L   | 0.153      | -            | -                | -                | -         |    -0.10 | casey, Flayy, kisserek, olimp, sNx      |
|            1 |     3966 | 2024-02-29 | Sangal            | W   | 0.140      | 0.500        | 0.288 (0.020)    | -                | -         |     3.30 | casey, Flayy, kisserek, olimp, sNx      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,188.24)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-13 |      0.841 | $1,089.00      | $915.42         |
| 2024-06-09 |      0.813 | $2,000.00      | $1,626.25       |
| 2024-05-18 |      0.667 | $2,000.00      | $1,333.61       |
| 2024-04-28 |      0.531 | $10,000.00     | $5,312.96       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
