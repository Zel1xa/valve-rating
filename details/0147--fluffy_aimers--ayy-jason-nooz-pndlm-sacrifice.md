### Roster Details<br />
Team Name: FLUFFY AIMERS<br />
Roster: ayy, jason, nooz, PNDLM, sacrifice<br />
Global Rank: [147](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [40]( ../standings_americas.md)<br />
<br />
Final Rank Value:  737.8<br />
<br />
Final Rank Value (737.8) = Starting Rank Value (758.3) + Head To Head Adjustments (-20.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.332[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.115[<sup>2</sup>](#table1)

The average of these factors is 0.175<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 758.3
- 400 + ( ( 0.175 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 758.3


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
|           20 |     2115 | 2024-05-14 | Wildcard    | L   | 0.654      | -            | -                | -                | -         |    -6.21 | ayy, jason, nooz, PNDLM, sacrifice     |
|           19 |     2120 | 2024-05-14 | Wildcard    | L   | 0.653      | -            | -                | -                | -         |    -6.52 | ayy, jason, nooz, PNDLM, sacrifice     |
|           18 |     2257 | 2024-05-09 | Limitless   | W   | 0.621      | 0.477        | 0.001 (0.000)    | 0.167 (0.049)    | 0 (0.000) |     7.01 | ayy, jason, nooz, PNDLM, sacrifice     |
|           17 |     2260 | 2024-05-09 | Limitless   | L   | 0.620      | -            | -                | -                | -         |   -12.86 | ayy, jason, nooz, PNDLM, sacrifice     |
|           16 |     2639 | 2024-04-21 | For Fun     | W   | 0.500      | 0.319        | 0.003 (0.001)    | 0.020 (0.003)    | 1 (0.500) |     5.99 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           15 |     2641 | 2024-04-21 | Will to Win | W   | 0.499      | 0.319        | 0.001 (0.000)    | 0.000 (0.000)    | 1 (0.499) |     3.43 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           14 |     2943 | 2024-04-10 | Take Flyte  | L   | 0.427      | -            | -                | -                | -         |    -7.84 | ayy, intra, jason, PNDLM, sacrifice    |
|           13 |     2948 | 2024-04-10 | Take Flyte  | W   | 0.427      | 0.477        | 0.002 (0.000)    | 0.240 (0.049)    | 0 (0.000) |     5.71 | ayy, jason, nooz, PNDLM, sacrifice     |
|           12 |     3134 | 2024-04-04 | BOSS        | L   | 0.387      | -            | -                | -                | -         |    -5.35 | ayy, intra, jason, nooz, sacrifice     |
|           11 |     3140 | 2024-04-04 | BOSS        | L   | 0.386      | -            | -                | -                | -         |    -5.53 | ayy, intra, jason, PNDLM, sacrifice    |
|           10 |     3529 | 2024-03-15 | NRG         | L   | 0.254      | -            | -                | -                | -         |    -3.08 | ayy, intra, jason, PNDLM, sacrifice    |
|            9 |     3531 | 2024-03-15 | NRG         | W   | 0.254      | 0.477        | 0.020 (0.002)    | 0.521 (0.063)    | 0 (0.000) |     5.00 | ayy, intra, jason, PNDLM, sacrifice    |
|            8 |     3735 | 2024-03-07 | LAG         | L   | 0.201      | -            | -                | -                | -         |    -2.54 | ayy, jason, LEARSI, PNDLM, sacrifice   |
|            7 |     3736 | 2024-03-07 | LAG         | W   | 0.200      | 0.477        | 0.012 (0.001)    | 0.353 (0.034)    | 0 (0.000) |     3.83 | ayy, jason, LEARSI, PNDLM, sacrifice   |
|            6 |     4200 | 2024-02-16 | Mythic      | L   | 0.066      | -            | -                | -                | -         |    -0.94 | intra, jason, LEARSI, PNDLM, sacrifice |
|            5 |     4204 | 2024-02-16 | LAG         | W   | 0.066      | 0.143        | 0.012 (0.000)    | 0.353 (0.003)    | 0 (0.000) |     1.28 | intra, jason, LEARSI, PNDLM, sacrifice |
|            4 |     4258 | 2024-02-14 | Mythic      | L   | 0.054      | -            | -                | -                | -         |    -0.77 | intra, jason, LEARSI, PNDLM, sacrifice |
|            3 |     4260 | 2024-02-14 | Mythic      | L   | 0.054      | -            | -                | -                | -         |    -0.77 | intra, jason, LEARSI, PNDLM, sacrifice |
|            2 |     4299 | 2024-02-13 | Carpe Diem  | L   | 0.047      | -            | -                | -                | -         |    -0.92 | intra, jason, LEARSI, PNDLM, sacrifice |
|            1 |     4302 | 2024-02-13 | Carpe Diem  | W   | 0.047      | 0.477        | 0.005 (0.000)    | 0.038 (0.001)    | 0 (0.000) |     0.57 | intra, jason, LEARSI, PNDLM, sacrifice |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,172.08)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.826 | $1,200.00      | $991.67         |
| 2024-04-21 |      0.500 | $4,357.00      | $2,180.42       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
