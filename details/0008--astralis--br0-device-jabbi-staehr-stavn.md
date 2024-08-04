### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1666.1<br />
<br />
Final Rank Value (1666.1) = Starting Rank Value (1685.5) + Head To Head Adjustments (-19.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.688[<sup>1</sup>](#table2)
- Bounty Collected: 0.620[<sup>2</sup>](#table1)
- Opponent Network: 0.318[<sup>2</sup>](#table1)
- LAN Wins: 0.889[<sup>2</sup>](#table1)

The average of these factors is 0.629<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1685.5
- 400 + ( ( 0.629 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1685.5


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
|           33 |       13 | 2024-08-03 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -8.63 | br0, device, jabbi, Staehr, stavn    |
|           32 |       52 | 2024-08-02 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     6.51 | br0, device, jabbi, Staehr, stavn    |
|           31 |      175 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.03 | br0, device, jabbi, Staehr, stavn    |
|           30 |      203 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     6.47 | br0, device, jabbi, Staehr, stavn    |
|           29 |     1026 | 2024-06-14 | Virtus.pro        | L   | 0.862      | -            | -                | -                | -         |   -14.28 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1085 | 2024-06-13 | SAW               | W   | 0.854      | 0.729        | -                | 0.540 (0.336)    | 1 (0.854) |     1.39 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1108 | 2024-06-12 | Natus Vincere     | L   | 0.848      | -            | -                | -                | -         |    -5.91 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1269 | 2024-06-08 | The MongolZ       | L   | 0.821      | -            | -                | -                | -         |    -6.58 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1324 | 2024-06-07 | BetBoom           | W   | 0.814      | 0.715        | 0.251 (0.146)    | 0.542 (0.316)    | 1 (0.814) |     4.59 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1371 | 2024-06-06 | The MongolZ       | W   | 0.809      | 0.715        | 1.000 (0.578)    | 0.721 (0.417)    | 1 (0.809) |    19.59 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1391 | 2024-06-06 | ENCE              | W   | 0.807      | 0.715        | -                | 0.400 (0.231)    | 1 (0.807) |     3.46 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1401 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.807      | -            | -                | -                | -         |   -16.61 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1447 | 2024-06-05 | Sashi             | L   | 0.801      | -            | -                | -                | -         |   -23.81 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1460 | 2024-06-05 | HEROIC            | W   | 0.799      | 0.715        | -                | 0.374 (0.214)    | 1 (0.799) |     8.04 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1809 | 2024-05-22 | Liquid            | L   | 0.707      | -            | -                | -                | -         |   -16.57 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1850 | 2024-05-21 | Aurora            | W   | 0.701      | 0.769        | 0.424 (0.228)    | 0.793 (0.427)    | -         |     6.17 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1880 | 2024-05-20 | BetBoom           | W   | 0.695      | 0.769        | 0.251 (0.134)    | 0.542 (0.289)    | -         |     2.88 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1900 | 2024-05-19 | BIG               | W   | 0.689      | -            | -                | -                | -         |     2.02 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2196 | 2024-05-11 | Vitality          | L   | 0.635      | -            | -                | -                | -         |    -6.00 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2215 | 2024-05-10 | Liquid            | W   | 0.628      | 0.889        | 0.315 (0.176)    | 0.460 (0.257)    | 1 (0.628) |     4.82 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2482 | 2024-04-27 | 3DMAX             | W   | 0.541      | 0.889        | 0.506 (0.243)    | 1.000 (0.481)    | 1 (0.541) |     6.68 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2553 | 2024-04-24 | FaZe              | W   | 0.522      | 0.889        | 0.640 (0.297)    | -                | 1 (0.522) |     8.66 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2573 | 2024-04-23 | Eternal Fire      | W   | 0.515      | 0.889        | 0.743 (0.340)    | 0.458 (0.210)    | -         |     8.30 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2860 | 2024-04-13 | FaZe              | L   | 0.447      | -            | -                | -                | -         |    -6.84 | br0, device, jabbi, Staehr, stavn    |
|            9 |     2960 | 2024-04-10 | Virtus.pro        | W   | 0.426      | 0.624        | 0.497 (0.132)    | -                | -         |     6.89 | br0, device, jabbi, Staehr, stavn    |
|            8 |     3008 | 2024-04-09 | FaZe              | W   | 0.420      | 0.624        | 0.640 (0.168)    | -                | -         |     6.99 | br0, device, jabbi, Staehr, stavn    |
|            7 |     3040 | 2024-04-08 | Steel Helmet      | W   | 0.413      | -            | -                | -                | -         |     0.03 | br0, device, jabbi, Staehr, stavn    |
|            6 |     4011 | 2024-02-23 | 9 Pandas          | L   | 0.114      | -            | -                | -                | -         |    -3.50 | blameF, device, jabbi, Staehr, stavn |
|            5 |     4030 | 2024-02-22 | ENCE              | L   | 0.107      | -            | -                | -                | -         |    -2.60 | blameF, device, jabbi, Staehr, stavn |
|            4 |     4057 | 2024-02-21 | Monte             | W   | 0.100      | -            | -                | -                | -         |     0.07 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4083 | 2024-02-20 | HEROIC            | L   | 0.094      | -            | -                | -                | -         |    -1.97 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4098 | 2024-02-19 | Spirit            | L   | 0.089      | -            | -                | -                | -         |    -0.64 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4108 | 2024-02-19 | Nexus             | W   | 0.088      | -            | -                | -                | -         |     0.02 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($114,322.13)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.35) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.874 | $20,000.00     | $17,488.89      |
| 2024-06-09 |      0.828 | $28,000.00     | $23,185.56      |
| 2024-05-23 |      0.714 | $50,000.00     | $35,715.28      |
| 2024-05-12 |      0.641 | $45,000.00     | $28,862.50      |
| 2024-04-14 |      0.453 | $20,000.00     | $9,069.91       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
