### Roster Details<br />
Team Name: Let Her Cook<br />
Roster: ASTRA, Joanana, ManeschijnX, meli, RacheLL<br />
Global Rank: [88](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  928.2<br />
<br />
Final Rank Value (928.2) = Starting Rank Value (930.8) + Head To Head Adjustments (-2.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.450[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.263[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.8
- 400 + ( ( 0.258 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 930.8


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
|           16 |     1603 | 2024-06-02 | Imperial fe       | L   | 0.768      | -            | -                | -                | -         |    -8.14 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           15 |     1606 | 2024-06-02 | HSG fe            | W   | 0.767      | 0.524        | 0.031 (0.013)    | 0.066 (0.027)    | 1 (0.767) |     9.24 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           14 |     1664 | 2024-05-31 | panelinha         | W   | 0.755      | 0.524        | 0.032 (0.013)    | 0.146 (0.058)    | 1 (0.755) |    10.05 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           13 |     1670 | 2024-05-31 | NAVI Javelins     | W   | 0.754      | 0.524        | 0.026 (0.010)    | 0.179 (0.071)    | 1 (0.754) |    10.41 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           12 |     2717 | 2024-04-20 | Astralis W        | W   | 0.480      | 0.331        | 0.002 (0.000)    | 0.060 (0.009)    | 0 (0.000) |     3.15 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           11 |     2754 | 2024-04-19 | Spirit fe         | W   | 0.474      | 0.331        | 0.005 (0.001)    | 0.136 (0.021)    | 0 (0.000) |     2.88 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           10 |     2972 | 2024-04-11 | NIP Impact        | L   | 0.420      | -            | -                | -                | -         |    -9.77 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            9 |     3017 | 2024-04-10 | 1WIN Gang         | L   | 0.414      | -            | -                | -                | -         |   -10.66 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            8 |     3073 | 2024-04-09 | Spirit fe         | W   | 0.407      | 0.303        | 0.005 (0.001)    | 0.136 (0.017)    | 0 (0.000) |     2.41 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            7 |     3157 | 2024-04-06 | Fearless Cheetahs | L   | 0.385      | -            | -                | -                | -         |    -9.55 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            6 |     3243 | 2024-04-03 | NAVI Javelins     | W   | 0.367      | 0.331        | 0.026 (0.003)    | 0.179 (0.022)    | 0 (0.000) |     4.20 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            5 |     3463 | 2024-03-21 | Fearless Cheetahs | L   | 0.281      | -            | -                | -                | -         |    -7.09 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            4 |     3646 | 2024-03-13 | Crescent fe       | W   | 0.227      | 0.331        | 0.004 (0.000)    | 0.074 (0.006)    | 0 (0.000) |     1.33 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            3 |     3647 | 2024-03-13 | Crescent fe       | W   | 0.227      | 0.331        | 0.004 (0.000)    | 0.074 (0.006)    | 0 (0.000) |     1.31 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            2 |     4044 | 2024-02-25 | BIG EQUIPA        | L   | 0.112      | -            | -                | -                | -         |    -2.51 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            1 |     4076 | 2024-02-24 | Nemesis fe        | W   | 0.106      | 0.238        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.16 | Joanana, kezziwow, meli, RacheLL, suns1de  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,201.39)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
