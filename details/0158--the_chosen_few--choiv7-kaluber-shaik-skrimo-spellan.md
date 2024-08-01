### Roster Details<br />
Team Name: The Chosen Few<br />
Roster: choiv7, KalubeR, shaiK, Skrimo, SPELLAN<br />
Global Rank: [158](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [103]( ../standings_europe.md)<br />
<br />
Final Rank Value:  693.4<br />
<br />
Final Rank Value (693.4) = Starting Rank Value (674.9) + Head To Head Adjustments (18.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.243[<sup>1</sup>](#table2)
- Bounty Collected: 0.272[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.9
- 400 + ( ( 0.134 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 674.9


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
|           15 |     3507 | 2024-03-15 | Permitta        | L   | 0.274      | -            | -                | -                | -         |    -1.61 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           14 |     3541 | 2024-03-14 | Endpoint        | W   | 0.268      | 0.372        | 0.012 (0.001)    | 0.555 (0.055)    | 0 (0.000) |     6.54 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           13 |     3609 | 2024-03-12 | ARCRED          | W   | 0.254      | 0.372        | 0.039 (0.004)    | 0.327 (0.031)    | 0 (0.000) |     5.83 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           12 |     3673 | 2024-03-09 | Passion UA      | W   | 0.234      | 0.372        | 0.172 (0.015)    | 1.000 (0.087)    | 0 (0.000) |     6.71 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           11 |     3750 | 2024-03-06 | Insilio         | L   | 0.215      | -            | -                | -                | -         |    -1.53 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           10 |     3829 | 2024-03-03 | Metizport       | L   | 0.195      | -            | -                | -                | -         |    -1.35 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            9 |     3834 | 2024-03-03 | TSM             | W   | 0.195      | 0.143        | 0.006 (0.000)    | 0.049 (0.001)    | 0 (0.000) |     3.10 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            8 |     3839 | 2024-03-03 | KOI             | W   | 0.195      | 0.143        | 0.040 (0.001)    | 0.313 (0.009)    | 0 (0.000) |     5.02 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            7 |     4017 | 2024-02-24 | brazylijski luz | L   | 0.140      | -            | -                | -                | -         |    -1.40 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            6 |     4168 | 2024-02-17 | Entropiq        | L   | 0.095      | -            | -                | -                | -         |    -2.00 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            5 |     4171 | 2024-02-17 | kONO            | L   | 0.095      | -            | -                | -                | -         |    -0.93 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            4 |     4178 | 2024-02-17 | Monte           | L   | 0.094      | -            | -                | -                | -         |    -0.40 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            3 |     4335 | 2024-02-10 | ex-Anonymo      | W   | 0.049      | 0.358        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     0.43 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            2 |     4414 | 2024-02-04 | North Macedonia | W   | 0.008      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.06 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            1 |     4432 | 2024-02-03 | Zero Tenacity   | L   | 0.002      | -            | -                | -                | -         |    -0.01 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($255.83)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
