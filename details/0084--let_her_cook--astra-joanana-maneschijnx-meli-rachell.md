### Roster Details<br />
Team Name: Let Her Cook<br />
Roster: ASTRA, Joanana, ManeschijnX, meli, RacheLL<br />
Global Rank: [84](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [62]( ../standings_europe.md)<br />
<br />
Final Rank Value:  927.3<br />
<br />
Final Rank Value (927.3) = Starting Rank Value (930.3) + Head To Head Adjustments (-3.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.450[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.265[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.3
- 400 + ( ( 0.259 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 930.3


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
|           16 |     1556 | 2024-06-02 | Imperial fe       | L   | 0.781      | -            | -                | -                | -         |    -8.25 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           15 |     1559 | 2024-06-02 | HSG fe            | W   | 0.781      | 0.524        | 0.031 (0.013)    | 0.070 (0.028)    | 1 (0.781) |     9.41 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           14 |     1617 | 2024-05-31 | panelinha         | W   | 0.769      | 0.524        | 0.032 (0.013)    | 0.154 (0.062)    | 1 (0.769) |    10.26 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           13 |     1623 | 2024-05-31 | NAVI Javelins     | W   | 0.767      | 0.524        | 0.026 (0.011)    | 0.189 (0.076)    | 1 (0.767) |    10.67 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           12 |     2670 | 2024-04-20 | Astralis W        | W   | 0.493      | 0.331        | 0.002 (0.000)    | 0.064 (0.010)    | 0 (0.000) |     3.25 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           11 |     2707 | 2024-04-19 | Spirit fe         | W   | 0.487      | 0.331        | 0.005 (0.001)    | 0.141 (0.023)    | 0 (0.000) |     2.96 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           10 |     2925 | 2024-04-11 | NIP Impact        | L   | 0.433      | -            | -                | -                | -         |   -10.06 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            9 |     2970 | 2024-04-10 | 1WIN Gang         | L   | 0.427      | -            | -                | -                | -         |   -11.00 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            8 |     3026 | 2024-04-09 | Spirit fe         | W   | 0.420      | 0.303        | 0.005 (0.001)    | 0.141 (0.018)    | 0 (0.000) |     2.49 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            7 |     3110 | 2024-04-06 | Fearless Cheetahs | L   | 0.398      | -            | -                | -                | -         |    -9.87 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            6 |     3196 | 2024-04-03 | NAVI Javelins     | W   | 0.380      | 0.331        | 0.026 (0.003)    | 0.189 (0.024)    | 0 (0.000) |     4.37 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            5 |     3416 | 2024-03-21 | Fearless Cheetahs | L   | 0.294      | -            | -                | -                | -         |    -7.42 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            4 |     3599 | 2024-03-13 | Crescent fe       | W   | 0.241      | 0.331        | 0.005 (0.000)    | 0.078 (0.006)    | 0 (0.000) |     1.41 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            3 |     3600 | 2024-03-13 | Crescent fe       | W   | 0.241      | 0.331        | 0.005 (0.000)    | 0.078 (0.006)    | 0 (0.000) |     1.39 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            2 |     3997 | 2024-02-25 | BIG EQUIPA        | L   | 0.125      | -            | -                | -                | -         |    -2.81 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            1 |     4029 | 2024-02-24 | Nemesis fe        | W   | 0.119      | 0.238        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.18 | Joanana, kezziwow, meli, RacheLL, suns1de  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,531.83)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
