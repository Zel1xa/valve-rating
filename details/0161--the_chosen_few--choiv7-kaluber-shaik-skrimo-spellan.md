### Roster Details<br />
Team Name: The Chosen Few<br />
Roster: choiv7, KalubeR, shaiK, Skrimo, SPELLAN<br />
Global Rank: [161](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [104]( ../standings_europe.md)<br />
<br />
Final Rank Value:  687.2<br />
<br />
Final Rank Value (687.2) = Starting Rank Value (670.2) + Head To Head Adjustments (17.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.242[<sup>1</sup>](#table2)
- Bounty Collected: 0.270[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 670.2
- 400 + ( ( 0.132 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 670.2


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
|           13 |     3542 | 2024-03-15 | Permitta        | L   | 0.250      | -            | -                | -                | -         |    -1.39 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           12 |     3574 | 2024-03-14 | Endpoint        | W   | 0.244      | 0.372        | 0.012 (0.001)    | 0.522 (0.048)    | 0 (0.000) |     5.83 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           11 |     3639 | 2024-03-12 | ARCRED          | W   | 0.231      | 0.372        | 0.041 (0.004)    | 0.344 (0.030)    | 0 (0.000) |     5.37 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           10 |     3702 | 2024-03-09 | Passion UA      | W   | 0.211      | 0.372        | 0.172 (0.014)    | 1.000 (0.078)    | 0 (0.000) |     6.03 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            9 |     3779 | 2024-03-06 | Insilio         | L   | 0.191      | -            | -                | -                | -         |    -1.36 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            8 |     3853 | 2024-03-03 | Metizport       | L   | 0.172      | -            | -                | -                | -         |    -1.54 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            7 |     3858 | 2024-03-03 | TSM             | W   | 0.172      | 0.143        | 0.005 (0.000)    | 0.046 (0.001)    | 0 (0.000) |     2.71 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            6 |     3863 | 2024-03-03 | KOI             | W   | 0.171      | 0.143        | 0.058 (0.001)    | 0.374 (0.009)    | 0 (0.000) |     4.92 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            5 |     4035 | 2024-02-24 | brazylijski luz | L   | 0.117      | -            | -                | -                | -         |    -1.21 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            4 |     4183 | 2024-02-17 | Entropiq        | L   | 0.072      | -            | -                | -                | -         |    -1.50 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            3 |     4186 | 2024-02-17 | kONO            | L   | 0.071      | -            | -                | -                | -         |    -0.71 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            2 |     4193 | 2024-02-17 | Monte           | L   | 0.070      | -            | -                | -                | -         |    -0.32 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            1 |     4340 | 2024-02-10 | ex-Anonymo      | W   | 0.025      | 0.358        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.14 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($238.13)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
