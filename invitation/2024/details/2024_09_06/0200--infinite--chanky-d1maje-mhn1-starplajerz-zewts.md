### Roster Details<br />
Team Name: INFINITE<br />
Roster: CHANKY, d1maje, mhN1, starplajerz, zewts<br />
Global Rank: [200](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [127]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  584.8<br />
<br />
Final Rank Value (584.8) = Starting Rank Value (533.7) + Head To Head Adjustments (51.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.250[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.068<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 533.7
- 400 + ( ( 0.068 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 533.7


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
|           14 |      995 | 2024-08-08 | Meteor          | L   | 1.000      | -            | -                | -                | -         |   -10.08 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|           13 |     1121 | 2024-08-05 | kONO            | L   | 0.984      | -            | -                | -                | -         |    -6.67 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|           12 |     1343 | 2024-07-30 | Lilmix          | W   | 0.945      | 0.143        | 0.017 (0.002)    | 0.074 (0.010)    | 0 (0.000) |    22.25 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|           11 |     1593 | 2024-07-22 | Into the Breach | L   | 0.892      | -            | -                | -                | -         |    -4.71 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|           10 |     1599 | 2024-07-22 | Sampi           | L   | 0.891      | -            | -                | -                | -         |    -4.40 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|            9 |     1619 | 2024-07-21 | Heimo           | W   | 0.885      | 0.143        | 0.004 (0.000)    | 0.075 (0.009)    | 0 (0.000) |    15.85 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|            8 |     1637 | 2024-07-20 | CPH Wolves      | L   | 0.880      | -            | -                | -                | -         |    -5.38 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|            7 |     1672 | 2024-07-19 | 777             | W   | 0.873      | 0.143        | 0.010 (0.001)    | 0.117 (0.015)    | 0 (0.000) |    17.52 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|            6 |     1748 | 2024-07-18 | Permitta        | W   | 0.865      | 0.143        | 0.032 (0.004)    | 0.998 (0.123)    | 0 (0.000) |    24.22 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|            5 |     2217 | 2024-06-14 | TÓR             | L   | 0.637      | -            | -                | -                | -         |    -3.66 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|            4 |     2244 | 2024-06-13 | CPH Wolves      | L   | 0.632      | -            | -                | -                | -         |    -4.03 | CHANKY, d1maje, mhN1, starplajerz, zewts |
|            3 |     2641 | 2024-06-04 | Sampi           | L   | 0.573      | -            | -                | -                | -         |    -2.09 | d1maje, mhN1, starplajerz, waZz, zewts   |
|            2 |     2804 | 2024-05-29 | Illuminar       | W   | 0.534      | 0.379        | 0.010 (0.002)    | 0.395 (0.080)    | 0 (0.000) |    14.06 | d1maje, mhN1, starplajerz, waZz, zewts   |
|            1 |     3002 | 2024-05-21 | Permitta        | L   | 0.480      | -            | -                | -                | -         |    -1.77 | d1maje, mhN1, starplajerz, waZz, zewts   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
