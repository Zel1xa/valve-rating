### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1705.7<br />
<br />
Final Rank Value (1705.7) = Starting Rank Value (1730.7) + Head To Head Adjustments (-25.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.710[<sup>1</sup>](#table2)
- Bounty Collected: 0.621[<sup>2</sup>](#table1)
- Opponent Network: 0.326[<sup>2</sup>](#table1)
- LAN Wins: 0.942[<sup>2</sup>](#table1)

The average of these factors is 0.650<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1730.7
- 400 + ( ( 0.650 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1730.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |       28 | 2024-08-04 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | 0.254 (0.148)    | 0.551 (0.320)    | 1 (1.000) |    10.62 | br0, device, jabbi, Staehr, stavn    |
|           33 |       60 | 2024-08-03 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.51 | br0, device, jabbi, Staehr, stavn    |
|           32 |       99 | 2024-08-02 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.73 | br0, device, jabbi, Staehr, stavn    |
|           31 |      224 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |   -10.03 | br0, device, jabbi, Staehr, stavn    |
|           30 |      252 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.63 | br0, device, jabbi, Staehr, stavn    |
|           29 |     1075 | 2024-06-14 | Virtus.pro        | L   | 0.855      | -            | -                | -                | -         |   -15.29 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1134 | 2024-06-13 | SAW               | W   | 0.846      | 0.729        | -                | 0.537 (0.331)    | 1 (0.846) |     1.16 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1157 | 2024-06-12 | Natus Vincere     | L   | 0.840      | -            | -                | -                | -         |    -6.67 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1318 | 2024-06-08 | The MongolZ       | L   | 0.813      | -            | -                | -                | -         |    -7.32 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1373 | 2024-06-07 | BetBoom           | W   | 0.807      | 0.715        | 0.249 (0.144)    | 0.536 (0.309)    | 1 (0.807) |     3.84 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1420 | 2024-06-06 | The MongolZ       | W   | 0.801      | 0.715        | 1.000 (0.573)    | 0.719 (0.412)    | 1 (0.801) |    18.60 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1440 | 2024-06-06 | ENCE              | W   | 0.800      | 0.715        | -                | 0.438 (0.250)    | 1 (0.800) |     3.00 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1450 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.799      | -            | -                | -                | -         |   -17.23 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1496 | 2024-06-05 | Sashi             | L   | 0.794      | -            | -                | -                | -         |   -23.83 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1509 | 2024-06-05 | HEROIC            | W   | 0.792      | 0.715        | -                | 0.370 (0.210)    | 1 (0.792) |     6.92 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1858 | 2024-05-22 | Liquid            | L   | 0.699      | -            | -                | -                | -         |   -15.40 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1899 | 2024-05-21 | Aurora            | W   | 0.693      | 0.769        | 0.422 (0.225)    | 0.788 (0.420)    | -         |     5.30 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1929 | 2024-05-20 | BetBoom           | W   | 0.688      | 0.769        | 0.249 (0.132)    | 0.536 (0.283)    | -         |     2.34 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1949 | 2024-05-19 | BIG               | W   | 0.682      | -            | -                | -                | -         |     1.63 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2245 | 2024-05-11 | Vitality          | L   | 0.627      | -            | -                | -                | -         |    -6.82 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2264 | 2024-05-10 | Liquid            | W   | 0.620      | 0.889        | 0.384 (0.212)    | 0.456 (0.251)    | 1 (0.620) |     5.68 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2531 | 2024-04-27 | 3DMAX             | W   | 0.534      | 0.889        | 0.508 (0.241)    | 1.000 (0.475)    | 1 (0.534) |     5.81 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2602 | 2024-04-24 | FaZe              | W   | 0.515      | 0.889        | 0.632 (0.289)    | -                | -         |     7.61 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2622 | 2024-04-23 | Eternal Fire      | W   | 0.507      | 0.889        | 0.740 (0.334)    | -                | -         |     7.22 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2909 | 2024-04-13 | FaZe              | L   | 0.439      | -            | -                | -                | -         |    -7.57 | br0, device, jabbi, Staehr, stavn    |
|            9 |     3009 | 2024-04-10 | Virtus.pro        | W   | 0.419      | -            | -                | -                | -         |     5.98 | br0, device, jabbi, Staehr, stavn    |
|            8 |     3057 | 2024-04-09 | FaZe              | W   | 0.412      | 0.624        | 0.632 (0.163)    | -                | -         |     5.99 | br0, device, jabbi, Staehr, stavn    |
|            7 |     3089 | 2024-04-08 | Steel Helmet      | W   | 0.405      | -            | -                | -                | -         |     0.02 | br0, device, jabbi, Staehr, stavn    |
|            6 |     4060 | 2024-02-23 | 9 Pandas          | L   | 0.106      | -            | -                | -                | -         |    -3.29 | blameF, device, jabbi, Staehr, stavn |
|            5 |     4079 | 2024-02-22 | ENCE              | L   | 0.099      | -            | -                | -                | -         |    -2.52 | blameF, device, jabbi, Staehr, stavn |
|            4 |     4106 | 2024-02-21 | Monte             | W   | 0.093      | -            | -                | -                | -         |     0.05 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4132 | 2024-02-20 | HEROIC            | L   | 0.086      | -            | -                | -                | -         |    -1.96 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4147 | 2024-02-19 | Spirit            | L   | 0.082      | -            | -                | -                | -         |    -0.71 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4157 | 2024-02-19 | Nexus             | W   | 0.080      | -            | -                | -                | -         |     0.02 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($125,599.63)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.39) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-16 |      0.867 | $20,000.00     | $17,338.89      |
| 2024-06-09 |      0.821 | $28,000.00     | $22,975.56      |
| 2024-05-23 |      0.707 | $50,000.00     | $35,340.28      |
| 2024-05-12 |      0.634 | $45,000.00     | $28,525.00      |
| 2024-04-14 |      0.446 | $20,000.00     | $8,919.91       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
