### Roster Details<br />
Team Name: Let Her Cook<br />
Roster: ASTRA, Joanana, ManeschijnX, meli, RacheLL<br />
Global Rank: [84](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [62]( ../standings_europe.md)<br />
<br />
Final Rank Value:  927.6<br />
<br />
Final Rank Value (927.6) = Starting Rank Value (930.4) + Head To Head Adjustments (-2.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.450[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.264[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.4
- 400 + ( ( 0.259 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 930.4


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
|           16 |     1581 | 2024-06-02 | Imperial fe       | L   | 0.774      | -            | -                | -                | -         |    -8.20 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           15 |     1584 | 2024-06-02 | HSG fe            | W   | 0.774      | 0.524        | 0.031 (0.013)    | 0.068 (0.028)    | 1 (0.774) |     9.32 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           14 |     1642 | 2024-05-31 | panelinha         | W   | 0.762      | 0.524        | 0.032 (0.013)    | 0.150 (0.060)    | 1 (0.762) |    10.15 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           13 |     1648 | 2024-05-31 | NAVI Javelins     | W   | 0.760      | 0.524        | 0.026 (0.010)    | 0.184 (0.073)    | 1 (0.760) |    10.54 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           12 |     2695 | 2024-04-20 | Astralis W        | W   | 0.486      | 0.331        | 0.002 (0.000)    | 0.062 (0.010)    | 0 (0.000) |     3.20 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           11 |     2732 | 2024-04-19 | Spirit fe         | W   | 0.480      | 0.331        | 0.005 (0.001)    | 0.139 (0.022)    | 0 (0.000) |     2.92 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           10 |     2950 | 2024-04-11 | NIP Impact        | L   | 0.427      | -            | -                | -                | -         |    -9.91 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            9 |     2995 | 2024-04-10 | 1WIN Gang         | L   | 0.420      | -            | -                | -                | -         |   -10.82 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            8 |     3051 | 2024-04-09 | Spirit fe         | W   | 0.413      | 0.303        | 0.005 (0.001)    | 0.139 (0.017)    | 0 (0.000) |     2.45 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            7 |     3135 | 2024-04-06 | Fearless Cheetahs | L   | 0.392      | -            | -                | -                | -         |    -9.70 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            6 |     3221 | 2024-04-03 | NAVI Javelins     | W   | 0.373      | 0.331        | 0.026 (0.003)    | 0.184 (0.023)    | 0 (0.000) |     4.29 | ASTRA, Joanana, kezziwow, meli, RacheLL    |
|            5 |     3441 | 2024-03-21 | Fearless Cheetahs | L   | 0.287      | -            | -                | -                | -         |    -7.25 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            4 |     3624 | 2024-03-13 | Crescent fe       | W   | 0.234      | 0.331        | 0.005 (0.000)    | 0.076 (0.006)    | 0 (0.000) |     1.37 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            3 |     3625 | 2024-03-13 | Crescent fe       | W   | 0.234      | 0.331        | 0.005 (0.000)    | 0.076 (0.006)    | 0 (0.000) |     1.35 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            2 |     4022 | 2024-02-25 | BIG EQUIPA        | L   | 0.118      | -            | -                | -                | -         |    -2.66 | Joanana, kezziwow, meli, RacheLL, suns1de  |
|            1 |     4054 | 2024-02-24 | Nemesis fe        | W   | 0.112      | 0.238        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.17 | Joanana, kezziwow, meli, RacheLL, suns1de  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,361.11)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
