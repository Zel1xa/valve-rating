### Roster Details<br />
Team Name: PERA<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [70](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  958.2<br />
<br />
Final Rank Value (958.2) = Starting Rank Value (929.8) + Head To Head Adjustments (28.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.430[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.165[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 929.8
- 400 + ( ( 0.258 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 929.8


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
|           35 |      189 | 2024-07-31 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.70 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |      237 | 2024-07-30 | Space             | W   | 1.000      | 0.500        | 0.006 (0.003)    | 0.429 (0.215)    | 0 (0.000) |    11.71 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      273 | 2024-07-29 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -15.25 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      597 | 2024-07-19 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -23.72 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      635 | 2024-07-18 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -8.25 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |      704 | 2024-07-17 | Verdant           | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.287 (0.096)    | 0 (0.000) |     9.04 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |      764 | 2024-07-16 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -2.38 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |      814 | 2024-07-15 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.85 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |     1132 | 2024-06-13 | Enterprise        | W   | 0.842      | 0.379        | 0.039 (0.013)    | 0.641 (0.204)    | 0 (0.000) |    12.11 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1164 | 2024-06-12 | Rebels            | W   | 0.835      | 0.379        | 0.038 (0.012)    | 0.578 (0.183)    | 0 (0.000) |    14.98 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1186 | 2024-06-11 | ECLOT             | W   | 0.829      | 0.379        | 0.061 (0.019)    | 0.537 (0.168)    | 0 (0.000) |    19.75 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1383 | 2024-06-07 | B8                | L   | 0.801      | -            | -                | -                | -         |    -6.62 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1393 | 2024-06-07 | Aurora            | L   | 0.801      | -            | -                | -                | -         |    -0.98 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     1497 | 2024-06-05 | The Prodigies     | W   | 0.789      | -            | -                | -                | 0 (0.000) |     2.66 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     1577 | 2024-06-03 | GL Academy        | W   | 0.775      | -            | -                | -                | 0 (0.000) |     6.39 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     1686 | 2024-05-30 | Rebels            | L   | 0.749      | -            | -                | -                | -         |   -10.38 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     1867 | 2024-05-22 | System5           | W   | 0.695      | -            | -                | -                | 0 (0.000) |     3.86 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     1911 | 2024-05-21 | EYEBALLERS        | W   | 0.689      | 0.500        | -                | 0.488 (0.168)    | -         |     8.80 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     1950 | 2024-05-20 | Nexus             | W   | 0.681      | 0.379        | 0.014 (0.004)    | 0.447 (0.115)    | -         |     6.57 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     2118 | 2024-05-15 | Norway            | W   | 0.649      | 0.500        | 0.006 (0.002)    | -                | -         |     4.30 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2179 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.642      | 0.500        | 0.031 (0.010)    | 0.537 (0.172)    | -         |    11.66 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2405 | 2024-05-04 | FlyQuest          | L   | 0.573      | -            | -                | -                | -         |    -3.57 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           13 |     2420 | 2024-05-03 | BIG               | L   | 0.567      | -            | -                | -                | -         |    -2.09 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           12 |     2441 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.561      | 0.889        | 0.254 (0.126)    | 0.531 (0.265)    | 1 (0.561) |    17.33 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           11 |     2487 | 2024-04-30 | Complexity        | L   | 0.548      | -            | -                | -                | -         |    -0.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           10 |     2698 | 2024-04-20 | EYEBALLERS        | L   | 0.482      | -            | -                | -                | -         |    -8.31 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            9 |     3238 | 2024-04-03 | SAW               | L   | 0.367      | -            | -                | -                | -         |    -2.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3293 | 2024-04-01 | RUSH B            | W   | 0.355      | 0.500        | 0.026 (0.005)    | 0.371 (0.066)    | -         |     4.89 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3570 | 2024-03-15 | Betera            | L   | 0.242      | -            | -                | -                | -         |    -5.93 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     3629 | 2024-03-13 | Monte             | L   | 0.229      | -            | -                | -                | -         |    -2.94 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     4008 | 2024-02-26 | System5           | L   | 0.122      | -            | -                | -                | -         |    -3.09 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     4146 | 2024-02-20 | ex-Preasy         | L   | 0.082      | -            | -                | -                | -         |    -1.80 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     4174 | 2024-02-19 | GamerLegion       | L   | 0.075      | -            | -                | -                | -         |    -1.68 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     4177 | 2024-02-19 | Cloud9            | L   | 0.074      | -            | -                | -                | -         |    -0.85 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4245 | 2024-02-16 | SINNERS           | L   | 0.055      | -            | -                | -                | -         |    -0.39 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,226.77)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-13 |      0.842 | $10,895.00     | $9,175.00       |
| 2024-06-09 |      0.815 | $500.00        | $407.33         |
| 2024-05-12 |      0.628 | $7,000.00      | $4,394.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
