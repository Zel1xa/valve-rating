### Roster Details<br />
Team Name: Let Her Cook<br />
Roster: ASTRA, Joanana, ManeschijnX, meli, RacheLL<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  927.3<br />
<br />
Final Rank Value (927.3) = Starting Rank Value (930.5) + Head To Head Adjustments (-3.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.451[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.265[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.5
- 400 + ( ( 0.259 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 930.5


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
|           16 |     1524 | 2024-06-02 | Imperial fe       | L   | 0.783      | -            | -                | -                | -         |    -8.27 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           15 |     1527 | 2024-06-02 | HSG fe            | W   | 0.782      | 0.524        | 0.031 (0.013)    | 0.070 (0.029)    | 1 (0.782) |     9.43 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           14 |     1585 | 2024-05-31 | panelinha         | W   | 0.770      | 0.524        | 0.032 (0.013)    | 0.154 (0.062)    | 1 (0.770) |    10.29 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           13 |     1591 | 2024-05-31 | NAVI Javelins     | W   | 0.769      | 0.524        | 0.026 (0.011)    | 0.189 (0.076)    | 1 (0.769) |    10.70 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           12 |     2638 | 2024-04-20 | Astralis W        | W   | 0.495      | 0.331        | 0.002 (0.000)    | 0.064 (0.010)    | 0 (0.000) |     3.27 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           11 |     2675 | 2024-04-19 | Spirit fe         | W   | 0.489      | 0.331        | 0.005 (0.001)    | 0.141 (0.023)    | 0 (0.000) |     2.97 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           10 |     2893 | 2024-04-11 | NIP Impact        | L   | 0.435      | -            | -                | -                | -         |   -10.13 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            9 |     2938 | 2024-04-10 | 1WIN Gang         | L   | 0.429      | -            | -                | -                | -         |   -11.05 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            8 |     2994 | 2024-04-09 | Spirit fe         | W   | 0.422      | 0.303        | 0.005 (0.001)    | 0.141 (0.018)    | 0 (0.000) |     2.50 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            7 |     3078 | 2024-04-06 | Fearless Cheetahs | L   | 0.400      | -            | -                | -                | -         |    -9.91 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            6 |     3164 | 2024-04-03 | NAVI Javelins     | W   | 0.382      | 0.331        | 0.026 (0.003)    | 0.189 (0.024)    | 0 (0.000) |     4.39 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            5 |     3384 | 2024-03-21 | Fearless Cheetahs | L   | 0.296      | -            | -                | -                | -         |    -7.47 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            4 |     3567 | 2024-03-13 | Crescent fe       | W   | 0.242      | 0.331        | 0.005 (0.000)    | 0.078 (0.006)    | 0 (0.000) |     1.42 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            3 |     3568 | 2024-03-13 | Crescent fe       | W   | 0.242      | 0.331        | 0.005 (0.000)    | 0.078 (0.006)    | 0 (0.000) |     1.40 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            2 |     3965 | 2024-02-25 | BIG EQUIPA        | L   | 0.127      | -            | -                | -                | -         |    -2.85 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            1 |     3997 | 2024-02-24 | Nemesis fe        | W   | 0.121      | 0.238        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.19 | Joanana, kezziwow, meli, RacheLL, suns1de  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,576.39)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
