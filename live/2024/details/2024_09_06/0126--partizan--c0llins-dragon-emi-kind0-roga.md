### Roster Details<br />
Team Name: Partizan<br />
Roster: c0llins, Dragon, emi, Kind0, ROGA<br />
Global Rank: [126](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [87]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  776.2<br />
<br />
Final Rank Value (776.2) = Starting Rank Value (744.3) + Head To Head Adjustments (32.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.331[<sup>1</sup>](#table2)
- Bounty Collected: 0.291[<sup>2</sup>](#table1)
- Opponent Network: 0.083[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.176<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 744.3
- 400 + ( ( 0.176 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 744.3


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
|           15 |      168 | 2024-09-01 | Rebels          | W   | 1.000      | 0.384        | 0.028 (0.011)    | 0.677 (0.260)    | 0 (0.000) |    23.91 | c0llins, Dragon, emi, Kind0, ROGA   |
|           14 |     1946 | 2024-07-13 | Nexus           | L   | 0.832      | -            | -                | -                | -         |   -14.19 | c0llins, choiv7, Dragon, emi, Kind0 |
|           13 |     1997 | 2024-07-10 | Israel          | W   | 0.812      | 0.143        | 0.000 (0.000)    | 0.031 (0.004)    | 0 (0.000) |     2.93 | c0llins, Dragon, emi, Kind0, VLDN   |
|           12 |     2008 | 2024-07-09 | North Macedonia | W   | 0.807      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.94 | c0llins, choiv7, Dragon, emi, Kind0 |
|           11 |     2015 | 2024-07-09 | Turkey          | L   | 0.806      | -            | -                | -                | -         |   -20.34 | c0llins, choiv7, Dragon, emi, Kind0 |
|           10 |     2568 | 2024-06-06 | Passion UA      | L   | 0.584      | -            | -                | -                | -         |    -3.60 | aidKiT, c0llins, Dragon, emi, xicoz |
|            9 |     2605 | 2024-06-05 | Enterprise      | W   | 0.579      | 0.371        | 0.039 (0.008)    | 0.720 (0.154)    | 0 (0.000) |    12.30 | aidKiT, c0llins, Dragon, emi, VLDN  |
|            8 |     2659 | 2024-06-04 | Passion UA      | L   | 0.572      | -            | -                | -                | -         |    -3.27 | aidKiT, c0llins, Dragon, emi, xicoz |
|            7 |     2704 | 2024-06-02 | Apogee          | W   | 0.558      | 0.371        | 0.006 (0.001)    | 0.207 (0.043)    | 0 (0.000) |     9.04 | aidKiT, c0llins, Dragon, emi, xicoz |
|            6 |     2793 | 2024-05-30 | Permitta        | W   | 0.538      | 0.371        | 0.032 (0.006)    | 0.998 (0.199)    | 0 (0.000) |    12.08 | aidKiT, c0llins, Dragon, emi, xicoz |
|            5 |     2892 | 2024-05-25 | Zero Tenacity   | L   | 0.506      | -            | -                | -                | -         |    -2.42 | aidKiT, c0llins, Dragon, emi, xicoz |
|            4 |     2900 | 2024-05-25 | UNiTY           | W   | 0.505      | 0.371        | 0.026 (0.005)    | 0.406 (0.076)    | 0 (0.000) |    11.16 | aidKiT, c0llins, Dragon, emi, xicoz |
|            3 |     2912 | 2024-05-24 | ex-Guild Eagles | L   | 0.498      | -            | -                | -                | -         |    -7.87 | aidKiT, c0llins, Dragon, emi, xicoz |
|            2 |     3014 | 2024-05-21 | kONO            | W   | 0.478      | 0.371        | 0.025 (0.004)    | 0.550 (0.097)    | 0 (0.000) |     9.76 | aidKiT, c0llins, Dragon, emi, xicoz |
|            1 |     3887 | 2024-04-18 | BetBoom         | L   | 0.259      | -            | -                | -                | -         |    -0.46 | aidKiT, c0llins, Dragon, emi, xicoz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,919.33)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
