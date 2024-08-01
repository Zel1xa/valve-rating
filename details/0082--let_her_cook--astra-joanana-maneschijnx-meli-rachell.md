### Roster Details<br />
Team Name: Let Her Cook<br />
Roster: ASTRA, Joanana, ManeschijnX, meli, RacheLL<br />
Global Rank: [82](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [60]( ../standings_europe.md)<br />
<br />
Final Rank Value:  926.9<br />
<br />
Final Rank Value (926.9) = Starting Rank Value (939.8) + Head To Head Adjustments (-12.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.452[<sup>1</sup>](#table2)
- Bounty Collected: 0.298[<sup>2</sup>](#table1)
- Opponent Network: 0.026[<sup>2</sup>](#table1)
- LAN Wins: 0.274[<sup>2</sup>](#table1)

The average of these factors is 0.262<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 939.8
- 400 + ( ( 0.262 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 939.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |     1464 | 2024-06-02 | Imperial fe       | L   | 0.801      | -            | -                | -                | -         |    -8.16 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           15 |     1468 | 2024-06-02 | HSG fe            | W   | 0.800      | 0.524        | 0.032 (0.013)    | 0.070 (0.030)    | 1 (0.800) |     9.91 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           14 |     1526 | 2024-05-31 | panelinha         | W   | 0.788      | 0.524        | 0.033 (0.013)    | 0.158 (0.065)    | 1 (0.788) |    10.86 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           13 |     1532 | 2024-05-31 | NAVI Javelins     | W   | 0.787      | 0.524        | 0.027 (0.011)    | 0.210 (0.087)    | 1 (0.787) |    11.57 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           12 |     2627 | 2024-04-20 | ex-GUILD fe       | W   | 0.512      | 0.331        | 0.003 (0.000)    | 0.066 (0.011)    | 0 (0.000) |     3.47 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           11 |     2665 | 2024-04-19 | Spirit fe         | W   | 0.507      | 0.331        | 0.005 (0.001)    | 0.101 (0.017)    | 0 (0.000) |     3.08 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           10 |     2866 | 2024-04-12 | NAVI Javelins     | L   | 0.459      | -            | -                | -                | -         |    -8.66 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            9 |     2887 | 2024-04-11 | NIP Impact        | L   | 0.453      | -            | -                | -                | -         |   -10.61 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            8 |     2932 | 2024-04-10 | 1WIN Gang         | L   | 0.447      | -            | -                | -                | -         |   -11.56 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            7 |     2988 | 2024-04-09 | Spirit fe         | W   | 0.440      | 0.303        | 0.005 (0.001)    | 0.101 (0.013)    | 0 (0.000) |     2.49 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            6 |     3072 | 2024-04-06 | Fearless Cheetahs | L   | 0.418      | -            | -                | -                | -         |   -10.38 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            5 |     3160 | 2024-04-03 | NAVI Javelins     | W   | 0.400      | 0.331        | 0.027 (0.004)    | 0.210 (0.028)    | 0 (0.000) |     4.63 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            4 |     3391 | 2024-03-21 | Fearless Cheetahs | L   | 0.313      | -            | -                | -                | -         |    -7.95 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            3 |     3578 | 2024-03-13 | Crescent fe       | W   | 0.260      | 0.331        | 0.005 (0.000)    | 0.079 (0.007)    | 0 (0.000) |     1.48 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            2 |     3987 | 2024-02-25 | BIG EQUIPA        | L   | 0.145      | -            | -                | -                | -         |    -3.27 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            1 |     4021 | 2024-02-24 | Nemesis fe        | W   | 0.139      | 0.238        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.20 | Joanana, kezziwow, meli, RacheLL, suns1de  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,020.83)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
