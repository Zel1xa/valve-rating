### Roster Details<br />
Team Name: Rebels<br />
Roster: casey, Flayy, innocent, kisserek, olimp<br />
Global Rank: [64](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  998.2<br />
<br />
Final Rank Value (998.2) = Starting Rank Value (991.1) + Head To Head Adjustments (7.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.413[<sup>1</sup>](#table2)
- Bounty Collected: 0.391[<sup>2</sup>](#table1)
- Opponent Network: 0.225[<sup>2</sup>](#table1)
- LAN Wins: 0.120[<sup>2</sup>](#table1)

The average of these factors is 0.287<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 991.1
- 400 + ( ( 0.287 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 991.1


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
|           45 |       21 | 2024-08-05 | SINNERS           | L   | 1.000      | -            | -                | -                | -         |   -16.66 | casey, Flayy, innocent, kisserek, olimp |
|           44 |      245 | 2024-07-30 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.63 | casey, Flayy, innocent, kisserek, olimp |
|           43 |      443 | 2024-07-24 | SAW               | W   | 1.000      | 0.500        | 0.104 (0.052)    | 0.516 (0.258)    | 0 (0.000) |    22.45 | casey, Flayy, innocent, kisserek, olimp |
|           42 |      454 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -18.20 | casey, Flayy, innocent, kisserek, olimp |
|           41 |      497 | 2024-07-23 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.641 (0.237)    | 0 (0.000) |    11.90 | casey, Flayy, innocent, kisserek, olimp |
|           40 |      514 | 2024-07-22 | Insilio           | W   | 1.000      | 0.371        | -                | 0.539 (0.200)    | 0 (0.000) |    13.92 | casey, Flayy, innocent, kisserek, olimp |
|           39 |      615 | 2024-07-19 | B8                | L   | 1.000      | -            | -                | -                | -         |    -9.14 | casey, Flayy, innocent, kisserek, olimp |
|           38 |      680 | 2024-07-18 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.00 | casey, Flayy, innocent, kisserek, olimp |
|           37 |      741 | 2024-07-17 | 9INE              | W   | 1.000      | 0.500        | -                | 0.523 (0.262)    | 0 (0.000) |    12.05 | casey, Flayy, innocent, kisserek, olimp |
|           36 |      829 | 2024-07-15 | brazylijski luz   | L   | 1.000      | -            | -                | -                | -         |   -22.98 | casey, Flayy, innocent, kisserek, olimp |
|           35 |      836 | 2024-07-15 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -7.80 | casey, Flayy, innocent, kisserek, olimp |
|           34 |      876 | 2024-07-12 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.641 (0.237)    | 0 (0.000) |    13.03 | casey, Flayy, innocent, kisserek, olimp |
|           33 |      913 | 2024-07-10 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.08 | casey, Flayy, innocent, kisserek, olimp |
|           32 |      925 | 2024-07-09 | 500               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.05 | casey, Flayy, innocent, kisserek, olimp |
|           31 |      961 | 2024-07-08 | Verdant           | W   | 1.000      | -            | -                | -                | -         |     9.89 | casey, Flayy, innocent, kisserek, olimp |
|           30 |     1150 | 2024-06-13 | Sampi             | L   | 0.840      | -            | -                | -                | -         |   -17.59 | casey, Flayy, innocent, kisserek, olimp |
|           29 |     1173 | 2024-06-12 | PERA              | L   | 0.834      | -            | -                | -                | -         |   -14.98 | casey, Flayy, innocent, kisserek, olimp |
|           28 |     1217 | 2024-06-10 | Permitta          | W   | 0.821      | 0.379        | 0.039 (0.012)    | 0.919 (0.286)    | -         |    10.58 | casey, Flayy, innocent, kisserek, olimp |
|           27 |     1255 | 2024-06-09 | Rhyno             | L   | 0.814      | -            | -                | -                | -         |   -14.07 | casey, Flayy, kisserek, olimp, SZPERO   |
|           26 |     1380 | 2024-06-07 | BLEED             | W   | 0.801      | 0.500        | 0.126 (0.050)    | 0.538 (0.216)    | -         |    22.27 | casey, Flayy, innocent, kisserek, olimp |
|           25 |     1505 | 2024-06-05 | 9INE              | W   | 0.787      | 0.500        | -                | 0.523 (0.206)    | -         |     9.27 | casey, Flayy, innocent, kisserek, olimp |
|           24 |     1695 | 2024-05-30 | PERA              | W   | 0.748      | 0.379        | 0.047 (0.013)    | -                | -         |    10.36 | casey, Flayy, innocent, kisserek, olimp |
|           23 |     1732 | 2024-05-29 | UNiTY             | L   | 0.739      | -            | -                | -                | -         |   -13.80 | casey, Flayy, innocent, kisserek, olimp |
|           22 |     1819 | 2024-05-25 | kONO              | W   | 0.711      | -            | -                | -                | -         |     6.71 | casey, Flayy, innocent, kisserek, olimp |
|           21 |     1933 | 2024-05-21 | UNiTY             | L   | 0.685      | -            | -                | -                | -         |   -12.14 | casey, Flayy, innocent, kisserek, olimp |
|           20 |     1956 | 2024-05-20 | The Prodigies     | W   | 0.681      | -            | -                | -                | -         |     1.43 | casey, Flayy, innocent, kisserek, olimp |
|           19 |     2024 | 2024-05-18 | B8                | L   | 0.665      | -            | -                | -                | -         |    -7.01 | casey, Flayy, innocent, kisserek, olimp |
|           18 |     2052 | 2024-05-17 | Gaimin Gladiators | W   | 0.659      | -            | -                | -                | -         |    10.37 | casey, Flayy, innocent, kisserek, olimp |
|           17 |     2547 | 2024-04-27 | Aurora            | L   | 0.531      | -            | -                | -                | -         |    -0.52 | casey, Flayy, innocent, kisserek, olimp |
|           16 |     2597 | 2024-04-26 | MIBR              | W   | 0.518      | 0.500        | 0.208 (0.054)    | 0.633 (0.164)    | 1 (0.518) |    15.10 | casey, Flayy, innocent, kisserek, olimp |
|           15 |     2599 | 2024-04-25 | Rooster           | W   | 0.517      | -            | -                | -                | 1 (0.517) |     4.15 | casey, Flayy, innocent, kisserek, olimp |
|           14 |     2747 | 2024-04-19 | brazylijski luz   | L   | 0.474      | -            | -                | -                | -         |   -10.84 | casey, Flayy, innocent, kisserek, olimp |
|           13 |     2932 | 2024-04-13 | Monte             | L   | 0.433      | -            | -                | -                | -         |    -6.99 | casey, Flayy, innocent, kisserek, olimp |
|           12 |     3066 | 2024-04-09 | B8                | W   | 0.407      | 0.500        | 0.170 (0.035)    | 0.912 (0.186)    | -         |     7.67 | casey, Flayy, innocent, kisserek, olimp |
|           11 |     3208 | 2024-04-04 | ALTERNATE aTTaX   | W   | 0.373      | -            | -                | -                | -         |     5.53 | casey, Flayy, innocent, kisserek, olimp |
|           10 |     3258 | 2024-04-03 | SINNERS           | L   | 0.365      | -            | -                | -                | -         |    -3.40 | casey, Flayy, innocent, kisserek, olimp |
|            9 |     3339 | 2024-03-28 | ex-Sprout         | W   | 0.327      | -            | -                | -                | -         |     0.61 | casey, Flayy, innocent, kisserek, olimp |
|            8 |     3373 | 2024-03-27 | B8                | L   | 0.321      | -            | -                | -                | -         |    -3.69 | casey, Flayy, innocent, kisserek, olimp |
|            7 |     3382 | 2024-03-27 | Sashi             | W   | 0.321      | -            | -                | -                | -         |     7.08 | casey, Flayy, innocent, kisserek, olimp |
|            6 |     3412 | 2024-03-25 | Aurora            | L   | 0.307      | -            | -                | -                | -         |    -0.20 | casey, Flayy, innocent, kisserek, olimp |
|            5 |     3611 | 2024-03-14 | brazylijski luz   | L   | 0.234      | -            | -                | -                | -         |    -5.54 | casey, Flayy, kisserek, olimp, SZPERO   |
|            4 |     3879 | 2024-03-04 | BLEED             | L   | 0.168      | -            | -                | -                | -         |    -2.91 | casey, Flayy, kisserek, olimp, sNx      |
|            3 |     3913 | 2024-03-03 | Sangal            | W   | 0.160      | 0.500        | 0.219 (0.018)    | -                | -         |     3.63 | casey, Flayy, kisserek, olimp, sNx      |
|            2 |     3928 | 2024-03-02 | Aurora            | L   | 0.154      | -            | -                | -                | -         |    -0.10 | casey, Flayy, kisserek, olimp, sNx      |
|            1 |     3961 | 2024-02-29 | Sangal            | W   | 0.140      | 0.500        | 0.219 (0.015)    | -                | -         |     3.21 | casey, Flayy, kisserek, olimp, sNx      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,194.53)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-13 |      0.841 | $1,089.00      | $915.87         |
| 2024-06-09 |      0.814 | $2,000.00      | $1,627.08       |
| 2024-05-18 |      0.667 | $2,000.00      | $1,334.44       |
| 2024-04-28 |      0.532 | $10,000.00     | $5,317.13       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
