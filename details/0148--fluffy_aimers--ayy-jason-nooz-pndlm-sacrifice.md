### Roster Details<br />
Team Name: FLUFFY AIMERS<br />
Roster: ayy, jason, nooz, PNDLM, sacrifice<br />
Global Rank: [148](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [40]( ../standings_americas.md)<br />
<br />
Final Rank Value:  737.6<br />
<br />
Final Rank Value (737.6) = Starting Rank Value (757.9) + Head To Head Adjustments (-20.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.332[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.114[<sup>2</sup>](#table1)

The average of these factors is 0.175<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 757.9
- 400 + ( ( 0.175 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 757.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     2128 | 2024-05-14 | Wildcard    | L   | 0.650      | -            | -                | -                | -         |    -6.19 | ayy, jason, nooz, PNDLM, sacrifice     |
|           19 |     2133 | 2024-05-14 | Wildcard    | L   | 0.650      | -            | -                | -                | -         |    -6.50 | ayy, jason, nooz, PNDLM, sacrifice     |
|           18 |     2270 | 2024-05-09 | Limitless   | W   | 0.617      | 0.477        | 0.001 (0.000)    | 0.166 (0.049)    | 0 (0.000) |     6.98 | ayy, jason, nooz, PNDLM, sacrifice     |
|           17 |     2273 | 2024-05-09 | Limitless   | L   | 0.617      | -            | -                | -                | -         |   -12.78 | ayy, jason, nooz, PNDLM, sacrifice     |
|           16 |     2652 | 2024-04-21 | For Fun     | W   | 0.497      | 0.319        | 0.003 (0.001)    | 0.020 (0.003)    | 1 (0.497) |     5.96 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           15 |     2654 | 2024-04-21 | Will to Win | W   | 0.496      | 0.319        | 0.001 (0.000)    | 0.000 (0.000)    | 1 (0.496) |     3.41 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           14 |     2956 | 2024-04-10 | Take Flyte  | L   | 0.424      | -            | -                | -                | -         |    -7.77 | ayy, intra, jason, PNDLM, sacrifice    |
|           13 |     2961 | 2024-04-10 | Take Flyte  | W   | 0.423      | 0.477        | 0.002 (0.000)    | 0.239 (0.048)    | 0 (0.000) |     5.67 | ayy, jason, nooz, PNDLM, sacrifice     |
|           12 |     3147 | 2024-04-04 | BOSS        | L   | 0.383      | -            | -                | -                | -         |    -5.31 | ayy, intra, jason, nooz, sacrifice     |
|           11 |     3153 | 2024-04-04 | BOSS        | L   | 0.383      | -            | -                | -                | -         |    -5.49 | ayy, intra, jason, PNDLM, sacrifice    |
|           10 |     3542 | 2024-03-15 | NRG         | L   | 0.251      | -            | -                | -                | -         |    -3.03 | ayy, intra, jason, PNDLM, sacrifice    |
|            9 |     3544 | 2024-03-15 | NRG         | W   | 0.250      | 0.477        | 0.020 (0.002)    | 0.520 (0.062)    | 0 (0.000) |     4.94 | ayy, intra, jason, PNDLM, sacrifice    |
|            8 |     3748 | 2024-03-07 | LAG         | L   | 0.197      | -            | -                | -                | -         |    -2.50 | ayy, jason, LEARSI, PNDLM, sacrifice   |
|            7 |     3749 | 2024-03-07 | LAG         | W   | 0.197      | 0.477        | 0.012 (0.001)    | 0.351 (0.033)    | 0 (0.000) |     3.77 | ayy, jason, LEARSI, PNDLM, sacrifice   |
|            6 |     4213 | 2024-02-16 | Mythic      | L   | 0.063      | -            | -                | -                | -         |    -0.89 | intra, jason, LEARSI, PNDLM, sacrifice |
|            5 |     4217 | 2024-02-16 | LAG         | W   | 0.063      | 0.143        | 0.012 (0.000)    | 0.351 (0.003)    | 0 (0.000) |     1.22 | intra, jason, LEARSI, PNDLM, sacrifice |
|            4 |     4271 | 2024-02-14 | Mythic      | L   | 0.051      | -            | -                | -                | -         |    -0.72 | intra, jason, LEARSI, PNDLM, sacrifice |
|            3 |     4273 | 2024-02-14 | Mythic      | L   | 0.050      | -            | -                | -                | -         |    -0.72 | intra, jason, LEARSI, PNDLM, sacrifice |
|            2 |     4312 | 2024-02-13 | Carpe Diem  | L   | 0.044      | -            | -                | -                | -         |    -0.85 | intra, jason, LEARSI, PNDLM, sacrifice |
|            1 |     4315 | 2024-02-13 | Carpe Diem  | W   | 0.044      | 0.477        | 0.005 (0.000)    | 0.037 (0.001)    | 0 (0.000) |     0.53 | intra, jason, LEARSI, PNDLM, sacrifice |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,153.56)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.823 | $1,200.00      | $987.67         |
| 2024-04-21 |      0.497 | $4,357.00      | $2,165.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
