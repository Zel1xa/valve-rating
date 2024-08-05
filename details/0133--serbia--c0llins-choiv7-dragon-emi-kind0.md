### Roster Details<br />
Team Name: Serbia<br />
Roster: c0llins, choiv7, Dragon, emi, Kind0<br />
Global Rank: [133](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [92]( ../standings_europe.md)<br />
<br />
Final Rank Value:  778.2<br />
<br />
Final Rank Value (778.2) = Starting Rank Value (761.3) + Head To Head Adjustments (16.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.288[<sup>2</sup>](#table1)
- Opponent Network: 0.073[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.176<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 761.3
- 400 + ( ( 0.176 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 761.3


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
|           14 |      841 | 2024-07-13 | Nexus           | L   | 1.000      | -            | -                | -                | -         |   -18.02 | c0llins, choiv7, Dragon, emi, Kind0 |
|           13 |      892 | 2024-07-10 | Israel          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.039 (0.006)    | 0 (0.000) |     3.16 | c0llins, Dragon, emi, Kind0, VLDN   |
|           12 |      903 | 2024-07-09 | North Macedonia | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.14 | c0llins, choiv7, Dragon, emi, Kind0 |
|           11 |      910 | 2024-07-09 | Turkey          | L   | 1.000      | -            | -                | -                | -         |   -25.65 | c0llins, choiv7, Dragon, emi, Kind0 |
|           10 |     1463 | 2024-06-06 | Passion UA      | L   | 0.797      | -            | -                | -                | -         |    -5.11 | aidKiT, c0llins, Dragon, emi, xicoz |
|            9 |     1500 | 2024-06-05 | Enterprise      | W   | 0.792      | 0.371        | 0.039 (0.012)    | 0.616 (0.181)    | 0 (0.000) |    16.76 | aidKiT, c0llins, Dragon, emi, VLDN  |
|            8 |     1554 | 2024-06-04 | Passion UA      | L   | 0.785      | -            | -                | -                | -         |    -4.57 | aidKiT, c0llins, Dragon, emi, xicoz |
|            7 |     1599 | 2024-06-02 | brazylijski luz | W   | 0.772      | 0.371        | 0.008 (0.002)    | 0.257 (0.073)    | 0 (0.000) |    13.63 | aidKiT, c0llins, Dragon, emi, xicoz |
|            6 |     1688 | 2024-05-30 | Permitta        | W   | 0.752      | 0.371        | 0.024 (0.007)    | 0.863 (0.240)    | 0 (0.000) |    16.23 | aidKiT, c0llins, Dragon, emi, xicoz |
|            5 |     1787 | 2024-05-25 | Zero Tenacity   | L   | 0.719      | -            | -                | -                | -         |    -3.25 | aidKiT, c0llins, Dragon, emi, xicoz |
|            4 |     1795 | 2024-05-25 | UNiTY           | W   | 0.718      | 0.371        | 0.025 (0.007)    | 0.300 (0.080)    | 0 (0.000) |    16.65 | aidKiT, c0llins, Dragon, emi, xicoz |
|            3 |     1807 | 2024-05-24 | ex-Guild Eagles | L   | 0.712      | -            | -                | -                | -         |    -9.27 | aidKiT, c0llins, Dragon, emi, xicoz |
|            2 |     1909 | 2024-05-21 | kONO            | W   | 0.692      | 0.371        | 0.028 (0.007)    | 0.566 (0.145)    | 0 (0.000) |    13.54 | aidKiT, c0llins, Dragon, emi, xicoz |
|            1 |     2782 | 2024-04-18 | BetBoom         | L   | 0.473      | -            | -                | -                | -         |    -0.39 | aidKiT, c0llins, Dragon, emi, xicoz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,987.50)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
