### Roster Details<br />
Team Name: MIGHT<br />
Roster: djay, Fr3nk1e, Nifty, scar, Snakes<br />
Global Rank: [200](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [55]( ../standings_americas.md)<br />
<br />
Final Rank Value:  512.7<br />
<br />
Final Rank Value (512.7) = Starting Rank Value (528.9) + Head To Head Adjustments (-16.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.063<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 528.9
- 400 + ( ( 0.063 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 528.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |     1777 | 2024-05-22 | Limitless        | L   | 0.711      | -            | -                | -                | -         |    -4.07 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           28 |     1782 | 2024-05-22 | Limitless        | L   | 0.711      | -            | -                | -                | -         |    -4.22 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           27 |     1859 | 2024-05-20 | Take Flyte       | L   | 0.698      | -            | -                | -                | -         |    -6.85 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           26 |     1863 | 2024-05-20 | Take Flyte       | W   | 0.698      | 0.477        | 0.002 (0.001)    | 0.240 (0.080)    | 0 (0.000) |    15.53 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           25 |     2023 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.664      | -            | -                | -                | -         |    -4.70 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           24 |     2030 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.664      | -            | -                | -                | -         |    -4.90 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           23 |     2083 | 2024-05-14 | BOSS             | L   | 0.658      | -            | -                | -                | -         |    -3.60 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           22 |     2091 | 2024-05-14 | BOSS             | L   | 0.657      | -            | -                | -                | -         |    -3.72 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           21 |     2226 | 2024-05-09 | Wildcard         | L   | 0.624      | -            | -                | -                | -         |    -1.93 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           20 |     2229 | 2024-05-09 | Wildcard         | L   | 0.624      | -            | -                | -                | -         |    -1.96 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           19 |     2244 | 2024-05-08 | Elevate          | L   | 0.618      | -            | -                | -                | -         |    -1.50 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           18 |     2246 | 2024-05-08 | Elevate          | L   | 0.618      | -            | -                | -                | -         |    -1.52 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           17 |     2911 | 2024-04-10 | Perseverance     | W   | 0.431      | 0.477        | 0.004 (0.001)    | 0.244 (0.050)    | 0 (0.000) |    10.47 | danss, djay, Nifty, scar, Snakes   |
|           16 |     2916 | 2024-04-10 | Perseverance     | L   | 0.431      | -            | -                | -                | -         |    -3.11 | danss, djay, Nifty, scar, Snakes   |
|           15 |     2964 | 2024-04-09 | Nouns            | L   | 0.425      | -            | -                | -                | -         |    -1.37 | danss, djay, Louie, scar, Snakes   |
|           14 |     2968 | 2024-04-09 | Nouns            | L   | 0.424      | -            | -                | -                | -         |    -1.39 | danss, djay, Nifty, scar, Snakes   |
|           13 |     3095 | 2024-04-04 | Party Astronauts | L   | 0.391      | -            | -                | -                | -         |    -1.17 | danss, djay, Nifty, scar, Snakes   |
|           12 |     3102 | 2024-04-04 | Party Astronauts | L   | 0.391      | -            | -                | -                | -         |    -1.18 | danss, djay, Nifty, scar, Snakes   |
|           11 |     3271 | 2024-03-27 | Limitless        | L   | 0.338      | -            | -                | -                | -         |    -3.61 | danss, djay, Nifty, scar, Snakes   |
|           10 |     3277 | 2024-03-27 | Limitless        | L   | 0.338      | -            | -                | -                | -         |    -3.71 | danss, djay, Nifty, scar, Snakes   |
|            9 |     3322 | 2024-03-26 | NRG              | L   | 0.331      | -            | -                | -                | -         |    -1.58 | danss, djay, Nifty, scar, Snakes   |
|            8 |     3327 | 2024-03-26 | NRG              | L   | 0.331      | -            | -                | -                | -         |    -1.60 | danss, djay, Nifty, scar, Snakes   |
|            7 |     3727 | 2024-03-06 | LAG              | L   | 0.198      | -            | -                | -                | -         |    -0.97 | danss, djay, Nifty, scar, Snakes   |
|            6 |     3728 | 2024-03-06 | LAG              | W   | 0.198      | 0.477        | 0.012 (0.001)    | 0.341 (0.032)    | 0 (0.000) |     5.30 | danss, djay, Nifty, scar, Snakes   |
|            5 |     3766 | 2024-03-05 | Mythic           | W   | 0.191      | 0.477        | 0.010 (0.001)    | 0.300 (0.027)    | 0 (0.000) |     4.84 | danss, djay, Nifty, scar, Snakes   |
|            4 |     3768 | 2024-03-05 | Mythic           | W   | 0.191      | 0.477        | 0.010 (0.001)    | 0.300 (0.027)    | 0 (0.000) |     4.88 | danss, djay, Nifty, scar, Snakes   |
|            3 |     4017 | 2024-02-22 | Liquid           | L   | 0.111      | -            | -                | -                | -         |    -0.01 | danss, djay, Nifty, scar, Snakes   |
|            2 |     4020 | 2024-02-22 | Perseverance     | W   | 0.110      | 0.143        | 0.004 (0.000)    | 0.244 (0.004)    | 0 (0.000) |     2.65 | danss, djay, Nifty, scar, Snakes   |
|            1 |     4167 | 2024-02-16 | Rocket           | L   | 0.070      | -            | -                | -                | -         |    -1.23 | danss, djay, Nifty, scar, Snakes   |

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
