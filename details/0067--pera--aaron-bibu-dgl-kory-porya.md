### Roster Details<br />
Team Name: PERA<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [67](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  957.1<br />
<br />
Final Rank Value (957.1) = Starting Rank Value (928.7) + Head To Head Adjustments (28.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.431[<sup>1</sup>](#table2)
- Bounty Collected: 0.363[<sup>2</sup>](#table1)
- Opponent Network: 0.173[<sup>2</sup>](#table1)
- LAN Wins: 0.066[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 928.7
- 400 + ( ( 0.258 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 928.7


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
|           35 |       96 | 2024-07-31 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.93 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |      143 | 2024-07-30 | Space             | W   | 1.000      | 0.500        | 0.006 (0.003)    | 0.420 (0.210)    | 0 (0.000) |    11.95 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      178 | 2024-07-29 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -16.42 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      503 | 2024-07-19 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -24.36 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      541 | 2024-07-18 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -8.70 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |      610 | 2024-07-17 | Verdant           | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.310 (0.103)    | 0 (0.000) |     9.12 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |      667 | 2024-07-16 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -2.54 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |      716 | 2024-07-15 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.20 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |     1010 | 2024-06-13 | Enterprise        | W   | 0.861      | 0.379        | 0.039 (0.013)    | 0.646 (0.210)    | 0 (0.000) |    12.30 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1041 | 2024-06-12 | Rebels            | W   | 0.854      | 0.379        | 0.038 (0.012)    | 0.605 (0.196)    | 0 (0.000) |    15.29 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1062 | 2024-06-11 | ECLOT             | W   | 0.847      | 0.379        | 0.063 (0.020)    | 0.578 (0.185)    | 0 (0.000) |    20.13 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1251 | 2024-06-07 | B8                | L   | 0.820      | -            | -                | -                | -         |    -6.82 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1261 | 2024-06-07 | Aurora            | L   | 0.819      | -            | -                | -                | -         |    -1.05 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     1365 | 2024-06-05 | The Prodigies     | W   | 0.807      | -            | -                | -                | 0 (0.000) |     2.75 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     1444 | 2024-06-03 | GL Academy        | W   | 0.794      | 0.379        | 0.007 (0.002)    | -                | 0 (0.000) |     6.64 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     1551 | 2024-05-30 | Rebels            | L   | 0.767      | -            | -                | -                | -         |   -10.63 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     1731 | 2024-05-22 | System5           | W   | 0.714      | -            | -                | -                | 0 (0.000) |     4.01 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     1775 | 2024-05-21 | EYEBALLERS        | W   | 0.707      | 0.500        | -                | 0.528 (0.187)    | -         |     9.03 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     1814 | 2024-05-20 | Nexus             | W   | 0.699      | 0.379        | 0.014 (0.004)    | 0.441 (0.117)    | -         |     6.75 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     1981 | 2024-05-15 | Norway            | W   | 0.667      | -            | -                | -                | -         |     4.47 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2042 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.660      | 0.500        | 0.032 (0.010)    | 0.580 (0.192)    | -         |    12.03 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2267 | 2024-05-04 | FlyQuest          | L   | 0.592      | -            | -                | -                | -         |    -3.52 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           13 |     2282 | 2024-05-03 | BIG               | L   | 0.585      | -            | -                | -                | -         |    -2.07 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           12 |     2303 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.579      | 0.889        | 0.204 (0.105)    | 0.502 (0.259)    | 1 (0.579) |    17.74 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           11 |     2349 | 2024-04-30 | Complexity        | L   | 0.566      | -            | -                | -                | -         |    -0.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           10 |     2559 | 2024-04-20 | EYEBALLERS        | L   | 0.500      | -            | -                | -                | -         |    -8.59 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            9 |     3099 | 2024-04-03 | SAW               | L   | 0.386      | -            | -                | -                | -         |    -2.27 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3154 | 2024-04-01 | RUSH B            | W   | 0.373      | 0.500        | 0.017 (0.003)    | 0.399 (0.074)    | -         |     5.02 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3425 | 2024-03-15 | Betera            | L   | 0.260      | -            | -                | -                | -         |    -6.36 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     3484 | 2024-03-13 | Monte             | L   | 0.247      | -            | -                | -                | -         |    -3.04 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     3861 | 2024-02-26 | System5           | L   | 0.141      | -            | -                | -                | -         |    -3.54 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     3999 | 2024-02-20 | ex-Preasy         | L   | 0.100      | -            | -                | -                | -         |    -2.19 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     4027 | 2024-02-19 | GamerLegion       | L   | 0.093      | -            | -                | -                | -         |    -2.05 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     4030 | 2024-02-19 | Cloud9            | L   | 0.092      | -            | -                | -                | -         |    -1.03 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4097 | 2024-02-16 | SINNERS           | L   | 0.073      | -            | -                | -                | -         |    -0.67 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,564.87)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-13 |      0.861 | $10,895.00     | $9,375.25       |
| 2024-06-09 |      0.833 | $500.00        | $416.52         |
| 2024-05-12 |      0.646 | $7,000.00      | $4,523.10       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
