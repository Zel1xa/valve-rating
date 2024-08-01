### Roster Details<br />
Team Name: PERA<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [69](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  956.5<br />
<br />
Final Rank Value (956.5) = Starting Rank Value (932.0) + Head To Head Adjustments (24.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.432[<sup>1</sup>](#table2)
- Bounty Collected: 0.366[<sup>2</sup>](#table1)
- Opponent Network: 0.167[<sup>2</sup>](#table1)
- LAN Wins: 0.068[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 932.0
- 400 + ( ( 0.258 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 932.0


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
|           35 |       31 | 2024-07-31 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.03 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |       80 | 2024-07-30 | Space             | W   | 1.000      | 0.500        | 0.006 (0.003)    | 0.406 (0.203)    | 0 (0.000) |    11.73 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      116 | 2024-07-29 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -16.54 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      446 | 2024-07-19 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -23.07 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      485 | 2024-07-18 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -8.69 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |      557 | 2024-07-17 | Verdant           | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.305 (0.102)    | 0 (0.000) |     9.66 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |      619 | 2024-07-16 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -2.50 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |      672 | 2024-07-15 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.60 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |      982 | 2024-06-13 | Enterprise        | W   | 0.875      | 0.379        | 0.040 (0.013)    | 0.622 (0.206)    | 0 (0.000) |    12.47 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1014 | 2024-06-12 | Rebels            | W   | 0.868      | 0.379        | 0.040 (0.013)    | 0.635 (0.209)    | 0 (0.000) |    15.93 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1037 | 2024-06-11 | ECLOT             | W   | 0.862      | 0.379        | 0.064 (0.021)    | 0.501 (0.164)    | 0 (0.000) |    18.56 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1244 | 2024-06-07 | B8                | L   | 0.834      | -            | -                | -                | -         |    -7.24 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1254 | 2024-06-07 | Aurora            | L   | 0.834      | -            | -                | -                | -         |    -1.06 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     1362 | 2024-06-05 | The Prodigies     | W   | 0.822      | -            | -                | -                | 0 (0.000) |     2.84 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     1443 | 2024-06-03 | GL Academy        | W   | 0.808      | 0.379        | 0.007 (0.002)    | -                | 0 (0.000) |     6.84 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     1553 | 2024-05-30 | Rebels            | L   | 0.782      | -            | -                | -                | -         |   -10.55 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     1736 | 2024-05-22 | System5           | W   | 0.728      | -            | -                | -                | 0 (0.000) |     4.13 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     1794 | 2024-05-21 | EYEBALLERS        | W   | 0.722      | 0.500        | -                | 0.513 (0.185)    | -         |     9.27 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     1837 | 2024-05-20 | Nexus             | W   | 0.714      | 0.379        | 0.014 (0.004)    | 0.504 (0.136)    | -         |     6.91 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     2013 | 2024-05-15 | Norway            | W   | 0.682      | -            | -                | -                | -         |     4.65 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2080 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.675      | 0.500        | 0.032 (0.011)    | 0.564 (0.190)    | -         |    11.98 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2311 | 2024-05-04 | FlyQuest          | L   | 0.607      | -            | -                | -                | -         |    -3.35 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           13 |     2326 | 2024-05-03 | BIG               | L   | 0.600      | -            | -                | -                | -         |    -3.01 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           12 |     2348 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.594      | 0.889        | 0.207 (0.109)    | 0.409 (0.216)    | 1 (0.594) |    17.77 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           11 |     2396 | 2024-04-30 | Complexity        | L   | 0.581      | -            | -                | -                | -         |    -0.31 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           10 |     2613 | 2024-04-20 | EYEBALLERS        | L   | 0.515      | -            | -                | -                | -         |    -8.78 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            9 |     3164 | 2024-04-03 | SAW               | L   | 0.401      | -            | -                | -                | -         |    -2.25 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3221 | 2024-04-01 | RUSH B            | W   | 0.388      | 0.500        | 0.017 (0.003)    | 0.308 (0.060)    | -         |     5.17 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3503 | 2024-03-15 | Betera            | L   | 0.275      | -            | -                | -                | -         |    -6.70 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     3567 | 2024-03-13 | Monte             | L   | 0.262      | -            | -                | -                | -         |    -3.09 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     3954 | 2024-02-26 | System5           | L   | 0.155      | -            | -                | -                | -         |    -3.91 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     4100 | 2024-02-20 | ex-Preasy         | L   | 0.115      | -            | -                | -                | -         |    -2.48 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     4128 | 2024-02-19 | GamerLegion       | L   | 0.108      | -            | -                | -                | -         |    -2.33 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     4131 | 2024-02-19 | Cloud9            | L   | 0.107      | -            | -                | -                | -         |    -1.12 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4199 | 2024-02-16 | SINNERS           | L   | 0.088      | -            | -                | -                | -         |    -0.93 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,834.83)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-13 |      0.875 | $10,895.00     | $9,535.14       |
| 2024-06-09 |      0.848 | $500.00        | $423.85         |
| 2024-05-12 |      0.661 | $7,000.00      | $4,625.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
