### Roster Details<br />
Team Name: PERA<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [68](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  956.3<br />
<br />
Final Rank Value (956.3) = Starting Rank Value (932.1) + Head To Head Adjustments (24.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.432[<sup>1</sup>](#table2)
- Bounty Collected: 0.366[<sup>2</sup>](#table1)
- Opponent Network: 0.169[<sup>2</sup>](#table1)
- LAN Wins: 0.068[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 932.1
- 400 + ( ( 0.259 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 932.1


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
|           35 |       35 | 2024-07-31 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.05 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |       84 | 2024-07-30 | Space             | W   | 1.000      | 0.500        | 0.006 (0.003)    | 0.406 (0.203)    | 0 (0.000) |    11.71 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      120 | 2024-07-29 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -16.57 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      450 | 2024-07-19 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -23.08 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      489 | 2024-07-18 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -8.72 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |      561 | 2024-07-17 | Verdant           | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.305 (0.102)    | 0 (0.000) |     9.65 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |      623 | 2024-07-16 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -2.50 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |      676 | 2024-07-15 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.60 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |      986 | 2024-06-13 | Enterprise        | W   | 0.874      | 0.379        | 0.040 (0.013)    | 0.622 (0.206)    | 0 (0.000) |    12.42 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1018 | 2024-06-12 | Rebels            | W   | 0.867      | 0.379        | 0.040 (0.013)    | 0.635 (0.209)    | 0 (0.000) |    15.87 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1041 | 2024-06-11 | ECLOT             | W   | 0.860      | 0.379        | 0.064 (0.021)    | 0.501 (0.163)    | 0 (0.000) |    18.49 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1248 | 2024-06-07 | B8                | L   | 0.833      | -            | -                | -                | -         |    -7.26 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1258 | 2024-06-07 | Aurora            | L   | 0.832      | -            | -                | -                | -         |    -1.06 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     1366 | 2024-06-05 | The Prodigies     | W   | 0.820      | -            | -                | -                | 0 (0.000) |     2.83 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     1447 | 2024-06-03 | GL Academy        | W   | 0.807      | 0.379        | 0.007 (0.002)    | -                | 0 (0.000) |     6.81 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     1557 | 2024-05-30 | Rebels            | L   | 0.780      | -            | -                | -                | -         |   -10.57 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     1740 | 2024-05-22 | System5           | W   | 0.727      | -            | -                | -                | 0 (0.000) |     4.11 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     1798 | 2024-05-21 | EYEBALLERS        | W   | 0.720      | 0.500        | -                | 0.512 (0.185)    | -         |     9.22 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     1841 | 2024-05-20 | Nexus             | W   | 0.713      | 0.379        | 0.014 (0.004)    | 0.504 (0.136)    | -         |     6.88 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     2017 | 2024-05-15 | Norway            | W   | 0.680      | -            | -                | -                | -         |     4.62 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2084 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.674      | 0.500        | 0.032 (0.011)    | 0.563 (0.190)    | -         |    11.92 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2315 | 2024-05-04 | FlyQuest          | L   | 0.605      | -            | -                | -                | -         |    -3.36 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           13 |     2330 | 2024-05-03 | BIG               | L   | 0.598      | -            | -                | -                | -         |    -3.03 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           12 |     2352 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.593      | 0.889        | 0.207 (0.109)    | 0.447 (0.236)    | 1 (0.593) |    17.96 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           11 |     2400 | 2024-04-30 | Complexity        | L   | 0.579      | -            | -                | -                | -         |    -0.31 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           10 |     2617 | 2024-04-20 | EYEBALLERS        | L   | 0.514      | -            | -                | -                | -         |    -8.78 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            9 |     3168 | 2024-04-03 | SAW               | L   | 0.399      | -            | -                | -                | -         |    -2.26 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3225 | 2024-04-01 | RUSH B            | W   | 0.386      | 0.500        | 0.017 (0.003)    | 0.308 (0.060)    | -         |     5.13 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3507 | 2024-03-15 | Betera            | L   | 0.273      | -            | -                | -                | -         |    -6.68 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     3571 | 2024-03-13 | Monte             | L   | 0.261      | -            | -                | -                | -         |    -3.09 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     3958 | 2024-02-26 | System5           | L   | 0.154      | -            | -                | -                | -         |    -3.87 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     4104 | 2024-02-20 | ex-Preasy         | L   | 0.113      | -            | -                | -                | -         |    -2.46 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     4132 | 2024-02-19 | GamerLegion       | L   | 0.107      | -            | -                | -                | -         |    -2.30 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     4135 | 2024-02-19 | Cloud9            | L   | 0.106      | -            | -                | -                | -         |    -1.11 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4203 | 2024-02-16 | SINNERS           | L   | 0.087      | -            | -                | -                | -         |    -0.92 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,809.28)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-13 |      0.874 | $10,895.00     | $9,520.01       |
| 2024-06-09 |      0.846 | $500.00        | $423.16         |
| 2024-05-12 |      0.659 | $7,000.00      | $4,616.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
