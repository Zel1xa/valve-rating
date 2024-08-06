### Roster Details<br />
Team Name: Rebels<br />
Roster: casey, Flayy, innocent, kisserek, olimp<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  997.0<br />
<br />
Final Rank Value (997.0) = Starting Rank Value (990.8) + Head To Head Adjustments (6.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.413[<sup>1</sup>](#table2)
- Bounty Collected: 0.391[<sup>2</sup>](#table1)
- Opponent Network: 0.227[<sup>2</sup>](#table1)
- LAN Wins: 0.120[<sup>2</sup>](#table1)

The average of these factors is 0.288<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 990.8
- 400 + ( ( 0.288 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 990.8


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
|           45 |        8 | 2024-08-05 | SINNERS           | L   | 1.000      | -            | -                | -                | -         |   -16.65 | casey, Flayy, innocent, kisserek, olimp |
|           44 |      232 | 2024-07-30 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.59 | casey, Flayy, innocent, kisserek, olimp |
|           43 |      430 | 2024-07-24 | SAW               | W   | 1.000      | 0.500        | 0.104 (0.052)    | 0.528 (0.264)    | 0 (0.000) |    22.51 | casey, Flayy, innocent, kisserek, olimp |
|           42 |      441 | 2024-07-24 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -18.24 | casey, Flayy, innocent, kisserek, olimp |
|           41 |      484 | 2024-07-23 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.616 (0.228)    | 0 (0.000) |    11.89 | casey, Flayy, innocent, kisserek, olimp |
|           40 |      501 | 2024-07-22 | Insilio           | W   | 1.000      | 0.371        | -                | 0.552 (0.204)    | 0 (0.000) |    13.88 | casey, Flayy, innocent, kisserek, olimp |
|           39 |      602 | 2024-07-19 | B8                | L   | 1.000      | -            | -                | -                | -         |    -9.15 | casey, Flayy, innocent, kisserek, olimp |
|           38 |      667 | 2024-07-18 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.90 | casey, Flayy, innocent, kisserek, olimp |
|           37 |      728 | 2024-07-17 | 9INE              | W   | 1.000      | 0.500        | 0.022 (0.011)    | 0.534 (0.267)    | 0 (0.000) |    12.00 | casey, Flayy, innocent, kisserek, olimp |
|           36 |      816 | 2024-07-15 | brazylijski luz   | L   | 1.000      | -            | -                | -                | -         |   -22.95 | casey, Flayy, innocent, kisserek, olimp |
|           35 |      823 | 2024-07-15 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -7.86 | casey, Flayy, innocent, kisserek, olimp |
|           34 |      863 | 2024-07-12 | Enterprise        | W   | 1.000      | 0.371        | 0.039 (0.015)    | 0.616 (0.228)    | 0 (0.000) |    13.01 | casey, Flayy, innocent, kisserek, olimp |
|           33 |      900 | 2024-07-10 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.09 | casey, Flayy, innocent, kisserek, olimp |
|           32 |      912 | 2024-07-09 | 500               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.06 | casey, Flayy, innocent, kisserek, olimp |
|           31 |      948 | 2024-07-08 | Verdant           | W   | 1.000      | -            | -                | -                | -         |     9.82 | casey, Flayy, innocent, kisserek, olimp |
|           30 |     1137 | 2024-06-13 | Sampi             | L   | 0.842      | -            | -                | -                | -         |   -17.73 | casey, Flayy, innocent, kisserek, olimp |
|           29 |     1160 | 2024-06-12 | PERA              | L   | 0.836      | -            | -                | -                | -         |   -14.98 | casey, Flayy, innocent, kisserek, olimp |
|           28 |     1204 | 2024-06-10 | Permitta          | W   | 0.822      | 0.379        | -                | 0.940 (0.293)    | -         |    10.30 | casey, Flayy, innocent, kisserek, olimp |
|           27 |     1242 | 2024-06-09 | Rhyno             | L   | 0.816      | -            | -                | -                | -         |   -14.23 | casey, Flayy, kisserek, olimp, SZPERO   |
|           26 |     1367 | 2024-06-07 | BLEED             | W   | 0.802      | 0.500        | 0.126 (0.050)    | 0.550 (0.221)    | -         |    22.29 | casey, Flayy, innocent, kisserek, olimp |
|           25 |     1492 | 2024-06-05 | 9INE              | W   | 0.789      | 0.500        | -                | 0.534 (0.211)    | -         |     9.21 | casey, Flayy, innocent, kisserek, olimp |
|           24 |     1682 | 2024-05-30 | PERA              | W   | 0.749      | 0.379        | 0.048 (0.013)    | -                | -         |    10.39 | casey, Flayy, innocent, kisserek, olimp |
|           23 |     1719 | 2024-05-29 | UNiTY             | L   | 0.740      | -            | -                | -                | -         |   -13.82 | casey, Flayy, innocent, kisserek, olimp |
|           22 |     1806 | 2024-05-25 | kONO              | W   | 0.713      | -            | -                | -                | -         |     6.71 | casey, Flayy, innocent, kisserek, olimp |
|           21 |     1920 | 2024-05-21 | UNiTY             | L   | 0.686      | -            | -                | -                | -         |   -12.16 | casey, Flayy, innocent, kisserek, olimp |
|           20 |     1943 | 2024-05-20 | The Prodigies     | W   | 0.682      | -            | -                | -                | -         |     1.43 | casey, Flayy, innocent, kisserek, olimp |
|           19 |     2011 | 2024-05-18 | B8                | L   | 0.667      | -            | -                | -                | -         |    -7.05 | casey, Flayy, innocent, kisserek, olimp |
|           18 |     2039 | 2024-05-17 | Gaimin Gladiators | W   | 0.661      | -            | -                | -                | -         |    10.41 | casey, Flayy, innocent, kisserek, olimp |
|           17 |     2534 | 2024-04-27 | Aurora            | L   | 0.532      | -            | -                | -                | -         |    -0.52 | casey, Flayy, innocent, kisserek, olimp |
|           16 |     2584 | 2024-04-26 | MIBR              | W   | 0.519      | 0.500        | 0.208 (0.054)    | 0.647 (0.168)    | 1 (0.519) |    15.15 | casey, Flayy, innocent, kisserek, olimp |
|           15 |     2586 | 2024-04-25 | Rooster           | W   | 0.518      | -            | -                | -                | 1 (0.518) |     4.16 | casey, Flayy, innocent, kisserek, olimp |
|           14 |     2734 | 2024-04-19 | brazylijski luz   | L   | 0.476      | -            | -                | -                | -         |   -10.87 | casey, Flayy, innocent, kisserek, olimp |
|           13 |     2919 | 2024-04-13 | Monte             | L   | 0.435      | -            | -                | -                | -         |    -7.00 | casey, Flayy, innocent, kisserek, olimp |
|           12 |     3053 | 2024-04-09 | B8                | W   | 0.409      | 0.500        | 0.164 (0.034)    | 0.933 (0.191)    | -         |     7.67 | casey, Flayy, innocent, kisserek, olimp |
|           11 |     3195 | 2024-04-04 | ALTERNATE aTTaX   | W   | 0.375      | -            | -                | -                | -         |     5.53 | casey, Flayy, innocent, kisserek, olimp |
|           10 |     3245 | 2024-04-03 | SINNERS           | L   | 0.367      | -            | -                | -                | -         |    -3.42 | casey, Flayy, innocent, kisserek, olimp |
|            9 |     3326 | 2024-03-28 | ex-Sprout         | W   | 0.329      | -            | -                | -                | -         |     0.62 | casey, Flayy, innocent, kisserek, olimp |
|            8 |     3360 | 2024-03-27 | B8                | L   | 0.323      | -            | -                | -                | -         |    -3.72 | casey, Flayy, innocent, kisserek, olimp |
|            7 |     3369 | 2024-03-27 | Sashi             | W   | 0.322      | -            | -                | -                | -         |     7.10 | casey, Flayy, innocent, kisserek, olimp |
|            6 |     3399 | 2024-03-25 | Aurora            | L   | 0.309      | -            | -                | -                | -         |    -0.21 | casey, Flayy, innocent, kisserek, olimp |
|            5 |     3598 | 2024-03-14 | brazylijski luz   | L   | 0.236      | -            | -                | -                | -         |    -5.58 | casey, Flayy, kisserek, olimp, SZPERO   |
|            4 |     3866 | 2024-03-04 | BLEED             | L   | 0.169      | -            | -                | -                | -         |    -2.93 | casey, Flayy, kisserek, olimp, sNx      |
|            3 |     3900 | 2024-03-03 | Sangal            | W   | 0.162      | 0.500        | 0.219 (0.018)    | -                | -         |     3.63 | casey, Flayy, kisserek, olimp, sNx      |
|            2 |     3915 | 2024-03-02 | Aurora            | L   | 0.155      | -            | -                | -                | -         |    -0.10 | casey, Flayy, kisserek, olimp, sNx      |
|            1 |     3948 | 2024-02-29 | Sangal            | W   | 0.142      | 0.500        | 0.219 (0.016)    | -                | -         |     3.21 | casey, Flayy, kisserek, olimp, sNx      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,215.48)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-13 |      0.842 | $1,089.00      | $917.38         |
| 2024-06-09 |      0.815 | $2,000.00      | $1,629.86       |
| 2024-05-18 |      0.669 | $2,000.00      | $1,337.22       |
| 2024-04-28 |      0.533 | $10,000.00     | $5,331.02       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
