### Roster Details<br />
Team Name: Smoke<br />
Roster: dok, dzt, MITHPUTTINI, s1cko, spinnie<br />
Global Rank: [132](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [35]( ../standings_americas.md)<br />
<br />
Final Rank Value:  772.8<br />
<br />
Final Rank Value (772.8) = Starting Rank Value (800.3) + Head To Head Adjustments (-27.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.126[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.195<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 800.3
- 400 + ( ( 0.195 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 800.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |       28 | 2024-07-31 | Bounty Hunters | L   | 1.000      | -            | -                | -                | -         |    -8.79 | dok, dzt, MITHPUTTINI, s1cko, spinnie |
|           21 |       73 | 2024-07-30 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -1.32 | dok, dzt, MITHPUTTINI, s1cko, spinnie |
|           20 |       77 | 2024-07-30 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -1.34 | dok, dzt, MITHPUTTINI, s1cko, spinnie |
|           19 |      160 | 2024-07-28 | Legacy         | L   | 1.000      | -            | -                | -                | -         |    -4.78 | dok, dzt, MITHPUTTINI, s1cko, spinnie |
|           18 |      469 | 2024-07-18 | Case           | L   | 1.000      | -            | -                | -                | -         |   -10.72 | dok, dzt, MITHPUTTINI, s1cko, spinnie |
|           17 |      473 | 2024-07-18 | Case           | L   | 1.000      | -            | -                | -                | -         |   -11.62 | dok, dzt, MITHPUTTINI, s1cko, spinnie |
|           16 |      533 | 2024-07-17 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -14.84 | dok, dzt, MITHPUTTINI, s1cko, spinnie |
|           15 |      539 | 2024-07-17 | Solid          | W   | 1.000      | 0.450        | 0.027 (0.012)    | 0.844 (0.380)    | 0 (0.000) |    16.75 | dok, dzt, MITHPUTTINI, s1cko, spinnie |
|           14 |      658 | 2024-07-15 | Hype           | W   | 1.000      | 0.450        | 0.025 (0.011)    | 0.512 (0.230)    | 0 (0.000) |    21.01 | dok, dzt, MITHPUTTINI, s1cko, spinnie |
|           13 |      663 | 2024-07-15 | Hype           | L   | 1.000      | -            | -                | -                | -         |   -10.08 | dok, dzt, MITHPUTTINI, s1cko, spinnie |
|           12 |     1464 | 2024-06-02 | ex-Corinthians | L   | 0.801      | -            | -                | -                | -         |   -17.85 | dok, dzt, leleo, spinnie, vhz         |
|           11 |     1490 | 2024-06-01 | Case           | L   | 0.794      | -            | -                | -                | -         |    -9.16 | dok, dzt, leleo, spinnie, vhz         |
|           10 |     1561 | 2024-05-30 | Solid          | L   | 0.780      | -            | -                | -                | -         |    -9.84 | dok, dzt, leleo, spinnie, vhz         |
|            9 |     1621 | 2024-05-27 | Vikings KR     | W   | 0.762      | 0.371        | 0.008 (0.002)    | 0.459 (0.130)    | 0 (0.000) |    11.54 | beg0d, dok, dzt, spinnie, vhz         |
|            8 |     1752 | 2024-05-22 | paiN           | W   | 0.726      | 0.450        | 0.300 (0.098)    | 0.801 (0.262)    | 0 (0.000) |    21.32 | beg0d, dok, dzt, spinnie, vhz         |
|            7 |     1753 | 2024-05-22 | paiN           | W   | 0.726      | 0.450        | 0.300 (0.098)    | 0.801 (0.262)    | 0 (0.000) |    21.64 | beg0d, dok, dzt, spinnie, vhz         |
|            6 |     1784 | 2024-05-21 | BESTIA         | L   | 0.722      | -            | -                | -                | -         |    -4.55 | beg0d, dok, dzt, spinnie, vhz         |
|            5 |     1787 | 2024-05-21 | BESTIA         | L   | 0.721      | -            | -                | -                | -         |    -4.74 | beg0d, dok, dzt, spinnie, vhz         |
|            4 |     2007 | 2024-05-15 | Fluxo          | L   | 0.682      | -            | -                | -                | -         |    -2.96 | beg0d, dok, dzt, spinnie, vhz         |
|            3 |     2008 | 2024-05-15 | Fluxo          | L   | 0.681      | -            | -                | -                | -         |    -3.04 | beg0d, dok, dzt, spinnie, vhz         |
|            2 |     2071 | 2024-05-14 | 9z             | L   | 0.675      | -            | -                | -                | -         |    -2.05 | beg0d, dok, dzt, spinnie, vhz         |
|            1 |     2075 | 2024-05-14 | 9z             | L   | 0.675      | -            | -                | -                | -         |    -2.09 | beg0d, dok, dzt, spinnie, vhz         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($762.92)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
