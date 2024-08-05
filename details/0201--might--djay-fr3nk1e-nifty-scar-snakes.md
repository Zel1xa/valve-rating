### Roster Details<br />
Team Name: MIGHT<br />
Roster: djay, Fr3nk1e, Nifty, scar, Snakes<br />
Global Rank: [201](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [56]( ../standings_americas.md)<br />
<br />
Final Rank Value:  512.4<br />
<br />
Final Rank Value (512.4) = Starting Rank Value (529.1) + Head To Head Adjustments (-16.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.063<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 529.1
- 400 + ( ( 0.063 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 529.1


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
|           29 |     1813 | 2024-05-22 | Limitless        | L   | 0.707      | -            | -                | -                | -         |    -4.08 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           28 |     1818 | 2024-05-22 | Limitless        | L   | 0.707      | -            | -                | -                | -         |    -4.23 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           27 |     1895 | 2024-05-20 | Take Flyte       | L   | 0.694      | -            | -                | -                | -         |    -6.76 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           26 |     1899 | 2024-05-20 | Take Flyte       | W   | 0.693      | 0.477        | 0.002 (0.001)    | 0.240 (0.079)    | 0 (0.000) |    15.48 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           25 |     2059 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.660      | -            | -                | -                | -         |    -4.57 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           24 |     2066 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.660      | -            | -                | -                | -         |    -4.75 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           23 |     2119 | 2024-05-14 | BOSS             | L   | 0.653      | -            | -                | -                | -         |    -3.56 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           22 |     2127 | 2024-05-14 | BOSS             | L   | 0.653      | -            | -                | -                | -         |    -3.68 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           21 |     2262 | 2024-05-09 | Wildcard         | L   | 0.620      | -            | -                | -                | -         |    -2.19 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           20 |     2265 | 2024-05-09 | Wildcard         | L   | 0.620      | -            | -                | -                | -         |    -2.24 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           19 |     2280 | 2024-05-08 | Elevate          | L   | 0.614      | -            | -                | -                | -         |    -1.47 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           18 |     2282 | 2024-05-08 | Elevate          | L   | 0.613      | -            | -                | -                | -         |    -1.50 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           17 |     2947 | 2024-04-10 | Phoenix          | W   | 0.427      | 0.477        | 0.004 (0.001)    | 0.283 (0.058)    | 0 (0.000) |    10.37 | danss, djay, Nifty, scar, Snakes   |
|           16 |     2952 | 2024-04-10 | Phoenix          | L   | 0.427      | -            | -                | -                | -         |    -3.08 | danss, djay, Nifty, scar, Snakes   |
|           15 |     3000 | 2024-04-09 | Nouns            | L   | 0.420      | -            | -                | -                | -         |    -1.36 | danss, djay, Louie, scar, Snakes   |
|           14 |     3004 | 2024-04-09 | Nouns            | L   | 0.420      | -            | -                | -                | -         |    -1.38 | danss, djay, Nifty, scar, Snakes   |
|           13 |     3131 | 2024-04-04 | Party Astronauts | L   | 0.387      | -            | -                | -                | -         |    -1.16 | danss, djay, Nifty, scar, Snakes   |
|           12 |     3138 | 2024-04-04 | Party Astronauts | L   | 0.387      | -            | -                | -                | -         |    -1.18 | danss, djay, Nifty, scar, Snakes   |
|           11 |     3307 | 2024-03-27 | Limitless        | L   | 0.334      | -            | -                | -                | -         |    -3.57 | danss, djay, Nifty, scar, Snakes   |
|           10 |     3313 | 2024-03-27 | Limitless        | L   | 0.334      | -            | -                | -                | -         |    -3.66 | danss, djay, Nifty, scar, Snakes   |
|            9 |     3358 | 2024-03-26 | NRG              | L   | 0.327      | -            | -                | -                | -         |    -1.55 | danss, djay, Nifty, scar, Snakes   |
|            8 |     3363 | 2024-03-26 | NRG              | L   | 0.327      | -            | -                | -                | -         |    -1.57 | danss, djay, Nifty, scar, Snakes   |
|            7 |     3763 | 2024-03-06 | LAG              | L   | 0.194      | -            | -                | -                | -         |    -1.01 | danss, djay, Nifty, scar, Snakes   |
|            6 |     3764 | 2024-03-06 | LAG              | W   | 0.194      | 0.477        | 0.012 (0.001)    | 0.353 (0.033)    | 0 (0.000) |     5.13 | danss, djay, Nifty, scar, Snakes   |
|            5 |     3802 | 2024-03-05 | Mythic           | W   | 0.187      | 0.477        | 0.010 (0.001)    | 0.299 (0.027)    | 0 (0.000) |     4.74 | danss, djay, Nifty, scar, Snakes   |
|            4 |     3804 | 2024-03-05 | Mythic           | W   | 0.187      | 0.477        | 0.010 (0.001)    | 0.299 (0.027)    | 0 (0.000) |     4.78 | danss, djay, Nifty, scar, Snakes   |
|            3 |     4053 | 2024-02-22 | Liquid           | L   | 0.106      | -            | -                | -                | -         |    -0.01 | danss, djay, Nifty, scar, Snakes   |
|            2 |     4056 | 2024-02-22 | Phoenix          | W   | 0.106      | 0.143        | 0.004 (0.000)    | 0.283 (0.004)    | 0 (0.000) |     2.55 | danss, djay, Nifty, scar, Snakes   |
|            1 |     4203 | 2024-02-16 | Rocket           | L   | 0.066      | -            | -                | -                | -         |    -1.16 | danss, djay, Nifty, scar, Snakes   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
