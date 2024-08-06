### Roster Details<br />
Team Name: Let Her Cook<br />
Roster: ASTRA, Joanana, ManeschijnX, meli, RacheLL<br />
Global Rank: [84](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [62]( ../standings_europe.md)<br />
<br />
Final Rank Value:  927.5<br />
<br />
Final Rank Value (927.5) = Starting Rank Value (930.2) + Head To Head Adjustments (-2.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.450[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.264[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.2
- 400 + ( ( 0.258 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 930.2


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
|           16 |     1584 | 2024-06-02 | Imperial fe       | L   | 0.772      | -            | -                | -                | -         |    -8.18 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           15 |     1587 | 2024-06-02 | HSG fe            | W   | 0.771      | 0.524        | 0.031 (0.013)    | 0.068 (0.028)    | 1 (0.771) |     9.30 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           14 |     1645 | 2024-05-31 | panelinha         | W   | 0.759      | 0.524        | 0.032 (0.013)    | 0.150 (0.060)    | 1 (0.759) |    10.12 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           13 |     1651 | 2024-05-31 | NAVI Javelins     | W   | 0.758      | 0.524        | 0.026 (0.010)    | 0.184 (0.073)    | 1 (0.758) |    10.49 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           12 |     2698 | 2024-04-20 | Astralis W        | W   | 0.484      | 0.331        | 0.002 (0.000)    | 0.062 (0.010)    | 0 (0.000) |     3.19 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           11 |     2735 | 2024-04-19 | Spirit fe         | W   | 0.478      | 0.331        | 0.005 (0.001)    | 0.139 (0.022)    | 0 (0.000) |     2.91 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           10 |     2953 | 2024-04-11 | NIP Impact        | L   | 0.424      | -            | -                | -                | -         |    -9.86 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            9 |     2998 | 2024-04-10 | 1WIN Gang         | L   | 0.418      | -            | -                | -                | -         |   -10.77 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            8 |     3054 | 2024-04-09 | Spirit fe         | W   | 0.411      | 0.303        | 0.005 (0.001)    | 0.139 (0.017)    | 0 (0.000) |     2.44 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            7 |     3138 | 2024-04-06 | Fearless Cheetahs | L   | 0.389      | -            | -                | -                | -         |    -9.65 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            6 |     3224 | 2024-04-03 | NAVI Javelins     | W   | 0.371      | 0.331        | 0.026 (0.003)    | 0.184 (0.023)    | 0 (0.000) |     4.26 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            5 |     3444 | 2024-03-21 | Fearless Cheetahs | L   | 0.285      | -            | -                | -                | -         |    -7.19 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            4 |     3627 | 2024-03-13 | Crescent fe       | W   | 0.232      | 0.331        | 0.005 (0.000)    | 0.076 (0.006)    | 0 (0.000) |     1.35 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            3 |     3628 | 2024-03-13 | Crescent fe       | W   | 0.232      | 0.331        | 0.005 (0.000)    | 0.076 (0.006)    | 0 (0.000) |     1.34 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            2 |     4025 | 2024-02-25 | BIG EQUIPA        | L   | 0.116      | -            | -                | -                | -         |    -2.61 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            1 |     4057 | 2024-02-24 | Nemesis fe        | W   | 0.110      | 0.238        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.17 | Joanana, kezziwow, meli, RacheLL, suns1de  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,305.56)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
