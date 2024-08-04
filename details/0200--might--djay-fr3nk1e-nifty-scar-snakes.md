### Roster Details<br />
Team Name: MIGHT<br />
Roster: djay, Fr3nk1e, Nifty, scar, Snakes<br />
Global Rank: [200](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [55]( ../standings_americas.md)<br />
<br />
Final Rank Value:  512.9<br />
<br />
Final Rank Value (512.9) = Starting Rank Value (529.1) + Head To Head Adjustments (-16.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.063<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 529.1
- 400 + ( ( 0.063 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 529.1


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
|           29 |     1773 | 2024-05-22 | Limitless        | L   | 0.714      | -            | -                | -                | -         |    -4.08 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           28 |     1778 | 2024-05-22 | Limitless        | L   | 0.714      | -            | -                | -                | -         |    -4.24 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           27 |     1855 | 2024-05-20 | Take Flyte       | L   | 0.701      | -            | -                | -                | -         |    -6.88 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           26 |     1859 | 2024-05-20 | Take Flyte       | W   | 0.701      | 0.477        | 0.002 (0.001)    | 0.240 (0.080)    | 0 (0.000) |    15.59 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           25 |     2019 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.668      | -            | -                | -                | -         |    -4.73 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           24 |     2026 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.667      | -            | -                | -                | -         |    -4.93 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           23 |     2079 | 2024-05-14 | BOSS             | L   | 0.661      | -            | -                | -                | -         |    -3.61 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           22 |     2087 | 2024-05-14 | BOSS             | L   | 0.660      | -            | -                | -                | -         |    -3.74 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           21 |     2222 | 2024-05-09 | Wildcard         | L   | 0.627      | -            | -                | -                | -         |    -1.93 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           20 |     2225 | 2024-05-09 | Wildcard         | L   | 0.627      | -            | -                | -                | -         |    -1.97 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           19 |     2240 | 2024-05-08 | Elevate          | L   | 0.621      | -            | -                | -                | -         |    -1.50 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           18 |     2242 | 2024-05-08 | Elevate          | L   | 0.621      | -            | -                | -                | -         |    -1.53 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           17 |     2906 | 2024-04-10 | Perseverance     | W   | 0.434      | 0.477        | 0.004 (0.001)    | 0.244 (0.051)    | 0 (0.000) |    10.55 | danss, djay, Nifty, scar, Snakes   |
|           16 |     2911 | 2024-04-10 | Perseverance     | L   | 0.434      | -            | -                | -                | -         |    -3.13 | danss, djay, Nifty, scar, Snakes   |
|           15 |     2959 | 2024-04-09 | Nouns            | L   | 0.428      | -            | -                | -                | -         |    -1.38 | danss, djay, Louie, scar, Snakes   |
|           14 |     2963 | 2024-04-09 | Nouns            | L   | 0.427      | -            | -                | -                | -         |    -1.40 | danss, djay, Nifty, scar, Snakes   |
|           13 |     3090 | 2024-04-04 | Party Astronauts | L   | 0.394      | -            | -                | -                | -         |    -1.18 | danss, djay, Nifty, scar, Snakes   |
|           12 |     3097 | 2024-04-04 | Party Astronauts | L   | 0.394      | -            | -                | -                | -         |    -1.19 | danss, djay, Nifty, scar, Snakes   |
|           11 |     3266 | 2024-03-27 | Limitless        | L   | 0.341      | -            | -                | -                | -         |    -3.65 | danss, djay, Nifty, scar, Snakes   |
|           10 |     3272 | 2024-03-27 | Limitless        | L   | 0.341      | -            | -                | -                | -         |    -3.75 | danss, djay, Nifty, scar, Snakes   |
|            9 |     3317 | 2024-03-26 | NRG              | L   | 0.334      | -            | -                | -                | -         |    -1.59 | danss, djay, Nifty, scar, Snakes   |
|            8 |     3322 | 2024-03-26 | NRG              | L   | 0.334      | -            | -                | -                | -         |    -1.62 | danss, djay, Nifty, scar, Snakes   |
|            7 |     3721 | 2024-03-06 | LAG              | L   | 0.201      | -            | -                | -                | -         |    -0.98 | danss, djay, Nifty, scar, Snakes   |
|            6 |     3722 | 2024-03-06 | LAG              | W   | 0.201      | 0.477        | 0.012 (0.001)    | 0.341 (0.033)    | 0 (0.000) |     5.39 | danss, djay, Nifty, scar, Snakes   |
|            5 |     3760 | 2024-03-05 | Mythic           | W   | 0.194      | 0.477        | 0.010 (0.001)    | 0.300 (0.028)    | 0 (0.000) |     4.92 | danss, djay, Nifty, scar, Snakes   |
|            4 |     3762 | 2024-03-05 | Mythic           | W   | 0.194      | 0.477        | 0.010 (0.001)    | 0.300 (0.028)    | 0 (0.000) |     4.96 | danss, djay, Nifty, scar, Snakes   |
|            3 |     4011 | 2024-02-22 | Liquid           | L   | 0.114      | -            | -                | -                | -         |    -0.02 | danss, djay, Nifty, scar, Snakes   |
|            2 |     4014 | 2024-02-22 | Perseverance     | W   | 0.113      | 0.143        | 0.004 (0.000)    | 0.244 (0.004)    | 0 (0.000) |     2.72 | danss, djay, Nifty, scar, Snakes   |
|            1 |     4160 | 2024-02-16 | Rocket           | L   | 0.073      | -            | -                | -                | -         |    -1.28 | danss, djay, Nifty, scar, Snakes   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
