### Roster Details<br />
Team Name: ex-GUILD fe<br />
Roster: Ann4, D7, KiTKaT, Nea, pullox<br />
Global Rank: [168](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [108]( ../standings_europe.md)<br />
<br />
Final Rank Value:  667.2<br />
<br />
Final Rank Value (667.2) = Starting Rank Value (662.7) + Head To Head Adjustments (4.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.278[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.127<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 662.7
- 400 + ( ( 0.127 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 662.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     1821 | 2024-05-18 | NIP Impact        | L   | 0.705      | -            | -                | -                | -         |    -9.35 | Ann4, D7, KiTKaT, Nea, pullox |
|           10 |     2490 | 2024-04-21 | Fearless Cheetahs | W   | 0.526      | 0.331        | 0.003 (0.001)    | 0.067 (0.012)    | 0 (0.000) |     9.10 | Ann4, D7, KiTKaT, Nea, pullox |
|            9 |     2521 | 2024-04-20 | Let Her Cook      | L   | 0.518      | -            | -                | -                | -         |    -3.36 | Ann4, D7, KiTKaT, Nea, pullox |
|            8 |     2560 | 2024-04-19 | Imperial fe       | L   | 0.513      | -            | -                | -                | -         |    -1.75 | Ann4, D7, KiTKaT, Nea, pullox |
|            7 |     2820 | 2024-04-10 | NIP Impact        | W   | 0.453      | 0.331        | 0.005 (0.001)    | 0.191 (0.029)    | 0 (0.000) |     8.35 | Ann4, D7, KiTKaT, Nea, pullox |
|            6 |     2958 | 2024-04-06 | NIP Impact        | L   | 0.424      | -            | -                | -                | -         |    -5.89 | Ann4, D7, KiTKaT, Nea, pullox |
|            5 |     3143 | 2024-03-28 | BIG EQUIPA        | W   | 0.366      | 0.331        | 0.017 (0.002)    | 0.156 (0.019)    | 0 (0.000) |     7.55 | Ann4, D7, KiTKaT, Nea, pullox |
|            4 |     3268 | 2024-03-21 | Astralis W        | W   | 0.319      | 0.331        | 0.001 (0.000)    | 0.022 (0.002)    | 0 (0.000) |     4.53 | Ann4, D7, KiTKaT, Nea, pullox |
|            3 |     3449 | 2024-03-13 | ENCE Athena       | L   | 0.266      | -            | -                | -                | -         |    -4.39 | Ann4, D7, KiTKaT, Nea, pullox |
|            2 |     3881 | 2024-02-24 | BIG EQUIPA        | L   | 0.145      | -            | -                | -                | -         |    -1.60 | Ann4, D7, KiTKaT, Nea, pullox |
|            1 |     4120 | 2024-02-14 | Spirit fe         | W   | 0.080      | 0.143        | 0.005 (0.000)    | 0.101 (0.001)    | 0 (0.000) |     1.26 | Ann4, D7, KiTKaT, Nea, pullox |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($841.39)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
