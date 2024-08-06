### Roster Details<br />
Team Name: Let Her Cook<br />
Roster: ASTRA, Joanana, ManeschijnX, meli, RacheLL<br />
Global Rank: [84](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [62]( ../standings_europe.md)<br />
<br />
Final Rank Value:  927.4<br />
<br />
Final Rank Value (927.4) = Starting Rank Value (930.0) + Head To Head Adjustments (-2.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.450[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.263[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.0
- 400 + ( ( 0.258 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 930.0


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
|           16 |     1588 | 2024-06-02 | Imperial fe       | L   | 0.770      | -            | -                | -                | -         |    -8.16 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           15 |     1591 | 2024-06-02 | HSG fe            | W   | 0.769      | 0.524        | 0.031 (0.013)    | 0.068 (0.027)    | 1 (0.769) |     9.27 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           14 |     1649 | 2024-05-31 | panelinha         | W   | 0.757      | 0.524        | 0.032 (0.013)    | 0.149 (0.059)    | 1 (0.757) |    10.08 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           13 |     1655 | 2024-05-31 | NAVI Javelins     | W   | 0.756      | 0.524        | 0.026 (0.010)    | 0.183 (0.072)    | 1 (0.756) |    10.45 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           12 |     2702 | 2024-04-20 | Astralis W        | W   | 0.481      | 0.331        | 0.002 (0.000)    | 0.061 (0.010)    | 0 (0.000) |     3.17 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           11 |     2739 | 2024-04-19 | Spirit fe         | W   | 0.475      | 0.331        | 0.005 (0.001)    | 0.139 (0.022)    | 0 (0.000) |     2.90 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           10 |     2957 | 2024-04-11 | NIP Impact        | L   | 0.422      | -            | -                | -                | -         |    -9.80 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            9 |     3002 | 2024-04-10 | 1WIN Gang         | L   | 0.415      | -            | -                | -                | -         |   -10.70 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            8 |     3058 | 2024-04-09 | Spirit fe         | W   | 0.408      | 0.303        | 0.005 (0.001)    | 0.139 (0.017)    | 0 (0.000) |     2.42 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            7 |     3142 | 2024-04-06 | Fearless Cheetahs | L   | 0.387      | -            | -                | -                | -         |    -9.59 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            6 |     3228 | 2024-04-03 | NAVI Javelins     | W   | 0.369      | 0.331        | 0.026 (0.003)    | 0.183 (0.022)    | 0 (0.000) |     4.23 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            5 |     3448 | 2024-03-21 | Fearless Cheetahs | L   | 0.282      | -            | -                | -                | -         |    -7.13 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            4 |     3631 | 2024-03-13 | Crescent fe       | W   | 0.229      | 0.331        | 0.004 (0.000)    | 0.076 (0.006)    | 0 (0.000) |     1.34 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            3 |     3632 | 2024-03-13 | Crescent fe       | W   | 0.229      | 0.331        | 0.004 (0.000)    | 0.076 (0.006)    | 0 (0.000) |     1.32 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            2 |     4029 | 2024-02-25 | BIG EQUIPA        | L   | 0.114      | -            | -                | -                | -         |    -2.55 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            1 |     4061 | 2024-02-24 | Nemesis fe        | W   | 0.108      | 0.238        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.17 | Joanana, kezziwow, meli, RacheLL, suns1de  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,243.06)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />