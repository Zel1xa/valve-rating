### Roster Details<br />
Team Name: Let Her Cook<br />
Roster: ASTRA, Joanana, ManeschijnX, meli, RacheLL<br />
Global Rank: [82](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [61]( ../standings_europe.md)<br />
<br />
Final Rank Value:  927.3<br />
<br />
Final Rank Value (927.3) = Starting Rank Value (930.4) + Head To Head Adjustments (-3.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.451[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.265[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.4
- 400 + ( ( 0.259 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 930.4


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
|           16 |     1532 | 2024-06-02 | Imperial fe       | L   | 0.782      | -            | -                | -                | -         |    -8.26 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           15 |     1535 | 2024-06-02 | HSG fe            | W   | 0.782      | 0.524        | 0.031 (0.013)    | 0.070 (0.029)    | 1 (0.782) |     9.42 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           14 |     1593 | 2024-05-31 | panelinha         | W   | 0.770      | 0.524        | 0.032 (0.013)    | 0.154 (0.062)    | 1 (0.770) |    10.27 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           13 |     1599 | 2024-05-31 | NAVI Javelins     | W   | 0.768      | 0.524        | 0.026 (0.011)    | 0.189 (0.076)    | 1 (0.768) |    10.69 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           12 |     2646 | 2024-04-20 | Astralis W        | W   | 0.494      | 0.331        | 0.002 (0.000)    | 0.064 (0.010)    | 0 (0.000) |     3.26 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           11 |     2683 | 2024-04-19 | Spirit fe         | W   | 0.488      | 0.331        | 0.005 (0.001)    | 0.141 (0.023)    | 0 (0.000) |     2.97 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           10 |     2901 | 2024-04-11 | NIP Impact        | L   | 0.434      | -            | -                | -                | -         |   -10.12 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            9 |     2946 | 2024-04-10 | 1WIN Gang         | L   | 0.428      | -            | -                | -                | -         |   -11.03 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            8 |     3002 | 2024-04-09 | Spirit fe         | W   | 0.421      | 0.303        | 0.005 (0.001)    | 0.141 (0.018)    | 0 (0.000) |     2.49 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            7 |     3086 | 2024-04-06 | Fearless Cheetahs | L   | 0.400      | -            | -                | -                | -         |    -9.89 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            6 |     3172 | 2024-04-03 | NAVI Javelins     | W   | 0.381      | 0.331        | 0.026 (0.003)    | 0.189 (0.024)    | 0 (0.000) |     4.39 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            5 |     3392 | 2024-03-21 | Fearless Cheetahs | L   | 0.295      | -            | -                | -                | -         |    -7.45 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            4 |     3575 | 2024-03-13 | Crescent fe       | W   | 0.242      | 0.331        | 0.005 (0.000)    | 0.078 (0.006)    | 0 (0.000) |     1.41 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            3 |     3576 | 2024-03-13 | Crescent fe       | W   | 0.242      | 0.331        | 0.005 (0.000)    | 0.078 (0.006)    | 0 (0.000) |     1.40 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            2 |     3973 | 2024-02-25 | BIG EQUIPA        | L   | 0.126      | -            | -                | -                | -         |    -2.83 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            1 |     4005 | 2024-02-24 | Nemesis fe        | W   | 0.120      | 0.238        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.18 | Joanana, kezziwow, meli, RacheLL, suns1de  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,558.45)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
