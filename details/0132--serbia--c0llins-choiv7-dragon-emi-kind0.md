### Roster Details<br />
Team Name: Serbia<br />
Roster: c0llins, choiv7, Dragon, emi, Kind0<br />
Global Rank: [132](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [91]( ../standings_europe.md)<br />
<br />
Final Rank Value:  781.9<br />
<br />
Final Rank Value (781.9) = Starting Rank Value (765.5) + Head To Head Adjustments (16.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.292[<sup>2</sup>](#table1)
- Opponent Network: 0.074[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.178<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 765.5
- 400 + ( ( 0.178 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 765.5


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
|           14 |      866 | 2024-07-13 | Nexus           | L   | 1.000      | -            | -                | -                | -         |   -17.93 | c0llins, choiv7, Dragon, emi, Kind0 |
|           13 |      917 | 2024-07-10 | Israel          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.038 (0.005)    | 0 (0.000) |     3.10 | c0llins, Dragon, emi, Kind0, VLDN   |
|           12 |      928 | 2024-07-09 | North Macedonia | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.08 | c0llins, choiv7, Dragon, emi, Kind0 |
|           11 |      935 | 2024-07-09 | Turkey          | L   | 1.000      | -            | -                | -                | -         |   -25.74 | c0llins, choiv7, Dragon, emi, Kind0 |
|           10 |     1488 | 2024-06-06 | Passion UA      | L   | 0.791      | -            | -                | -                | -         |    -5.04 | aidKiT, c0llins, Dragon, emi, xicoz |
|            9 |     1525 | 2024-06-05 | Enterprise      | W   | 0.786      | 0.371        | 0.039 (0.011)    | 0.641 (0.187)    | 0 (0.000) |    16.61 | aidKiT, c0llins, Dragon, emi, VLDN  |
|            8 |     1579 | 2024-06-04 | Passion UA      | L   | 0.779      | -            | -                | -                | -         |    -4.51 | aidKiT, c0llins, Dragon, emi, xicoz |
|            7 |     1624 | 2024-06-02 | brazylijski luz | W   | 0.765      | 0.371        | 0.008 (0.002)    | 0.250 (0.071)    | 0 (0.000) |    13.38 | aidKiT, c0llins, Dragon, emi, xicoz |
|            6 |     1713 | 2024-05-30 | Permitta        | W   | 0.745      | 0.371        | 0.039 (0.011)    | 0.919 (0.254)    | 0 (0.000) |    16.40 | aidKiT, c0llins, Dragon, emi, xicoz |
|            5 |     1812 | 2024-05-25 | Zero Tenacity   | L   | 0.713      | -            | -                | -                | -         |    -3.17 | aidKiT, c0llins, Dragon, emi, xicoz |
|            4 |     1820 | 2024-05-25 | UNiTY           | W   | 0.712      | 0.371        | 0.024 (0.006)    | 0.331 (0.087)    | 0 (0.000) |    16.39 | aidKiT, c0llins, Dragon, emi, xicoz |
|            3 |     1832 | 2024-05-24 | ex-Guild Eagles | L   | 0.705      | -            | -                | -                | -         |    -9.16 | aidKiT, c0llins, Dragon, emi, xicoz |
|            2 |     1934 | 2024-05-21 | kONO            | W   | 0.685      | 0.371        | 0.028 (0.007)    | 0.553 (0.140)    | 0 (0.000) |    13.41 | aidKiT, c0llins, Dragon, emi, xicoz |
|            1 |     2807 | 2024-04-18 | BetBoom         | L   | 0.467      | -            | -                | -                | -         |    -0.40 | aidKiT, c0llins, Dragon, emi, xicoz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,954.86)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
