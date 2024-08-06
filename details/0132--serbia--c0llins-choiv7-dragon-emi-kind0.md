### Roster Details<br />
Team Name: Serbia<br />
Roster: c0llins, choiv7, Dragon, emi, Kind0<br />
Global Rank: [132](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [91]( ../standings_europe.md)<br />
<br />
Final Rank Value:  779.8<br />
<br />
Final Rank Value (779.8) = Starting Rank Value (763.3) + Head To Head Adjustments (16.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.288[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 763.3
- 400 + ( ( 0.177 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 763.3


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
|           14 |      855 | 2024-07-13 | Nexus           | L   | 1.000      | -            | -                | -                | -         |   -17.94 | c0llins, choiv7, Dragon, emi, Kind0 |
|           13 |      906 | 2024-07-10 | Israel          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.038 (0.005)    | 0 (0.000) |     3.13 | c0llins, Dragon, emi, Kind0, VLDN   |
|           12 |      917 | 2024-07-09 | North Macedonia | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.11 | c0llins, choiv7, Dragon, emi, Kind0 |
|           11 |      924 | 2024-07-09 | Turkey          | L   | 1.000      | -            | -                | -                | -         |   -25.68 | c0llins, choiv7, Dragon, emi, Kind0 |
|           10 |     1477 | 2024-06-06 | Passion UA      | L   | 0.792      | -            | -                | -                | -         |    -5.06 | aidKiT, c0llins, Dragon, emi, xicoz |
|            9 |     1514 | 2024-06-05 | Enterprise      | W   | 0.787      | 0.371        | 0.039 (0.011)    | 0.641 (0.187)    | 0 (0.000) |    16.65 | aidKiT, c0llins, Dragon, emi, VLDN  |
|            8 |     1568 | 2024-06-04 | Passion UA      | L   | 0.780      | -            | -                | -                | -         |    -4.53 | aidKiT, c0llins, Dragon, emi, xicoz |
|            7 |     1613 | 2024-06-02 | brazylijski luz | W   | 0.766      | 0.371        | 0.008 (0.002)    | 0.250 (0.071)    | 0 (0.000) |    13.46 | aidKiT, c0llins, Dragon, emi, xicoz |
|            6 |     1702 | 2024-05-30 | Permitta        | W   | 0.746      | 0.371        | 0.023 (0.006)    | 0.919 (0.254)    | 0 (0.000) |    16.24 | aidKiT, c0llins, Dragon, emi, xicoz |
|            5 |     1801 | 2024-05-25 | Zero Tenacity   | L   | 0.714      | -            | -                | -                | -         |    -3.19 | aidKiT, c0llins, Dragon, emi, xicoz |
|            4 |     1809 | 2024-05-25 | UNiTY           | W   | 0.713      | 0.371        | 0.024 (0.006)    | 0.331 (0.088)    | 0 (0.000) |    16.46 | aidKiT, c0llins, Dragon, emi, xicoz |
|            3 |     1821 | 2024-05-24 | ex-Guild Eagles | L   | 0.707      | -            | -                | -                | -         |    -9.21 | aidKiT, c0llins, Dragon, emi, xicoz |
|            2 |     1923 | 2024-05-21 | kONO            | W   | 0.686      | 0.371        | 0.028 (0.007)    | 0.553 (0.141)    | 0 (0.000) |    13.49 | aidKiT, c0llins, Dragon, emi, xicoz |
|            1 |     2796 | 2024-04-18 | BetBoom         | L   | 0.468      | -            | -                | -                | -         |    -0.39 | aidKiT, c0llins, Dragon, emi, xicoz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,960.65)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
