### Roster Details<br />
Team Name: Partizan<br />
Roster: c0llins, Dragon, emi, Kind0, ROGA<br />
Global Rank: [125](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [87]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  776.0<br />
<br />
Final Rank Value (776.0) = Starting Rank Value (744.1) + Head To Head Adjustments (31.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.331[<sup>1</sup>](#table2)
- Bounty Collected: 0.290[<sup>2</sup>](#table1)
- Opponent Network: 0.083[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.176<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 744.1
- 400 + ( ( 0.176 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 744.1


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
|           15 |      173 | 2024-09-01 | Rebels          | W   | 1.000      | 0.384        | 0.028 (0.011)    | 0.677 (0.260)    | 0 (0.000) |    23.91 | c0llins, Dragon, emi, Kind0, ROGA   |
|           14 |     1951 | 2024-07-13 | Nexus           | L   | 0.828      | -            | -                | -                | -         |   -14.11 | c0llins, choiv7, Dragon, emi, Kind0 |
|           13 |     2002 | 2024-07-10 | Israel          | W   | 0.808      | 0.143        | 0.000 (0.000)    | 0.031 (0.004)    | 0 (0.000) |     2.92 | c0llins, Dragon, emi, Kind0, VLDN   |
|           12 |     2013 | 2024-07-09 | North Macedonia | W   | 0.803      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.93 | c0llins, choiv7, Dragon, emi, Kind0 |
|           11 |     2020 | 2024-07-09 | Turkey          | L   | 0.802      | -            | -                | -                | -         |   -20.24 | c0llins, choiv7, Dragon, emi, Kind0 |
|           10 |     2573 | 2024-06-06 | Passion UA      | L   | 0.580      | -            | -                | -                | -         |    -3.57 | aidKiT, c0llins, Dragon, emi, xicoz |
|            9 |     2610 | 2024-06-05 | Enterprise      | W   | 0.575      | 0.371        | 0.039 (0.008)    | 0.720 (0.153)    | 0 (0.000) |    12.21 | aidKiT, c0llins, Dragon, emi, VLDN  |
|            8 |     2664 | 2024-06-04 | Passion UA      | L   | 0.568      | -            | -                | -                | -         |    -3.25 | aidKiT, c0llins, Dragon, emi, xicoz |
|            7 |     2709 | 2024-06-02 | Apogee          | W   | 0.554      | 0.371        | 0.006 (0.001)    | 0.206 (0.042)    | 0 (0.000) |     8.96 | aidKiT, c0llins, Dragon, emi, xicoz |
|            6 |     2798 | 2024-05-30 | Permitta        | W   | 0.534      | 0.371        | 0.032 (0.006)    | 0.999 (0.198)    | 0 (0.000) |    12.01 | aidKiT, c0llins, Dragon, emi, xicoz |
|            5 |     2897 | 2024-05-25 | Zero Tenacity   | L   | 0.502      | -            | -                | -                | -         |    -2.40 | aidKiT, c0llins, Dragon, emi, xicoz |
|            4 |     2905 | 2024-05-25 | UNiTY           | W   | 0.501      | 0.371        | 0.026 (0.005)    | 0.406 (0.075)    | 0 (0.000) |    11.07 | aidKiT, c0llins, Dragon, emi, xicoz |
|            3 |     2917 | 2024-05-24 | ex-Guild Eagles | L   | 0.494      | -            | -                | -                | -         |    -7.82 | aidKiT, c0llins, Dragon, emi, xicoz |
|            2 |     3019 | 2024-05-21 | kONO            | W   | 0.474      | 0.371        | 0.025 (0.004)    | 0.550 (0.097)    | 0 (0.000) |     9.68 | aidKiT, c0llins, Dragon, emi, xicoz |
|            1 |     3892 | 2024-04-18 | BetBoom         | L   | 0.255      | -            | -                | -                | -         |    -0.46 | aidKiT, c0llins, Dragon, emi, xicoz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,899.31)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
