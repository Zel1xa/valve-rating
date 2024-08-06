### Roster Details<br />
Team Name: PERA<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [71](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  957.7<br />
<br />
Final Rank Value (957.7) = Starting Rank Value (930.0) + Head To Head Adjustments (27.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.430[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.168[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.0
- 400 + ( ( 0.258 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 930.0


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
|           35 |      185 | 2024-07-31 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.72 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |      233 | 2024-07-30 | Space             | W   | 1.000      | 0.500        | 0.006 (0.003)    | 0.439 (0.219)    | 0 (0.000) |    11.54 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      269 | 2024-07-29 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -15.25 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      593 | 2024-07-19 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -23.76 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      631 | 2024-07-18 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -8.26 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |      700 | 2024-07-17 | Verdant           | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.294 (0.098)    | 0 (0.000) |     9.01 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |      760 | 2024-07-16 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -2.40 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |      810 | 2024-07-15 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.85 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |     1128 | 2024-06-13 | Enterprise        | W   | 0.842      | 0.379        | 0.039 (0.013)    | 0.616 (0.196)    | 0 (0.000) |    12.12 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1160 | 2024-06-12 | Rebels            | W   | 0.836      | 0.379        | 0.038 (0.012)    | 0.591 (0.187)    | 0 (0.000) |    14.98 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1182 | 2024-06-11 | ECLOT             | W   | 0.829      | 0.379        | 0.061 (0.019)    | 0.549 (0.172)    | 0 (0.000) |    19.74 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1379 | 2024-06-07 | B8                | L   | 0.802      | -            | -                | -                | -         |    -6.66 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1389 | 2024-06-07 | Aurora            | L   | 0.801      | -            | -                | -                | -         |    -0.99 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     1493 | 2024-06-05 | The Prodigies     | W   | 0.789      | -            | -                | -                | 0 (0.000) |     2.66 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     1573 | 2024-06-03 | GL Academy        | W   | 0.776      | -            | -                | -                | 0 (0.000) |     6.38 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     1682 | 2024-05-30 | Rebels            | L   | 0.749      | -            | -                | -                | -         |   -10.39 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     1863 | 2024-05-22 | System5           | W   | 0.696      | -            | -                | -                | 0 (0.000) |     3.85 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     1907 | 2024-05-21 | EYEBALLERS        | W   | 0.689      | 0.500        | -                | 0.499 (0.172)    | -         |     8.67 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     1946 | 2024-05-20 | Nexus             | W   | 0.681      | 0.379        | 0.014 (0.004)    | 0.457 (0.118)    | -         |     6.53 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     2114 | 2024-05-15 | Norway            | W   | 0.649      | 0.500        | 0.006 (0.002)    | -                | -         |     4.29 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2175 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.642      | 0.500        | 0.031 (0.010)    | 0.549 (0.176)    | -         |    11.63 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2401 | 2024-05-04 | FlyQuest          | L   | 0.574      | -            | -                | -                | -         |    -3.57 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           13 |     2416 | 2024-05-03 | BIG               | L   | 0.567      | -            | -                | -                | -         |    -2.10 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           12 |     2437 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.561      | 0.889        | 0.254 (0.127)    | 0.543 (0.271)    | 1 (0.561) |    17.34 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           11 |     2483 | 2024-04-30 | Complexity        | L   | 0.548      | -            | -                | -                | -         |    -0.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           10 |     2694 | 2024-04-20 | EYEBALLERS        | L   | 0.482      | -            | -                | -                | -         |    -8.34 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            9 |     3234 | 2024-04-03 | SAW               | L   | 0.368      | -            | -                | -                | -         |    -2.27 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3289 | 2024-04-01 | RUSH B            | W   | 0.355      | 0.500        | 0.026 (0.005)    | 0.379 (0.067)    | -         |     4.89 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3566 | 2024-03-15 | Betera            | L   | 0.242      | -            | -                | -                | -         |    -5.95 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     3625 | 2024-03-13 | Monte             | L   | 0.229      | -            | -                | -                | -         |    -2.95 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     4004 | 2024-02-26 | System5           | L   | 0.122      | -            | -                | -                | -         |    -3.10 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     4142 | 2024-02-20 | ex-Preasy         | L   | 0.082      | -            | -                | -                | -         |    -1.81 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     4170 | 2024-02-19 | GamerLegion       | L   | 0.075      | -            | -                | -                | -         |    -1.69 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     4173 | 2024-02-19 | Cloud9            | L   | 0.074      | -            | -                | -                | -         |    -0.85 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4241 | 2024-02-16 | SINNERS           | L   | 0.055      | -            | -                | -                | -         |    -0.40 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,231.88)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-13 |      0.842 | $10,895.00     | $9,178.03       |
| 2024-06-09 |      0.815 | $500.00        | $407.47         |
| 2024-05-12 |      0.628 | $7,000.00      | $4,396.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
