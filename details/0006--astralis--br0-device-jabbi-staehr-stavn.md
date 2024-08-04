### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1705.9<br />
<br />
Final Rank Value (1705.9) = Starting Rank Value (1731.6) + Head To Head Adjustments (-25.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.710[<sup>1</sup>](#table2)
- Bounty Collected: 0.623[<sup>2</sup>](#table1)
- Opponent Network: 0.328[<sup>2</sup>](#table1)
- LAN Wins: 0.943[<sup>2</sup>](#table1)

The average of these factors is 0.651<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1731.6
- 400 + ( ( 0.651 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1731.6


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
|           34 |       11 | 2024-08-04 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | 0.254 (0.148)    | 0.553 (0.321)    | 1 (1.000) |    10.56 | br0, device, jabbi, Staehr, stavn    |
|           33 |       43 | 2024-08-03 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.49 | br0, device, jabbi, Staehr, stavn    |
|           32 |       83 | 2024-08-02 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.75 | br0, device, jabbi, Staehr, stavn    |
|           31 |      207 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |   -10.01 | br0, device, jabbi, Staehr, stavn    |
|           30 |      235 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.65 | br0, device, jabbi, Staehr, stavn    |
|           29 |     1058 | 2024-06-14 | Virtus.pro        | L   | 0.861      | -            | -                | -                | -         |   -15.35 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1117 | 2024-06-13 | SAW               | W   | 0.852      | 0.729        | -                | 0.540 (0.335)    | 1 (0.852) |     1.18 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1140 | 2024-06-12 | Natus Vincere     | L   | 0.846      | -            | -                | -                | -         |    -6.72 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1301 | 2024-06-08 | The MongolZ       | L   | 0.819      | -            | -                | -                | -         |    -7.46 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1356 | 2024-06-07 | BetBoom           | W   | 0.812      | 0.715        | 0.251 (0.146)    | 0.541 (0.314)    | 1 (0.812) |     3.88 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1403 | 2024-06-06 | The MongolZ       | W   | 0.807      | 0.715        | 1.000 (0.577)    | 0.721 (0.416)    | 1 (0.807) |    18.64 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1423 | 2024-06-06 | ENCE              | W   | 0.806      | 0.715        | -                | 0.400 (0.231)    | 1 (0.806) |     2.94 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1433 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.805      | -            | -                | -                | -         |   -17.42 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1479 | 2024-06-05 | Sashi             | L   | 0.799      | -            | -                | -                | -         |   -24.00 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1492 | 2024-06-05 | HEROIC            | W   | 0.798      | 0.715        | -                | 0.373 (0.213)    | 1 (0.798) |     6.99 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1841 | 2024-05-22 | Liquid            | L   | 0.705      | -            | -                | -                | -         |   -15.55 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1882 | 2024-05-21 | Aurora            | W   | 0.699      | 0.769        | 0.423 (0.227)    | 0.793 (0.426)    | -         |     5.27 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1912 | 2024-05-20 | BetBoom           | W   | 0.693      | 0.769        | 0.251 (0.134)    | 0.541 (0.288)    | -         |     2.36 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1932 | 2024-05-19 | BIG               | W   | 0.687      | -            | -                | -                | -         |     1.64 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2228 | 2024-05-11 | Vitality          | L   | 0.633      | -            | -                | -                | -         |    -6.87 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2247 | 2024-05-10 | Liquid            | W   | 0.626      | 0.889        | 0.384 (0.214)    | 0.460 (0.256)    | 1 (0.626) |     5.70 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2514 | 2024-04-27 | 3DMAX             | W   | 0.540      | 0.889        | 0.506 (0.243)    | 1.000 (0.480)    | 1 (0.540) |     5.78 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2585 | 2024-04-24 | FaZe              | W   | 0.520      | 0.889        | 0.638 (0.295)    | -                | -         |     7.77 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2605 | 2024-04-23 | Eternal Fire      | W   | 0.513      | 0.889        | 0.742 (0.338)    | -                | -         |     7.32 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2892 | 2024-04-13 | FaZe              | L   | 0.445      | -            | -                | -                | -         |    -7.61 | br0, device, jabbi, Staehr, stavn    |
|            9 |     2992 | 2024-04-10 | Virtus.pro        | W   | 0.424      | -            | -                | -                | -         |     6.08 | br0, device, jabbi, Staehr, stavn    |
|            8 |     3040 | 2024-04-09 | FaZe              | W   | 0.418      | 0.624        | 0.638 (0.166)    | -                | -         |     6.14 | br0, device, jabbi, Staehr, stavn    |
|            7 |     3072 | 2024-04-08 | Steel Helmet      | W   | 0.411      | -            | -                | -                | -         |     0.02 | br0, device, jabbi, Staehr, stavn    |
|            6 |     4043 | 2024-02-23 | 9 Pandas          | L   | 0.112      | -            | -                | -                | -         |    -3.46 | blameF, device, jabbi, Staehr, stavn |
|            5 |     4062 | 2024-02-22 | ENCE              | L   | 0.105      | -            | -                | -                | -         |    -2.69 | blameF, device, jabbi, Staehr, stavn |
|            4 |     4089 | 2024-02-21 | Monte             | W   | 0.098      | -            | -                | -                | -         |     0.05 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4115 | 2024-02-20 | HEROIC            | L   | 0.092      | -            | -                | -                | -         |    -2.09 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4130 | 2024-02-19 | Spirit            | L   | 0.088      | -            | -                | -                | -         |    -0.76 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4140 | 2024-02-19 | Nexus             | W   | 0.086      | -            | -                | -                | -         |     0.02 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($126,531.60)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.39) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-16 |      0.873 | $20,000.00     | $17,453.24      |
| 2024-06-09 |      0.826 | $28,000.00     | $23,135.65      |
| 2024-05-23 |      0.713 | $50,000.00     | $35,626.16      |
| 2024-05-12 |      0.640 | $45,000.00     | $28,782.29      |
| 2024-04-14 |      0.452 | $20,000.00     | $9,034.26       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
