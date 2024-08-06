### Roster Details<br />
Team Name: Flamengo<br />
Roster: Alisson, ALLE, caike, danoco, zock9<br />
Global Rank: [206](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [61]( ../standings_americas.md)<br />
<br />
Final Rank Value:  491.0<br />
<br />
Final Rank Value (491.0) = Starting Rank Value (494.9) + Head To Head Adjustments (-3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.184[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.046<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 494.9
- 400 + ( ( 0.046 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 494.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     3593 | 2024-03-14 | MIBR Academy  | L   | 0.236      | -            | -                | -                | -         |    -3.56 | Alisson, ALLE, caike, danoco, zock9   |
|           11 |     3603 | 2024-03-14 | RED Canids    | L   | 0.235      | -            | -                | -                | -         |    -0.27 | Alisson, ALLE, caike, danoco, zock9   |
|           10 |     3677 | 2024-03-11 | MIBR Academy  | W   | 0.216      | 0.303        | 0.000 (0.000)    | 0.022 (0.001)    | 0 (0.000) |     3.57 | Alisson, ALLE, caike, danoco, zock9   |
|            9 |     3705 | 2024-03-10 | FURIA Academy | L   | 0.209      | -            | -                | -                | -         |    -3.12 | Alisson, ALLE, danoco, voltera, zock9 |
|            8 |     3752 | 2024-03-08 | adalYamigos   | L   | 0.195      | -            | -                | -                | -         |    -2.24 | Alisson, ALLE, danoco, voltera, zock9 |
|            7 |     4136 | 2024-02-20 | Solid         | L   | 0.083      | -            | -                | -                | -         |    -0.25 | Alisson, ALLE, danoco, LUCAS1, zock9  |
|            6 |     4139 | 2024-02-20 | Sharks        | W   | 0.083      | 0.143        | 0.030 (0.000)    | 0.558 (0.007)    | 0 (0.000) |     2.45 | Alisson, ALLE, danoco, LUCAS1, zock9  |
|            5 |     4234 | 2024-02-16 | Galorys       | L   | 0.057      | -            | -                | -                | -         |    -0.17 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            4 |     4248 | 2024-02-16 | LA RUGONETA   | L   | 0.054      | -            | -                | -                | -         |    -0.76 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            3 |     4273 | 2024-02-15 | Case          | L   | 0.048      | -            | -                | -                | -         |    -0.12 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            2 |     4342 | 2024-02-13 | 9z Academy    | W   | 0.036      | 0.303        | 0.000 (0.000)    | 0.069 (0.001)    | 0 (0.000) |     0.59 | ALLE, danoco, LUCAS1, sakamoto, zock9 |
|            1 |     4358 | 2024-02-12 | Fluxo         | L   | 0.028      | -            | -                | -                | -         |    -0.04 | ALLE, danoco, LUCAS1, sakamoto, zock9 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
