### Roster Details<br />
Team Name: Let Her Cook<br />
Roster: ASTRA, Joanana, ManeschijnX, meli, RacheLL<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  926.0<br />
<br />
Final Rank Value (926.0) = Starting Rank Value (930.2) + Head To Head Adjustments (-4.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.451[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.266[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.2
- 400 + ( ( 0.259 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 930.2


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
|           15 |     1520 | 2024-06-02 | Imperial fe       | L   | 0.786      | -            | -                | -                | -         |    -8.24 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           14 |     1523 | 2024-06-02 | HSG fe            | W   | 0.785      | 0.524        | 0.031 (0.013)    | 0.070 (0.029)    | 1 (0.785) |     9.52 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           13 |     1581 | 2024-05-31 | panelinha         | W   | 0.773      | 0.524        | 0.032 (0.013)    | 0.155 (0.063)    | 1 (0.773) |    10.39 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           12 |     1587 | 2024-05-31 | NAVI Javelins     | W   | 0.772      | 0.524        | 0.026 (0.011)    | 0.190 (0.077)    | 1 (0.772) |    10.81 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           11 |     2633 | 2024-04-20 | Astralis W        | W   | 0.498      | 0.331        | 0.002 (0.000)    | 0.064 (0.011)    | 0 (0.000) |     3.31 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           10 |     2670 | 2024-04-19 | Spirit fe         | W   | 0.492      | 0.331        | 0.005 (0.001)    | 0.140 (0.023)    | 0 (0.000) |     3.01 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|            9 |     2888 | 2024-04-11 | NIP Impact        | L   | 0.438      | -            | -                | -                | -         |   -10.18 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            8 |     2933 | 2024-04-10 | 1WIN Gang         | L   | 0.432      | -            | -                | -                | -         |   -11.11 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            7 |     2989 | 2024-04-09 | Spirit fe         | W   | 0.425      | 0.303        | 0.005 (0.001)    | 0.140 (0.018)    | 0 (0.000) |     2.53 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            6 |     3073 | 2024-04-06 | Fearless Cheetahs | L   | 0.403      | -            | -                | -                | -         |    -9.96 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            5 |     3159 | 2024-04-03 | NAVI Javelins     | W   | 0.385      | 0.331        | 0.026 (0.003)    | 0.190 (0.024)    | 0 (0.000) |     4.46 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            4 |     3379 | 2024-03-21 | Fearless Cheetahs | L   | 0.299      | -            | -                | -                | -         |    -7.53 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            3 |     3562 | 2024-03-13 | Crescent fe       | W   | 0.245      | 0.331        | 0.005 (0.000)    | 0.078 (0.006)    | 0 (0.000) |     1.44 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            2 |     3959 | 2024-02-25 | BIG EQUIPA        | L   | 0.130      | -            | -                | -                | -         |    -2.92 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            1 |     3991 | 2024-02-24 | Nemesis fe        | W   | 0.124      | 0.238        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.19 | Joanana, kezziwow, meli, RacheLL, suns1de  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,652.78)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
