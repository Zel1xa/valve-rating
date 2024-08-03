### Roster Details<br />
Team Name: Let Her Cook<br />
Roster: ASTRA, Joanana, ManeschijnX, meli, RacheLL<br />
Global Rank: [82](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [60]( ../standings_europe.md)<br />
<br />
Final Rank Value:  927.2<br />
<br />
Final Rank Value (927.2) = Starting Rank Value (931.6) + Head To Head Adjustments (-4.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.451[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.026[<sup>2</sup>](#table1)
- LAN Wins: 0.266[<sup>2</sup>](#table1)

The average of these factors is 0.260<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 931.6
- 400 + ( ( 0.260 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 931.6


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
|           15 |     1459 | 2024-06-02 | Imperial fe       | L   | 0.788      | -            | -                | -                | -         |    -8.25 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           14 |     1462 | 2024-06-02 | HSG fe            | W   | 0.787      | 0.524        | 0.031 (0.013)    | 0.072 (0.030)    | 1 (0.787) |     9.53 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           13 |     1518 | 2024-05-31 | panelinha         | W   | 0.775      | 0.524        | 0.032 (0.013)    | 0.161 (0.065)    | 1 (0.775) |    10.41 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           12 |     1524 | 2024-05-31 | NAVI Javelins     | W   | 0.774      | 0.524        | 0.027 (0.011)    | 0.196 (0.080)    | 1 (0.774) |    10.84 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           11 |     2567 | 2024-04-20 | Astralis W        | W   | 0.499      | 0.331        | 0.002 (0.000)    | 0.067 (0.011)    | 0 (0.000) |     3.32 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           10 |     2604 | 2024-04-19 | Spirit fe         | W   | 0.494      | 0.331        | 0.005 (0.001)    | 0.145 (0.024)    | 0 (0.000) |     3.01 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|            9 |     2822 | 2024-04-11 | NIP Impact        | L   | 0.440      | -            | -                | -                | -         |   -10.22 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            8 |     2867 | 2024-04-10 | 1WIN Gang         | L   | 0.434      | -            | -                | -                | -         |   -11.16 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            7 |     2923 | 2024-04-09 | Spirit fe         | W   | 0.427      | 0.303        | 0.005 (0.001)    | 0.145 (0.019)    | 0 (0.000) |     2.53 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            6 |     3007 | 2024-04-06 | Fearless Cheetahs | L   | 0.405      | -            | -                | -                | -         |   -10.01 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            5 |     3093 | 2024-04-03 | NAVI Javelins     | W   | 0.387      | 0.331        | 0.027 (0.003)    | 0.196 (0.025)    | 0 (0.000) |     4.48 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            4 |     3308 | 2024-03-21 | Fearless Cheetahs | L   | 0.300      | -            | -                | -                | -         |    -7.58 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            3 |     3489 | 2024-03-13 | Crescent fe       | W   | 0.247      | 0.331        | 0.005 (0.000)    | 0.081 (0.007)    | 0 (0.000) |     1.44 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            2 |     3886 | 2024-02-25 | BIG EQUIPA        | L   | 0.132      | -            | -                | -                | -         |    -2.96 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            1 |     3918 | 2024-02-24 | Nemesis fe        | W   | 0.126      | 0.238        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.19 | Joanana, kezziwow, meli, RacheLL, suns1de  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,695.60)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
