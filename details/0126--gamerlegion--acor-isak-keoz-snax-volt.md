### Roster Details<br />
Team Name: GamerLegion<br />
Roster: acoR, isak, Keoz, Snax, volt<br />
Global Rank: [126](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
<br />
Final Rank Value:  791.7<br />
<br />
Final Rank Value (791.7) = Starting Rank Value (770.7) + Head To Head Adjustments (21.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.267[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.108[<sup>2</sup>](#table1)

The average of these factors is 0.181<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 770.7
- 400 + ( ( 0.181 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 770.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     3453 | 2024-03-20 | Imperial        | L   | 0.284      | -            | -                | -                | -         |    -0.60 | acoR, isak, Keoz, Snax, volt |
|           13 |     3471 | 2024-03-19 | Eternal Fire    | L   | 0.276      | -            | -                | -                | -         |    -0.05 | acoR, isak, Keoz, Snax, volt |
|           12 |     3480 | 2024-03-18 | Legacy          | W   | 0.270      | 0.143        | 0.122 (0.005)    | 0.644 (0.025)    | 1 (0.270) |     6.73 | acoR, isak, Keoz, Snax, volt |
|           11 |     3489 | 2024-03-17 | SAW             | L   | 0.266      | -            | -                | -                | -         |    -0.83 | acoR, isak, Keoz, Snax, volt |
|           10 |     3505 | 2024-03-17 | AMKAL           | W   | 0.264      | 0.143        | 0.130 (0.005)    | 0.474 (0.018)    | 1 (0.264) |     7.33 | acoR, isak, Keoz, Snax, volt |
|            9 |     3725 | 2024-03-08 | BIG             | L   | 0.204      | -            | -                | -                | -         |    -0.32 | acoR, isak, Keoz, Snax, volt |
|            8 |     4030 | 2024-02-24 | 9 Pandas        | L   | 0.117      | -            | -                | -                | -         |    -0.82 | acoR, isak, Keoz, Snax, volt |
|            7 |     4037 | 2024-02-24 | ex-Guild Eagles | W   | 0.116      | 0.143        | 0.007 (0.000)    | 0.218 (0.004)    | 1 (0.116) |     2.02 | acoR, isak, Keoz, Snax, volt |
|            6 |     4045 | 2024-02-23 | fnatic          | W   | 0.111      | 0.143        | 0.371 (0.006)    | 0.708 (0.011)    | 1 (0.111) |     3.44 | acoR, isak, Keoz, Snax, volt |
|            5 |     4063 | 2024-02-22 | HEROIC          | L   | 0.104      | -            | -                | -                | -         |    -0.04 | acoR, isak, Keoz, Snax, volt |
|            4 |     4089 | 2024-02-21 | OG              | W   | 0.097      | 0.143        | 0.138 (0.002)    | 0.127 (0.002)    | 1 (0.097) |     2.37 | acoR, isak, Keoz, Snax, volt |
|            3 |     4121 | 2024-02-20 | ENCE            | L   | 0.090      | -            | -                | -                | -         |    -0.06 | acoR, isak, Keoz, Snax, volt |
|            2 |     4142 | 2024-02-19 | PERA            | W   | 0.084      | 0.143        | 0.048 (0.001)    | 0.453 (0.005)    | 1 (0.084) |     1.88 | acoR, isak, Keoz, Snax, volt |
|            1 |     4151 | 2024-02-19 | Vitality        | L   | 0.083      | -            | -                | -                | -         |    -0.01 | acoR, isak, Keoz, Snax, volt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,937.85)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-20 |      0.285 | $10,000.00     | $2,845.83       |
| 2024-03-10 |      0.218 | $5,000.00      | $1,092.01       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
