### Roster Details<br />
Team Name: INFINITE<br />
Roster: CHANKY, d1maje, mhN1, starplajerz, zewts<br />
Global Rank: [181](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [116]( ../standings_europe.md)<br />
<br />
Final Rank Value:  619.5<br />
<br />
Final Rank Value (619.5) = Starting Rank Value (547.0) + Head To Head Adjustments (72.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.258[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.071<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 547.0
- 400 + ( ( 0.071 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 547.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |       68 | 2024-07-30 | Lilmix          | W   | 1.000      | 0.143        | 0.023 (0.003)    | 0.098 (0.014)    | 0 (0.000) |    25.43 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|           11 |      317 | 2024-07-22 | Into the Breach | L   | 1.000      | -            | -                | -                | -         |   -12.62 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|           10 |      324 | 2024-07-22 | Sampi           | L   | 1.000      | -            | -                | -                | -         |    -5.40 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|            9 |      343 | 2024-07-21 | Heimo           | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.086 (0.012)    | 0 (0.000) |    18.01 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|            8 |      361 | 2024-07-20 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |    -6.20 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|            7 |      396 | 2024-07-19 | 777             | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.183 (0.026)    | 0 (0.000) |    20.45 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|            6 |      472 | 2024-07-18 | Permitta        | W   | 1.000      | 0.143        | 0.024 (0.003)    | 0.799 (0.114)    | 0 (0.000) |    27.75 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|            5 |      938 | 2024-06-14 | TÓR             | L   | 0.884      | -            | -                | -                | -         |    -3.34 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|            4 |      965 | 2024-06-13 | CPH Wolves      | L   | 0.878      | -            | -                | -                | -         |    -5.78 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|            3 |     1362 | 2024-06-04 | Sampi           | L   | 0.819      | -            | -                | -                | -         |    -3.18 | d1maje, mhN1, starplajerz, waZz, zewts   |
|            2 |     1525 | 2024-05-29 | Illuminar       | W   | 0.780      | 0.379        | 0.012 (0.004)    | 0.348 (0.103)    | 0 (0.000) |    20.52 | d1maje, mhN1, starplajerz, waZz, zewts   |
|            1 |     1723 | 2024-05-21 | Permitta        | L   | 0.726      | -            | -                | -                | -         |    -3.14 | d1maje, mhN1, starplajerz, waZz, zewts   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
