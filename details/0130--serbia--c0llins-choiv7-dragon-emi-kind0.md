### Roster Details<br />
Team Name: Serbia<br />
Roster: c0llins, choiv7, Dragon, emi, Kind0<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [91]( ../standings_europe.md)<br />
<br />
Final Rank Value:  778.0<br />
<br />
Final Rank Value (778.0) = Starting Rank Value (761.1) + Head To Head Adjustments (16.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.289[<sup>2</sup>](#table1)
- Opponent Network: 0.073[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 761.1
- 400 + ( ( 0.177 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 761.1


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
|           14 |      792 | 2024-07-13 | Nexus           | L   | 1.000      | -            | -                | -                | -         |   -18.07 | c0llins, choiv7, Dragon, emi, Kind0 |
|           13 |      843 | 2024-07-10 | Israel          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.039 (0.006)    | 0 (0.000) |     3.16 | c0llins, Dragon, emi, Kind0, VLDN   |
|           12 |      854 | 2024-07-09 | North Macedonia | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.14 | c0llins, choiv7, Dragon, emi, Kind0 |
|           11 |      861 | 2024-07-09 | Turkey          | L   | 1.000      | -            | -                | -                | -         |   -25.66 | c0llins, choiv7, Dragon, emi, Kind0 |
|           10 |     1414 | 2024-06-06 | Passion UA      | L   | 0.805      | -            | -                | -                | -         |    -5.30 | aidKiT, c0llins, Dragon, emi, xicoz |
|            9 |     1451 | 2024-06-05 | Enterprise      | W   | 0.800      | 0.371        | 0.039 (0.012)    | 0.625 (0.185)    | 0 (0.000) |    16.82 | aidKiT, c0llins, Dragon, emi, VLDN  |
|            8 |     1505 | 2024-06-04 | Passion UA      | L   | 0.793      | -            | -                | -                | -         |    -4.75 | aidKiT, c0llins, Dragon, emi, xicoz |
|            7 |     1550 | 2024-06-02 | brazylijski luz | W   | 0.779      | 0.371        | 0.008 (0.002)    | 0.262 (0.076)    | 0 (0.000) |    13.76 | aidKiT, c0llins, Dragon, emi, xicoz |
|            6 |     1639 | 2024-05-30 | Permitta        | W   | 0.759      | 0.371        | 0.024 (0.007)    | 0.876 (0.246)    | 0 (0.000) |    16.33 | aidKiT, c0llins, Dragon, emi, xicoz |
|            5 |     1738 | 2024-05-25 | Zero Tenacity   | L   | 0.727      | -            | -                | -                | -         |    -3.27 | aidKiT, c0llins, Dragon, emi, xicoz |
|            4 |     1746 | 2024-05-25 | UNiTY           | W   | 0.726      | 0.371        | 0.025 (0.007)    | 0.305 (0.082)    | 0 (0.000) |    16.70 | aidKiT, c0llins, Dragon, emi, xicoz |
|            3 |     1758 | 2024-05-24 | ex-Guild Eagles | L   | 0.720      | -            | -                | -                | -         |    -9.29 | aidKiT, c0llins, Dragon, emi, xicoz |
|            2 |     1860 | 2024-05-21 | kONO            | W   | 0.699      | 0.371        | 0.028 (0.007)    | 0.536 (0.139)    | 0 (0.000) |    13.72 | aidKiT, c0llins, Dragon, emi, xicoz |
|            1 |     2733 | 2024-04-18 | BetBoom         | L   | 0.481      | -            | -                | -                | -         |    -0.39 | aidKiT, c0llins, Dragon, emi, xicoz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,026.97)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
