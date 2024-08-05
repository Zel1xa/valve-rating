### Roster Details<br />
Team Name: The Chosen Few<br />
Roster: choiv7, KalubeR, shaiK, Skrimo, SPELLAN<br />
Global Rank: [156](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [102]( ../standings_europe.md)<br />
<br />
Final Rank Value:  694.8<br />
<br />
Final Rank Value (694.8) = Starting Rank Value (676.0) + Head To Head Adjustments (18.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.243[<sup>1</sup>](#table2)
- Bounty Collected: 0.273[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 676.0
- 400 + ( ( 0.134 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 676.0


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
|           15 |     3389 | 2024-03-15 | Permitta        | L   | 0.278      | -            | -                | -                | -         |    -1.70 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           14 |     3421 | 2024-03-14 | Endpoint        | W   | 0.272      | 0.372        | 0.012 (0.001)    | 0.523 (0.053)    | 0 (0.000) |     6.48 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           13 |     3486 | 2024-03-12 | ARCRED          | W   | 0.259      | 0.372        | 0.038 (0.004)    | 0.328 (0.032)    | 0 (0.000) |     5.91 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           12 |     3549 | 2024-03-09 | Passion UA      | W   | 0.239      | 0.372        | 0.171 (0.015)    | 1.000 (0.089)    | 0 (0.000) |     6.80 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           11 |     3626 | 2024-03-06 | Insilio         | L   | 0.219      | -            | -                | -                | -         |    -1.58 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           10 |     3700 | 2024-03-03 | Metizport       | L   | 0.200      | -            | -                | -                | -         |    -1.35 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            9 |     3705 | 2024-03-03 | TSM             | W   | 0.199      | 0.143        | 0.006 (0.000)    | 0.050 (0.001)    | 0 (0.000) |     3.17 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            8 |     3710 | 2024-03-03 | KOI             | W   | 0.199      | 0.143        | 0.059 (0.002)    | 0.382 (0.011)    | 0 (0.000) |     5.76 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            7 |     3882 | 2024-02-24 | brazylijski luz | L   | 0.145      | -            | -                | -                | -         |    -1.50 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            6 |     4030 | 2024-02-17 | Entropiq        | L   | 0.100      | -            | -                | -                | -         |    -2.09 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            5 |     4033 | 2024-02-17 | kONO            | L   | 0.099      | -            | -                | -                | -         |    -1.00 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            4 |     4040 | 2024-02-17 | Monte           | L   | 0.098      | -            | -                | -                | -         |    -0.41 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            3 |     4187 | 2024-02-10 | ex-Anonymo      | W   | 0.053      | 0.358        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.29 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            2 |     4265 | 2024-02-04 | North Macedonia | W   | 0.012      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.09 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            1 |     4283 | 2024-02-03 | Zero Tenacity   | L   | 0.006      | -            | -                | -                | -         |    -0.02 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($259.09)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
