### Roster Details<br />
Team Name: MIGHT<br />
Roster: djay, Fr3nk1e, Nifty, scar, Snakes<br />
Global Rank: [202](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [57]( ../standings_americas.md)<br />
<br />
Final Rank Value:  511.9<br />
<br />
Final Rank Value (511.9) = Starting Rank Value (528.6) + Head To Head Adjustments (-16.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.229[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.063<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 528.6
- 400 + ( ( 0.063 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 528.6


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
|           29 |     1841 | 2024-05-22 | Limitless        | L   | 0.698      | -            | -                | -                | -         |    -4.02 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           28 |     1846 | 2024-05-22 | Limitless        | L   | 0.698      | -            | -                | -                | -         |    -4.18 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           27 |     1923 | 2024-05-20 | Take Flyte       | L   | 0.684      | -            | -                | -                | -         |    -6.64 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           26 |     1927 | 2024-05-20 | Take Flyte       | W   | 0.684      | 0.477        | 0.002 (0.001)    | 0.236 (0.077)    | 0 (0.000) |    15.31 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           25 |     2087 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.651      | -            | -                | -                | -         |    -4.49 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           24 |     2094 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.651      | -            | -                | -                | -         |    -4.67 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           23 |     2147 | 2024-05-14 | BOSS             | L   | 0.644      | -            | -                | -                | -         |    -3.49 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           22 |     2155 | 2024-05-14 | BOSS             | L   | 0.644      | -            | -                | -                | -         |    -3.60 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           21 |     2290 | 2024-05-09 | Wildcard         | L   | 0.611      | -            | -                | -                | -         |    -2.16 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           20 |     2293 | 2024-05-09 | Wildcard         | L   | 0.611      | -            | -                | -                | -         |    -2.21 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           19 |     2308 | 2024-05-08 | Elevate          | L   | 0.604      | -            | -                | -                | -         |    -1.45 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           18 |     2310 | 2024-05-08 | Elevate          | L   | 0.604      | -            | -                | -                | -         |    -1.47 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           17 |     2975 | 2024-04-10 | Phoenix          | W   | 0.418      | 0.477        | 0.004 (0.001)    | 0.277 (0.055)    | 0 (0.000) |    10.15 | danss, djay, Nifty, scar, Snakes   |
|           16 |     2980 | 2024-04-10 | Phoenix          | L   | 0.417      | -            | -                | -                | -         |    -3.01 | danss, djay, Nifty, scar, Snakes   |
|           15 |     3028 | 2024-04-09 | Nouns            | L   | 0.411      | -            | -                | -                | -         |    -1.33 | danss, djay, Louie, scar, Snakes   |
|           14 |     3032 | 2024-04-09 | Nouns            | L   | 0.411      | -            | -                | -                | -         |    -1.35 | danss, djay, Nifty, scar, Snakes   |
|           13 |     3159 | 2024-04-04 | Party Astronauts | L   | 0.378      | -            | -                | -                | -         |    -1.14 | danss, djay, Nifty, scar, Snakes   |
|           12 |     3166 | 2024-04-04 | Party Astronauts | L   | 0.378      | -            | -                | -                | -         |    -1.15 | danss, djay, Nifty, scar, Snakes   |
|           11 |     3335 | 2024-03-27 | Limitless        | L   | 0.325      | -            | -                | -                | -         |    -3.45 | danss, djay, Nifty, scar, Snakes   |
|           10 |     3341 | 2024-03-27 | Limitless        | L   | 0.324      | -            | -                | -                | -         |    -3.54 | danss, djay, Nifty, scar, Snakes   |
|            9 |     3386 | 2024-03-26 | NRG              | L   | 0.318      | -            | -                | -                | -         |    -1.50 | danss, djay, Nifty, scar, Snakes   |
|            8 |     3391 | 2024-03-26 | NRG              | L   | 0.318      | -            | -                | -                | -         |    -1.52 | danss, djay, Nifty, scar, Snakes   |
|            7 |     3791 | 2024-03-06 | LAG              | L   | 0.185      | -            | -                | -                | -         |    -0.96 | danss, djay, Nifty, scar, Snakes   |
|            6 |     3792 | 2024-03-06 | LAG              | W   | 0.184      | 0.477        | 0.012 (0.001)    | 0.385 (0.034)    | 0 (0.000) |     4.89 | danss, djay, Nifty, scar, Snakes   |
|            5 |     3830 | 2024-03-05 | Mythic           | W   | 0.178      | 0.477        | 0.010 (0.001)    | 0.291 (0.025)    | 0 (0.000) |     4.51 | danss, djay, Nifty, scar, Snakes   |
|            4 |     3832 | 2024-03-05 | Mythic           | W   | 0.178      | 0.477        | 0.010 (0.001)    | 0.291 (0.025)    | 0 (0.000) |     4.55 | danss, djay, Nifty, scar, Snakes   |
|            3 |     4081 | 2024-02-22 | Liquid           | L   | 0.097      | -            | -                | -                | -         |    -0.01 | danss, djay, Nifty, scar, Snakes   |
|            2 |     4084 | 2024-02-22 | Phoenix          | W   | 0.097      | 0.143        | 0.004 (0.000)    | 0.277 (0.004)    | 0 (0.000) |     2.33 | danss, djay, Nifty, scar, Snakes   |
|            1 |     4231 | 2024-02-16 | Rocket           | L   | 0.057      | -            | -                | -                | -         |    -1.00 | danss, djay, Nifty, scar, Snakes   |

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