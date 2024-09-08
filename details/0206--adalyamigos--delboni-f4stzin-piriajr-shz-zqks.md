### Roster Details<br />
Team Name: adalYamigos<br />
Roster: delboNi, f4stzin, piriajr, shz, zqkS<br />
Global Rank: [206](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [54]( ../standings_americas.md)<br />
<br />
Final Rank Value:  536.5<br />
<br />
Final Rank Value (536.5) = Starting Rank Value (527.3) + Head To Head Adjustments (9.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.252[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.066<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 527.3
- 400 + ( ( 0.066 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 527.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     4063 | 2024-04-12 | Case     | L   | 0.210      | -            | -                | -                | -         |    -0.61 | delboNi, f4stzin, piriajr, shz, zqkS |
|            9 |     4083 | 2024-04-11 | Imperial | L   | 0.203      | -            | -                | -                | -         |    -0.32 | delboNi, f4stzin, piriajr, shz, zqkS |
|            8 |     4171 | 2024-04-09 | MIBR     | L   | 0.190      | -            | -                | -                | -         |    -0.05 | delboNi, f4stzin, piriajr, shz, zqkS |
|            7 |     4176 | 2024-04-09 | MIBR     | L   | 0.189      | -            | -                | -                | -         |    -0.05 | delboNi, f4stzin, piriajr, shz, zqkS |
|            6 |     4248 | 2024-04-07 | Case     | W   | 0.176      | 0.435        | 0.039 (0.003)    | 0.727 (0.056)    | 0 (0.000) |     5.06 | delboNi, f4stzin, piriajr, shz, zqkS |
|            5 |     4283 | 2024-04-05 | 2GAME    | L   | 0.163      | -            | -                | -                | -         |    -2.04 | delboNi, f4stzin, piriajr, shz, zqkS |
|            4 |     4284 | 2024-04-05 | 2GAME    | W   | 0.162      | 0.450        | 0.002 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     3.11 | delboNi, f4stzin, piriajr, shz, zqkS |
|            3 |     4302 | 2024-04-04 | BESTIA   | W   | 0.156      | 0.450        | 0.107 (0.008)    | 0.807 (0.057)    | 0 (0.000) |     4.51 | delboNi, f4stzin, piriajr, shz, zqkS |
|            2 |     4311 | 2024-04-04 | BESTIA   | L   | 0.156      | -            | -                | -                | -         |    -0.41 | delboNi, f4stzin, piriajr, shz, zqkS |
|            1 |     4795 | 2024-03-12 | Solid    | L   | 0.003      | -            | -                | -                | -         |    -0.03 | delboNi, f4stzin, piriajr, shz, zqkS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
