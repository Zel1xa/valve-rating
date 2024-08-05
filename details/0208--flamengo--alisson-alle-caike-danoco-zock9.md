### Roster Details<br />
Team Name: Flamengo<br />
Roster: Alisson, ALLE, caike, danoco, zock9<br />
Global Rank: [208](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [61]( ../standings_americas.md)<br />
<br />
Final Rank Value:  491.4<br />
<br />
Final Rank Value (491.4) = Starting Rank Value (495.3) + Head To Head Adjustments (-3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.185[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.047<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 495.3
- 400 + ( ( 0.047 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 495.3


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
|           12 |     3578 | 2024-03-14 | MIBR Academy  | L   | 0.242      | -            | -                | -                | -         |    -3.65 | Alisson, ALLE, caike, danoco, zock9   |
|           11 |     3588 | 2024-03-14 | RED Canids    | L   | 0.241      | -            | -                | -                | -         |    -0.27 | Alisson, ALLE, caike, danoco, zock9   |
|           10 |     3662 | 2024-03-11 | MIBR Academy  | W   | 0.222      | 0.303        | 0.000 (0.000)    | 0.023 (0.002)    | 0 (0.000) |     3.67 | Alisson, ALLE, caike, danoco, zock9   |
|            9 |     3690 | 2024-03-10 | FURIA Academy | L   | 0.215      | -            | -                | -                | -         |    -3.20 | Alisson, ALLE, danoco, voltera, zock9 |
|            8 |     3737 | 2024-03-08 | adalYamigos   | L   | 0.201      | -            | -                | -                | -         |    -2.29 | Alisson, ALLE, danoco, voltera, zock9 |
|            7 |     4121 | 2024-02-20 | Solid         | L   | 0.089      | -            | -                | -                | -         |    -0.26 | Alisson, ALLE, danoco, LUCAS1, zock9  |
|            6 |     4124 | 2024-02-20 | Sharks        | W   | 0.089      | 0.143        | 0.030 (0.000)    | 0.565 (0.007)    | 0 (0.000) |     2.62 | Alisson, ALLE, danoco, LUCAS1, zock9  |
|            5 |     4219 | 2024-02-16 | Galorys       | L   | 0.062      | -            | -                | -                | -         |    -0.18 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            4 |     4233 | 2024-02-16 | LA RUGONETA   | L   | 0.060      | -            | -                | -                | -         |    -0.84 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            3 |     4258 | 2024-02-15 | Case          | L   | 0.054      | -            | -                | -                | -         |    -0.13 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            2 |     4327 | 2024-02-13 | 9z Academy    | W   | 0.042      | 0.303        | 0.000 (0.000)    | 0.070 (0.001)    | 0 (0.000) |     0.69 | ALLE, danoco, LUCAS1, sakamoto, zock9 |
|            1 |     4343 | 2024-02-12 | Fluxo         | L   | 0.034      | -            | -                | -                | -         |    -0.05 | ALLE, danoco, LUCAS1, sakamoto, zock9 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
