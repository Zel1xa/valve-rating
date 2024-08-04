### Roster Details<br />
Team Name: Flamengo<br />
Roster: Alisson, ALLE, caike, danoco, zock9<br />
Global Rank: [207](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [60]( ../standings_americas.md)<br />
<br />
Final Rank Value:  491.9<br />
<br />
Final Rank Value (491.9) = Starting Rank Value (495.8) + Head To Head Adjustments (-3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.186[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.047<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 495.8
- 400 + ( ( 0.047 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 495.8


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
|           12 |     3529 | 2024-03-14 | MIBR Academy  | L   | 0.250      | -            | -                | -                | -         |    -3.76 | Alisson, ALLE, caike, danoco, zock9   |
|           11 |     3539 | 2024-03-14 | RED Canids    | L   | 0.248      | -            | -                | -                | -         |    -0.28 | Alisson, ALLE, caike, danoco, zock9   |
|           10 |     3613 | 2024-03-11 | MIBR Academy  | W   | 0.230      | 0.303        | 0.000 (0.000)    | 0.024 (0.002)    | 0 (0.000) |     3.79 | Alisson, ALLE, caike, danoco, zock9   |
|            9 |     3641 | 2024-03-10 | FURIA Academy | L   | 0.222      | -            | -                | -                | -         |    -3.31 | Alisson, ALLE, danoco, voltera, zock9 |
|            8 |     3688 | 2024-03-08 | adalYamigos   | L   | 0.209      | -            | -                | -                | -         |    -2.35 | Alisson, ALLE, danoco, voltera, zock9 |
|            7 |     4072 | 2024-02-20 | Solid         | L   | 0.097      | -            | -                | -                | -         |    -0.29 | Alisson, ALLE, danoco, LUCAS1, zock9  |
|            6 |     4075 | 2024-02-20 | Sharks        | W   | 0.096      | 0.143        | 0.030 (0.000)    | 0.565 (0.008)    | 0 (0.000) |     2.84 | Alisson, ALLE, danoco, LUCAS1, zock9  |
|            5 |     4170 | 2024-02-16 | Galorys       | L   | 0.070      | -            | -                | -                | -         |    -0.20 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            4 |     4184 | 2024-02-16 | LA RUGONETA   | L   | 0.068      | -            | -                | -                | -         |    -0.94 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            3 |     4209 | 2024-02-15 | Case          | L   | 0.062      | -            | -                | -                | -         |    -0.15 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            2 |     4278 | 2024-02-13 | 9z Academy    | W   | 0.050      | 0.303        | 0.000 (0.000)    | 0.070 (0.001)    | 0 (0.000) |     0.81 | ALLE, danoco, LUCAS1, sakamoto, zock9 |
|            1 |     4294 | 2024-02-12 | Fluxo         | L   | 0.041      | -            | -                | -                | -         |    -0.06 | ALLE, danoco, LUCAS1, sakamoto, zock9 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
