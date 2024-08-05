### Roster Details<br />
Team Name: Serbia<br />
Roster: c0llins, choiv7, Dragon, emi, Kind0<br />
Global Rank: [128](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [89]( ../standings_europe.md)<br />
<br />
Final Rank Value:  784.4<br />
<br />
Final Rank Value (784.4) = Starting Rank Value (765.3) + Head To Head Adjustments (19.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.345[<sup>1</sup>](#table2)
- Bounty Collected: 0.290[<sup>2</sup>](#table1)
- Opponent Network: 0.074[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 765.3
- 400 + ( ( 0.177 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 765.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      667 | 2024-07-13 | Nexus           | L   | 1.000      | -            | -                | -                | -         |   -18.27 | c0llins, choiv7, Dragon, emi, Kind0 |
|           13 |      718 | 2024-07-10 | Israel          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.038 (0.005)    | 0 (0.000) |     3.06 | c0llins, Dragon, emi, Kind0, VLDN   |
|           12 |      729 | 2024-07-09 | North Macedonia | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.37 | c0llins, choiv7, Dragon, emi, Kind0 |
|           11 |      736 | 2024-07-09 | Turkey          | L   | 1.000      | -            | -                | -                | -         |   -25.77 | c0llins, choiv7, Dragon, emi, Kind0 |
|           10 |     1289 | 2024-06-06 | Passion UA      | L   | 0.830      | -            | -                | -                | -         |    -5.59 | aidKiT, c0llins, Dragon, emi, xicoz |
|            9 |     1326 | 2024-06-05 | Enterprise      | W   | 0.825      | 0.371        | 0.040 (0.012)    | 0.622 (0.190)    | 0 (0.000) |    17.29 | aidKiT, c0llins, Dragon, emi, VLDN  |
|            8 |     1380 | 2024-06-04 | Passion UA      | L   | 0.818      | -            | -                | -                | -         |    -5.01 | aidKiT, c0llins, Dragon, emi, xicoz |
|            7 |     1425 | 2024-06-02 | brazylijski luz | W   | 0.804      | 0.371        | 0.008 (0.002)    | 0.264 (0.079)    | 0 (0.000) |    14.18 | aidKiT, c0llins, Dragon, emi, xicoz |
|            6 |     1514 | 2024-05-30 | Permitta        | W   | 0.784      | 0.371        | 0.024 (0.007)    | 0.799 (0.232)    | 0 (0.000) |    16.51 | aidKiT, c0llins, Dragon, emi, xicoz |
|            5 |     1613 | 2024-05-25 | Zero Tenacity   | L   | 0.752      | -            | -                | -                | -         |    -3.39 | aidKiT, c0llins, Dragon, emi, xicoz |
|            4 |     1621 | 2024-05-25 | UNiTY           | W   | 0.751      | 0.371        | 0.025 (0.007)    | 0.306 (0.085)    | 0 (0.000) |    17.26 | aidKiT, c0llins, Dragon, emi, xicoz |
|            3 |     1633 | 2024-05-24 | ex-Guild Eagles | L   | 0.744      | -            | -                | -                | -         |    -9.41 | aidKiT, c0llins, Dragon, emi, xicoz |
|            2 |     1735 | 2024-05-21 | kONO            | W   | 0.724      | 0.371        | 0.029 (0.008)    | 0.537 (0.144)    | 0 (0.000) |    14.27 | aidKiT, c0llins, Dragon, emi, xicoz |
|            1 |     2608 | 2024-04-18 | BetBoom         | L   | 0.505      | -            | -                | -                | -         |    -0.38 | aidKiT, c0llins, Dragon, emi, xicoz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,149.47)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
