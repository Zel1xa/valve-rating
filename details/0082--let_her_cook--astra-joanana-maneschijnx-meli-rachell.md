### Roster Details<br />
Team Name: Let Her Cook<br />
Roster: ASTRA, Joanana, ManeschijnX, meli, RacheLL<br />
Global Rank: [82](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [60]( ../standings_europe.md)<br />
<br />
Final Rank Value:  927.6<br />
<br />
Final Rank Value (927.6) = Starting Rank Value (940.6) + Head To Head Adjustments (-13.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.452[<sup>1</sup>](#table2)
- Bounty Collected: 0.298[<sup>2</sup>](#table1)
- Opponent Network: 0.026[<sup>2</sup>](#table1)
- LAN Wins: 0.274[<sup>2</sup>](#table1)

The average of these factors is 0.263<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 940.6
- 400 + ( ( 0.263 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 940.6


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
|           16 |     1458 | 2024-06-02 | Imperial fe       | L   | 0.802      | -            | -                | -                | -         |    -8.17 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           15 |     1462 | 2024-06-02 | HSG fe            | W   | 0.802      | 0.524        | 0.032 (0.013)    | 0.071 (0.030)    | 1 (0.802) |     9.93 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           14 |     1520 | 2024-05-31 | panelinha         | W   | 0.790      | 0.524        | 0.033 (0.013)    | 0.158 (0.065)    | 1 (0.790) |    10.88 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           13 |     1526 | 2024-05-31 | NAVI Javelins     | W   | 0.788      | 0.524        | 0.027 (0.011)    | 0.211 (0.087)    | 1 (0.788) |    11.60 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           12 |     2621 | 2024-04-20 | ex-GUILD fe       | W   | 0.514      | 0.331        | 0.003 (0.000)    | 0.066 (0.011)    | 0 (0.000) |     3.48 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           11 |     2659 | 2024-04-19 | Spirit fe         | W   | 0.508      | 0.331        | 0.005 (0.001)    | 0.101 (0.017)    | 0 (0.000) |     3.08 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           10 |     2860 | 2024-04-12 | NAVI Javelins     | L   | 0.460      | -            | -                | -                | -         |    -8.69 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            9 |     2881 | 2024-04-11 | NIP Impact        | L   | 0.455      | -            | -                | -                | -         |   -10.65 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            8 |     2926 | 2024-04-10 | 1WIN Gang         | L   | 0.448      | -            | -                | -                | -         |   -11.61 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            7 |     2982 | 2024-04-09 | Spirit fe         | W   | 0.441      | 0.303        | 0.005 (0.001)    | 0.101 (0.014)    | 0 (0.000) |     2.49 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            6 |     3066 | 2024-04-06 | Fearless Cheetahs | L   | 0.420      | -            | -                | -                | -         |   -10.43 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            5 |     3154 | 2024-04-03 | NAVI Javelins     | W   | 0.402      | 0.331        | 0.027 (0.004)    | 0.211 (0.028)    | 0 (0.000) |     4.64 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            4 |     3385 | 2024-03-21 | Fearless Cheetahs | L   | 0.315      | -            | -                | -                | -         |    -7.99 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            3 |     3572 | 2024-03-13 | Crescent fe       | W   | 0.262      | 0.331        | 0.005 (0.000)    | 0.079 (0.007)    | 0 (0.000) |     1.48 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            2 |     3981 | 2024-02-25 | BIG EQUIPA        | L   | 0.146      | -            | -                | -                | -         |    -3.31 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            1 |     4015 | 2024-02-24 | Nemesis fe        | W   | 0.140      | 0.238        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.20 | Joanana, kezziwow, meli, RacheLL, suns1de  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,062.50)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
