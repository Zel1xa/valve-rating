### Roster Details<br />
Team Name: PERA<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [71](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  958.1<br />
<br />
Final Rank Value (958.1) = Starting Rank Value (930.6) + Head To Head Adjustments (27.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.431[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.169[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.6
- 400 + ( ( 0.259 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 930.6


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
|           35 |      179 | 2024-07-31 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.72 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |      227 | 2024-07-30 | Space             | W   | 1.000      | 0.500        | 0.006 (0.003)    | 0.439 (0.220)    | 0 (0.000) |    11.53 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      263 | 2024-07-29 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -15.26 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      587 | 2024-07-19 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -23.80 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      625 | 2024-07-18 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -8.25 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |      694 | 2024-07-17 | Verdant           | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.294 (0.098)    | 0 (0.000) |     8.98 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |      754 | 2024-07-16 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -2.43 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |      804 | 2024-07-15 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.84 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |     1122 | 2024-06-13 | Enterprise        | W   | 0.847      | 0.379        | 0.039 (0.013)    | 0.616 (0.198)    | 0 (0.000) |    12.16 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1154 | 2024-06-12 | Rebels            | W   | 0.840      | 0.379        | 0.038 (0.012)    | 0.591 (0.188)    | 0 (0.000) |    15.04 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1176 | 2024-06-11 | ECLOT             | W   | 0.833      | 0.379        | 0.062 (0.019)    | 0.550 (0.173)    | 0 (0.000) |    19.84 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1373 | 2024-06-07 | B8                | L   | 0.806      | -            | -                | -                | -         |    -6.68 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1383 | 2024-06-07 | Aurora            | L   | 0.805      | -            | -                | -                | -         |    -1.00 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     1487 | 2024-06-05 | The Prodigies     | W   | 0.793      | -            | -                | -                | 0 (0.000) |     2.67 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     1567 | 2024-06-03 | GL Academy        | W   | 0.780      | -            | -                | -                | 0 (0.000) |     6.42 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     1676 | 2024-05-30 | Rebels            | L   | 0.753      | -            | -                | -                | -         |   -10.47 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     1857 | 2024-05-22 | System5           | W   | 0.700      | -            | -                | -                | 0 (0.000) |     3.88 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     1901 | 2024-05-21 | EYEBALLERS        | W   | 0.693      | 0.500        | -                | 0.500 (0.173)    | -         |     8.71 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     1940 | 2024-05-20 | Nexus             | W   | 0.686      | 0.379        | 0.014 (0.004)    | 0.458 (0.119)    | -         |     6.54 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     2108 | 2024-05-15 | Norway            | W   | 0.653      | 0.500        | 0.006 (0.002)    | -                | -         |     4.32 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2169 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.647      | 0.500        | 0.031 (0.010)    | 0.550 (0.178)    | -         |    11.71 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2395 | 2024-05-04 | FlyQuest          | L   | 0.578      | -            | -                | -                | -         |    -3.56 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           13 |     2410 | 2024-05-03 | BIG               | L   | 0.571      | -            | -                | -                | -         |    -2.11 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           12 |     2431 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.566      | 0.889        | 0.254 (0.128)    | 0.544 (0.274)    | 1 (0.566) |    17.47 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           11 |     2477 | 2024-04-30 | Complexity        | L   | 0.552      | -            | -                | -                | -         |    -0.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           10 |     2688 | 2024-04-20 | EYEBALLERS        | L   | 0.487      | -            | -                | -                | -         |    -8.42 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            9 |     3228 | 2024-04-03 | SAW               | L   | 0.372      | -            | -                | -                | -         |    -2.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3283 | 2024-04-01 | RUSH B            | W   | 0.359      | 0.500        | 0.026 (0.005)    | 0.380 (0.068)    | -         |     4.95 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3560 | 2024-03-15 | Betera            | L   | 0.246      | -            | -                | -                | -         |    -6.05 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     3619 | 2024-03-13 | Monte             | L   | 0.233      | -            | -                | -                | -         |    -2.99 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     3998 | 2024-02-26 | System5           | L   | 0.127      | -            | -                | -                | -         |    -3.21 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     4136 | 2024-02-20 | ex-Preasy         | L   | 0.086      | -            | -                | -                | -         |    -1.90 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     4164 | 2024-02-19 | GamerLegion       | L   | 0.079      | -            | -                | -                | -         |    -1.78 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     4167 | 2024-02-19 | Cloud9            | L   | 0.079      | -            | -                | -                | -         |    -0.90 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4235 | 2024-02-16 | SINNERS           | L   | 0.060      | -            | -                | -                | -         |    -0.43 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,311.08)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-13 |      0.847 | $10,895.00     | $9,224.94       |
| 2024-06-09 |      0.819 | $500.00        | $409.62         |
| 2024-05-12 |      0.632 | $7,000.00      | $4,426.53       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
