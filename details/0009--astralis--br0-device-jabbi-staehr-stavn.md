### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [9](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1668.3<br />
<br />
Final Rank Value (1668.3) = Starting Rank Value (1690.4) + Head To Head Adjustments (-22.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.692[<sup>1</sup>](#table2)
- Bounty Collected: 0.627[<sup>2</sup>](#table1)
- Opponent Network: 0.327[<sup>2</sup>](#table1)
- LAN Wins: 0.860[<sup>2</sup>](#table1)

The average of these factors is 0.627<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1690.4
- 400 + ( ( 0.627 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1690.4


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
|           31 |       86 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.05 | br0, device, jabbi, Staehr, stavn    |
|           30 |      115 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     6.89 | br0, device, jabbi, Staehr, stavn    |
|           29 |      945 | 2024-06-14 | Virtus.pro        | L   | 0.882      | -            | -                | -                | -         |   -14.34 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1003 | 2024-06-13 | SAW               | W   | 0.873      | 0.729        | -                | 0.544 (0.346)    | 1 (0.873) |     1.47 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1026 | 2024-06-12 | Natus Vincere     | L   | 0.867      | -            | -                | -                | -         |    -5.70 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1193 | 2024-06-08 | The MongolZ       | L   | 0.840      | -            | -                | -                | -         |    -6.66 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1253 | 2024-06-07 | BetBoom           | W   | 0.834      | 0.715        | 0.257 (0.154)    | 0.551 (0.329)    | 1 (0.834) |     4.73 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1302 | 2024-06-06 | The MongolZ       | W   | 0.828      | 0.715        | 1.000 (0.592)    | 0.719 (0.426)    | 1 (0.828) |    20.13 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1322 | 2024-06-06 | ENCE              | W   | 0.827      | 0.715        | -                | 0.403 (0.238)    | 1 (0.827) |     3.43 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1333 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.826      | -            | -                | -                | -         |   -21.07 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1381 | 2024-06-05 | Sashi             | L   | 0.820      | -            | -                | -                | -         |   -24.37 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1394 | 2024-06-05 | HEROIC            | W   | 0.819      | 0.715        | -                | 0.381 (0.223)    | 1 (0.819) |     8.08 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1756 | 2024-05-22 | Liquid            | L   | 0.726      | -            | -                | -                | -         |   -17.93 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1802 | 2024-05-21 | Aurora            | W   | 0.720      | 0.769        | 0.432 (0.239)    | 0.798 (0.442)    | -         |     6.34 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1834 | 2024-05-20 | BetBoom           | W   | 0.714      | 0.769        | 0.257 (0.141)    | 0.551 (0.303)    | -         |     3.00 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1862 | 2024-05-19 | BIG               | W   | 0.708      | -            | -                | -                | -         |     1.46 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2168 | 2024-05-11 | Vitality          | L   | 0.654      | -            | -                | -                | -         |    -6.37 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2187 | 2024-05-10 | Liquid            | W   | 0.647      | 0.889        | 0.322 (0.185)    | 0.429 (0.247)    | 1 (0.647) |     4.08 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2459 | 2024-04-27 | 3DMAX             | W   | 0.561      | 0.889        | 0.505 (0.252)    | 1.000 (0.498)    | 1 (0.561) |     6.75 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2530 | 2024-04-24 | FaZe              | W   | 0.542      | 0.889        | 0.638 (0.307)    | -                | 1 (0.542) |     9.55 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2552 | 2024-04-23 | Eternal Fire      | W   | 0.534      | 0.889        | 0.757 (0.360)    | 0.461 (0.219)    | 1 (0.534) |     8.93 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2847 | 2024-04-13 | FaZe              | L   | 0.466      | -            | -                | -                | -         |    -6.62 | br0, device, jabbi, Staehr, stavn    |
|            9 |     2948 | 2024-04-10 | Virtus.pro        | W   | 0.446      | 0.624        | 0.483 (0.134)    | -                | -         |     7.38 | br0, device, jabbi, Staehr, stavn    |
|            8 |     2996 | 2024-04-09 | FaZe              | W   | 0.439      | 0.624        | 0.638 (0.175)    | -                | -         |     7.85 | br0, device, jabbi, Staehr, stavn    |
|            7 |     3028 | 2024-04-08 | Steel Helmet      | W   | 0.432      | -            | -                | -                | -         |     0.03 | br0, device, jabbi, Staehr, stavn    |
|            6 |     4031 | 2024-02-23 | 9 Pandas          | L   | 0.133      | -            | -                | -                | -         |    -4.10 | blameF, device, jabbi, Staehr, stavn |
|            5 |     4051 | 2024-02-22 | ENCE              | L   | 0.126      | -            | -                | -                | -         |    -3.03 | blameF, device, jabbi, Staehr, stavn |
|            4 |     4080 | 2024-02-21 | Monte             | W   | 0.120      | -            | -                | -                | -         |     0.08 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4105 | 2024-02-20 | HEROIC            | L   | 0.113      | -            | -                | -                | -         |    -2.33 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4120 | 2024-02-19 | Spirit            | L   | 0.109      | -            | -                | -                | -         |    -0.77 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4130 | 2024-02-19 | Nexus             | W   | 0.107      | -            | -                | -                | -         |     0.03 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($117,491.57)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.36) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.894 | $20,000.00     | $17,877.78      |
| 2024-06-09 |      0.848 | $28,000.00     | $23,730.00      |
| 2024-05-23 |      0.734 | $50,000.00     | $36,687.50      |
| 2024-05-12 |      0.661 | $45,000.00     | $29,737.50      |
| 2024-04-14 |      0.473 | $20,000.00     | $9,458.80       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
