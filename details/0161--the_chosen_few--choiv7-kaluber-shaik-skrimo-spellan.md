### Roster Details<br />
Team Name: The Chosen Few<br />
Roster: choiv7, KalubeR, shaiK, Skrimo, SPELLAN<br />
Global Rank: [161](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [104]( ../standings_europe.md)<br />
<br />
Final Rank Value:  687.6<br />
<br />
Final Rank Value (687.6) = Starting Rank Value (670.5) + Head To Head Adjustments (17.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.242[<sup>1</sup>](#table2)
- Bounty Collected: 0.270[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 670.5
- 400 + ( ( 0.132 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 670.5


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
|           13 |     3538 | 2024-03-15 | Permitta        | L   | 0.253      | -            | -                | -                | -         |    -1.41 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           12 |     3570 | 2024-03-14 | Endpoint        | W   | 0.247      | 0.372        | 0.012 (0.001)    | 0.522 (0.048)    | 0 (0.000) |     5.89 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           11 |     3635 | 2024-03-12 | ARCRED          | W   | 0.233      | 0.372        | 0.041 (0.004)    | 0.344 (0.030)    | 0 (0.000) |     5.42 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           10 |     3698 | 2024-03-09 | Passion UA      | W   | 0.213      | 0.372        | 0.172 (0.014)    | 1.000 (0.079)    | 0 (0.000) |     6.10 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            9 |     3775 | 2024-03-06 | Insilio         | L   | 0.194      | -            | -                | -                | -         |    -1.38 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            8 |     3849 | 2024-03-03 | Metizport       | L   | 0.174      | -            | -                | -                | -         |    -1.56 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            7 |     3854 | 2024-03-03 | TSM             | W   | 0.174      | 0.143        | 0.005 (0.000)    | 0.047 (0.001)    | 0 (0.000) |     2.75 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            6 |     3859 | 2024-03-03 | KOI             | W   | 0.173      | 0.143        | 0.058 (0.001)    | 0.375 (0.009)    | 0 (0.000) |     4.99 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            5 |     4031 | 2024-02-24 | brazylijski luz | L   | 0.119      | -            | -                | -                | -         |    -1.23 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            4 |     4179 | 2024-02-17 | Entropiq        | L   | 0.074      | -            | -                | -                | -         |    -1.55 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            3 |     4182 | 2024-02-17 | kONO            | L   | 0.073      | -            | -                | -                | -         |    -0.74 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            2 |     4189 | 2024-02-17 | Monte           | L   | 0.072      | -            | -                | -                | -         |    -0.33 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            1 |     4336 | 2024-02-10 | ex-Anonymo      | W   | 0.028      | 0.358        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.16 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($239.91)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
