### Roster Details<br />
Team Name: PERA<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [73](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  958.7<br />
<br />
Final Rank Value (958.7) = Starting Rank Value (929.6) + Head To Head Adjustments (29.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.430[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.165[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.257<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 929.6
- 400 + ( ( 0.257 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 929.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |      202 | 2024-07-31 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.68 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |      250 | 2024-07-30 | Space             | W   | 1.000      | 0.500        | 0.006 (0.003)    | 0.429 (0.215)    | 0 (0.000) |    11.81 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      286 | 2024-07-29 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -15.20 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      610 | 2024-07-19 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -23.67 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      648 | 2024-07-18 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -8.23 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |      717 | 2024-07-17 | Verdant           | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.287 (0.096)    | 0 (0.000) |     9.11 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |      777 | 2024-07-16 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -2.37 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |      827 | 2024-07-15 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.85 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |     1145 | 2024-06-13 | Enterprise        | W   | 0.841      | 0.379        | 0.039 (0.012)    | 0.641 (0.204)    | 0 (0.000) |    12.16 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1177 | 2024-06-12 | Rebels            | W   | 0.834      | 0.379        | 0.038 (0.012)    | 0.578 (0.183)    | 0 (0.000) |    14.98 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1199 | 2024-06-11 | ECLOT             | W   | 0.827      | 0.379        | 0.061 (0.019)    | 0.537 (0.168)    | 0 (0.000) |    19.75 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1396 | 2024-06-07 | B8                | L   | 0.800      | -            | -                | -                | -         |    -6.59 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1406 | 2024-06-07 | Aurora            | L   | 0.799      | -            | -                | -                | -         |    -0.97 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     1510 | 2024-06-05 | The Prodigies     | W   | 0.787      | -            | -                | -                | 0 (0.000) |     2.65 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     1590 | 2024-06-03 | GL Academy        | W   | 0.774      | -            | -                | -                | 0 (0.000) |     6.41 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     1699 | 2024-05-30 | Rebels            | L   | 0.747      | -            | -                | -                | -         |   -10.36 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     1880 | 2024-05-22 | System5           | W   | 0.694      | -            | -                | -                | 0 (0.000) |     3.85 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     1924 | 2024-05-21 | EYEBALLERS        | W   | 0.687      | 0.500        | -                | 0.488 (0.168)    | -         |     8.81 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     1963 | 2024-05-20 | Nexus             | W   | 0.680      | 0.379        | 0.014 (0.004)    | 0.447 (0.115)    | -         |     6.61 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     2131 | 2024-05-15 | Norway            | W   | 0.647      | 0.500        | 0.006 (0.002)    | -                | -         |     4.29 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2192 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.641      | 0.500        | 0.031 (0.010)    | 0.537 (0.172)    | -         |    11.68 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2418 | 2024-05-04 | FlyQuest          | L   | 0.572      | -            | -                | -                | -         |    -3.57 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           13 |     2433 | 2024-05-03 | BIG               | L   | 0.565      | -            | -                | -                | -         |    -2.09 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           12 |     2454 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.560      | 0.889        | 0.253 (0.126)    | 0.531 (0.264)    | 1 (0.560) |    17.29 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           11 |     2500 | 2024-04-30 | Complexity        | L   | 0.546      | -            | -                | -                | -         |    -0.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           10 |     2711 | 2024-04-20 | EYEBALLERS        | L   | 0.481      | -            | -                | -                | -         |    -8.27 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            9 |     3251 | 2024-04-03 | SAW               | L   | 0.366      | -            | -                | -                | -         |    -2.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3306 | 2024-04-01 | RUSH B            | W   | 0.353      | 0.500        | 0.026 (0.005)    | 0.371 (0.066)    | -         |     4.88 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3583 | 2024-03-15 | Betera            | L   | 0.240      | -            | -                | -                | -         |    -5.90 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     3642 | 2024-03-13 | Monte             | L   | 0.228      | -            | -                | -                | -         |    -2.92 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     4021 | 2024-02-26 | System5           | L   | 0.121      | -            | -                | -                | -         |    -3.05 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     4159 | 2024-02-20 | ex-Preasy         | L   | 0.080      | -            | -                | -                | -         |    -1.77 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     4187 | 2024-02-19 | GamerLegion       | L   | 0.073      | -            | -                | -                | -         |    -1.65 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     4190 | 2024-02-19 | Cloud9            | L   | 0.073      | -            | -                | -                | -         |    -0.84 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4258 | 2024-02-16 | SINNERS           | L   | 0.054      | -            | -                | -                | -         |    -0.38 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,201.22)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-13 |      0.841 | $10,895.00     | $9,159.87       |
| 2024-06-09 |      0.813 | $500.00        | $406.63         |
| 2024-05-12 |      0.626 | $7,000.00      | $4,384.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
