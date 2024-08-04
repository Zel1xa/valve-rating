### Roster Details<br />
Team Name: The Chosen Few<br />
Roster: choiv7, KalubeR, shaiK, Skrimo, SPELLAN<br />
Global Rank: [157](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [102]( ../standings_europe.md)<br />
<br />
Final Rank Value:  688.2<br />
<br />
Final Rank Value (688.2) = Starting Rank Value (670.7) + Head To Head Adjustments (17.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.242[<sup>1</sup>](#table2)
- Bounty Collected: 0.270[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 670.7
- 400 + ( ( 0.132 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 670.7


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
|           13 |     3506 | 2024-03-15 | Permitta        | L   | 0.254      | -            | -                | -                | -         |    -1.42 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           12 |     3538 | 2024-03-14 | Endpoint        | W   | 0.249      | 0.372        | 0.012 (0.001)    | 0.522 (0.048)    | 0 (0.000) |     5.92 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           11 |     3603 | 2024-03-12 | ARCRED          | W   | 0.235      | 0.372        | 0.041 (0.004)    | 0.344 (0.030)    | 0 (0.000) |     5.46 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           10 |     3666 | 2024-03-09 | Passion UA      | W   | 0.215      | 0.372        | 0.172 (0.014)    | 1.000 (0.080)    | 0 (0.000) |     6.13 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            9 |     3743 | 2024-03-06 | Insilio         | L   | 0.196      | -            | -                | -                | -         |    -1.41 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            8 |     3817 | 2024-03-03 | Metizport       | L   | 0.176      | -            | -                | -                | -         |    -1.20 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            7 |     3822 | 2024-03-03 | TSM             | W   | 0.176      | 0.143        | 0.005 (0.000)    | 0.047 (0.001)    | 0 (0.000) |     2.78 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            6 |     3827 | 2024-03-03 | KOI             | W   | 0.175      | 0.143        | 0.058 (0.001)    | 0.375 (0.009)    | 0 (0.000) |     5.04 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            5 |     3999 | 2024-02-24 | brazylijski luz | L   | 0.121      | -            | -                | -                | -         |    -1.26 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            4 |     4147 | 2024-02-17 | Entropiq        | L   | 0.076      | -            | -                | -                | -         |    -1.59 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            3 |     4150 | 2024-02-17 | kONO            | L   | 0.075      | -            | -                | -                | -         |    -0.76 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            2 |     4157 | 2024-02-17 | Monte           | L   | 0.074      | -            | -                | -                | -         |    -0.33 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            1 |     4304 | 2024-02-10 | ex-Anonymo      | W   | 0.029      | 0.358        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.17 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($241.25)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
