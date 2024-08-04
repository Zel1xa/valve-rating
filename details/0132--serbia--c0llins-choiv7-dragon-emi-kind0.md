### Roster Details<br />
Team Name: Serbia<br />
Roster: c0llins, choiv7, Dragon, emi, Kind0<br />
Global Rank: [132](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [92]( ../standings_europe.md)<br />
<br />
Final Rank Value:  778.1<br />
<br />
Final Rank Value (778.1) = Starting Rank Value (761.0) + Head To Head Adjustments (17.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.289[<sup>2</sup>](#table1)
- Opponent Network: 0.073[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 761.0
- 400 + ( ( 0.177 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 761.0


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
|           14 |      816 | 2024-07-13 | Nexus           | L   | 1.000      | -            | -                | -                | -         |   -18.07 | c0llins, choiv7, Dragon, emi, Kind0 |
|           13 |      867 | 2024-07-10 | Israel          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.039 (0.006)    | 0 (0.000) |     3.16 | c0llins, Dragon, emi, Kind0, VLDN   |
|           12 |      878 | 2024-07-09 | North Macedonia | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.14 | c0llins, choiv7, Dragon, emi, Kind0 |
|           11 |      885 | 2024-07-09 | Turkey          | L   | 1.000      | -            | -                | -                | -         |   -25.66 | c0llins, choiv7, Dragon, emi, Kind0 |
|           10 |     1438 | 2024-06-06 | Passion UA      | L   | 0.804      | -            | -                | -                | -         |    -5.22 | aidKiT, c0llins, Dragon, emi, xicoz |
|            9 |     1475 | 2024-06-05 | Enterprise      | W   | 0.799      | 0.371        | 0.039 (0.012)    | 0.625 (0.185)    | 0 (0.000) |    16.82 | aidKiT, c0llins, Dragon, emi, VLDN  |
|            8 |     1529 | 2024-06-04 | Passion UA      | L   | 0.792      | -            | -                | -                | -         |    -4.67 | aidKiT, c0llins, Dragon, emi, xicoz |
|            7 |     1574 | 2024-06-02 | brazylijski luz | W   | 0.778      | 0.371        | 0.008 (0.002)    | 0.261 (0.075)    | 0 (0.000) |    13.78 | aidKiT, c0llins, Dragon, emi, xicoz |
|            6 |     1663 | 2024-05-30 | Permitta        | W   | 0.758      | 0.371        | 0.024 (0.007)    | 0.876 (0.246)    | 0 (0.000) |    16.34 | aidKiT, c0llins, Dragon, emi, xicoz |
|            5 |     1762 | 2024-05-25 | Zero Tenacity   | L   | 0.726      | -            | -                | -                | -         |    -3.28 | aidKiT, c0llins, Dragon, emi, xicoz |
|            4 |     1770 | 2024-05-25 | UNiTY           | W   | 0.725      | 0.371        | 0.025 (0.007)    | 0.305 (0.082)    | 0 (0.000) |    16.79 | aidKiT, c0llins, Dragon, emi, xicoz |
|            3 |     1782 | 2024-05-24 | ex-Guild Eagles | L   | 0.719      | -            | -                | -                | -         |    -9.33 | aidKiT, c0llins, Dragon, emi, xicoz |
|            2 |     1884 | 2024-05-21 | kONO            | W   | 0.698      | 0.371        | 0.028 (0.007)    | 0.536 (0.139)    | 0 (0.000) |    13.70 | aidKiT, c0llins, Dragon, emi, xicoz |
|            1 |     2757 | 2024-04-18 | BetBoom         | L   | 0.480      | -            | -                | -                | -         |    -0.39 | aidKiT, c0llins, Dragon, emi, xicoz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,021.64)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />