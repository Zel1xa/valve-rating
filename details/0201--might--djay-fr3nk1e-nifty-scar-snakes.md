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
Final Rank Value (512.4) = Starting Rank Value (529.3) + Head To Head Adjustments (-16.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.063<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 529.3
- 400 + ( ( 0.063 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 529.3


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
|           29 |     1809 | 2024-05-22 | Limitless        | L   | 0.709      | -            | -                | -                | -         |    -4.08 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           28 |     1814 | 2024-05-22 | Limitless        | L   | 0.709      | -            | -                | -                | -         |    -4.24 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           27 |     1891 | 2024-05-20 | Take Flyte       | L   | 0.696      | -            | -                | -                | -         |    -6.79 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           26 |     1895 | 2024-05-20 | Take Flyte       | W   | 0.696      | 0.477        | 0.002 (0.001)    | 0.240 (0.080)    | 0 (0.000) |    15.54 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           25 |     2055 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.663      | -            | -                | -                | -         |    -4.67 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           24 |     2062 | 2024-05-15 | FLUFFY AIMERS    | L   | 0.662      | -            | -                | -                | -         |    -4.87 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           23 |     2115 | 2024-05-14 | BOSS             | L   | 0.656      | -            | -                | -                | -         |    -3.57 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           22 |     2123 | 2024-05-14 | BOSS             | L   | 0.655      | -            | -                | -                | -         |    -3.69 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           21 |     2258 | 2024-05-09 | Wildcard         | L   | 0.622      | -            | -                | -                | -         |    -2.20 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           20 |     2261 | 2024-05-09 | Wildcard         | L   | 0.622      | -            | -                | -                | -         |    -2.25 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           19 |     2276 | 2024-05-08 | Elevate          | L   | 0.616      | -            | -                | -                | -         |    -1.48 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           18 |     2278 | 2024-05-08 | Elevate          | L   | 0.616      | -            | -                | -                | -         |    -1.50 | djay, Fr3nk1e, Nifty, scar, Snakes |
|           17 |     2943 | 2024-04-10 | Phoenix          | W   | 0.429      | 0.477        | 0.004 (0.001)    | 0.283 (0.058)    | 0 (0.000) |    10.42 | danss, djay, Nifty, scar, Snakes   |
|           16 |     2948 | 2024-04-10 | Phoenix          | L   | 0.429      | -            | -                | -                | -         |    -3.11 | danss, djay, Nifty, scar, Snakes   |
|           15 |     2996 | 2024-04-09 | Nouns            | L   | 0.423      | -            | -                | -                | -         |    -1.37 | danss, djay, Louie, scar, Snakes   |
|           14 |     3000 | 2024-04-09 | Nouns            | L   | 0.422      | -            | -                | -                | -         |    -1.38 | danss, djay, Nifty, scar, Snakes   |
|           13 |     3127 | 2024-04-04 | Party Astronauts | L   | 0.389      | -            | -                | -                | -         |    -1.17 | danss, djay, Nifty, scar, Snakes   |
|           12 |     3134 | 2024-04-04 | Party Astronauts | L   | 0.389      | -            | -                | -                | -         |    -1.19 | danss, djay, Nifty, scar, Snakes   |
|           11 |     3303 | 2024-03-27 | Limitless        | L   | 0.336      | -            | -                | -                | -         |    -3.60 | danss, djay, Nifty, scar, Snakes   |
|           10 |     3309 | 2024-03-27 | Limitless        | L   | 0.336      | -            | -                | -                | -         |    -3.69 | danss, djay, Nifty, scar, Snakes   |
|            9 |     3354 | 2024-03-26 | NRG              | L   | 0.330      | -            | -                | -                | -         |    -1.57 | danss, djay, Nifty, scar, Snakes   |
|            8 |     3359 | 2024-03-26 | NRG              | L   | 0.329      | -            | -                | -                | -         |    -1.60 | danss, djay, Nifty, scar, Snakes   |
|            7 |     3759 | 2024-03-06 | LAG              | L   | 0.196      | -            | -                | -                | -         |    -1.02 | danss, djay, Nifty, scar, Snakes   |
|            6 |     3760 | 2024-03-06 | LAG              | W   | 0.196      | 0.477        | 0.012 (0.001)    | 0.353 (0.033)    | 0 (0.000) |     5.20 | danss, djay, Nifty, scar, Snakes   |
|            5 |     3798 | 2024-03-05 | Mythic           | W   | 0.190      | 0.477        | 0.010 (0.001)    | 0.299 (0.027)    | 0 (0.000) |     4.80 | danss, djay, Nifty, scar, Snakes   |
|            4 |     3800 | 2024-03-05 | Mythic           | W   | 0.189      | 0.477        | 0.010 (0.001)    | 0.299 (0.027)    | 0 (0.000) |     4.84 | danss, djay, Nifty, scar, Snakes   |
|            3 |     4049 | 2024-02-22 | Liquid           | L   | 0.109      | -            | -                | -                | -         |    -0.01 | danss, djay, Nifty, scar, Snakes   |
|            2 |     4052 | 2024-02-22 | Phoenix          | W   | 0.109      | 0.143        | 0.004 (0.000)    | 0.283 (0.004)    | 0 (0.000) |     2.60 | danss, djay, Nifty, scar, Snakes   |
|            1 |     4199 | 2024-02-16 | Rocket           | L   | 0.069      | -            | -                | -                | -         |    -1.20 | danss, djay, Nifty, scar, Snakes   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
