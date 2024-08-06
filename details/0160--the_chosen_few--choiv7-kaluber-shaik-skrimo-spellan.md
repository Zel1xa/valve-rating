### Roster Details<br />
Team Name: The Chosen Few<br />
Roster: choiv7, KalubeR, shaiK, Skrimo, SPELLAN<br />
Global Rank: [160](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [103]( ../standings_europe.md)<br />
<br />
Final Rank Value:  687.5<br />
<br />
Final Rank Value (687.5) = Starting Rank Value (670.3) + Head To Head Adjustments (17.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.241[<sup>1</sup>](#table2)
- Bounty Collected: 0.268[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 670.3
- 400 + ( ( 0.131 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 670.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     3577 | 2024-03-15 | Permitta        | L   | 0.240      | -            | -                | -                | -         |    -1.26 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           12 |     3609 | 2024-03-14 | Endpoint        | W   | 0.235      | 0.372        | 0.012 (0.001)    | 0.502 (0.044)    | 0 (0.000) |     5.60 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           11 |     3674 | 2024-03-12 | ARCRED          | W   | 0.221      | 0.372        | 0.041 (0.003)    | 0.369 (0.030)    | 0 (0.000) |     5.47 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           10 |     3737 | 2024-03-09 | Passion UA      | W   | 0.201      | 0.372        | 0.173 (0.013)    | 1.000 (0.075)    | 0 (0.000) |     5.76 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            9 |     3814 | 2024-03-06 | Insilio         | L   | 0.182      | -            | -                | -                | -         |    -1.28 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            8 |     3888 | 2024-03-03 | Metizport       | L   | 0.162      | -            | -                | -                | -         |    -1.10 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            7 |     3893 | 2024-03-03 | TSM             | W   | 0.162      | 0.143        | 0.005 (0.000)    | 0.044 (0.001)    | 0 (0.000) |     2.56 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            6 |     3898 | 2024-03-03 | KOI             | W   | 0.161      | 0.143        | 0.058 (0.001)    | 0.357 (0.008)    | 0 (0.000) |     4.63 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            5 |     4070 | 2024-02-24 | brazylijski luz | L   | 0.107      | -            | -                | -                | -         |    -1.11 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            4 |     4218 | 2024-02-17 | Entropiq        | L   | 0.062      | -            | -                | -                | -         |    -1.30 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            3 |     4221 | 2024-02-17 | kONO            | L   | 0.061      | -            | -                | -                | -         |    -0.60 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            2 |     4228 | 2024-02-17 | Monte           | L   | 0.060      | -            | -                | -                | -         |    -0.28 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            1 |     4375 | 2024-02-10 | ex-Anonymo      | W   | 0.015      | 0.358        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.09 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($230.76)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
