### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [9](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1670.0<br />
<br />
Final Rank Value (1670.0) = Starting Rank Value (1688.9) + Head To Head Adjustments (-18.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.692[<sup>1</sup>](#table2)
- Bounty Collected: 0.626[<sup>2</sup>](#table1)
- Opponent Network: 0.328[<sup>2</sup>](#table1)
- LAN Wins: 0.860[<sup>2</sup>](#table1)

The average of these factors is 0.627<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1688.9
- 400 + ( ( 0.627 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1688.9


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
|           31 |       93 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.18 | br0, device, jabbi, Staehr, stavn    |
|           30 |      121 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     6.83 | br0, device, jabbi, Staehr, stavn    |
|           29 |      951 | 2024-06-14 | Virtus.pro        | L   | 0.880      | -            | -                | -                | -         |   -14.43 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1009 | 2024-06-13 | SAW               | W   | 0.871      | 0.729        | -                | 0.544 (0.345)    | 1 (0.871) |     1.45 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1032 | 2024-06-12 | Natus Vincere     | L   | 0.865      | -            | -                | -                | -         |    -5.79 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1199 | 2024-06-08 | The MongolZ       | L   | 0.839      | -            | -                | -                | -         |    -6.68 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1259 | 2024-06-07 | BetBoom           | W   | 0.832      | 0.715        | 0.257 (0.153)    | 0.551 (0.328)    | 1 (0.832) |     4.67 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1308 | 2024-06-06 | The MongolZ       | W   | 0.826      | 0.715        | 1.000 (0.591)    | 0.719 (0.425)    | 1 (0.826) |    20.06 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1328 | 2024-06-06 | ENCE              | W   | 0.825      | 0.715        | -                | 0.403 (0.238)    | 1 (0.825) |     3.43 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1339 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.824      | -            | -                | -                | -         |   -19.96 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1387 | 2024-06-05 | Sashi             | L   | 0.819      | -            | -                | -                | -         |   -24.34 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1400 | 2024-06-05 | HEROIC            | W   | 0.817      | 0.715        | -                | 0.380 (0.222)    | 1 (0.817) |     8.08 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1762 | 2024-05-22 | Liquid            | L   | 0.725      | -            | -                | -                | -         |   -16.55 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1808 | 2024-05-21 | Aurora            | W   | 0.718      | 0.769        | 0.431 (0.238)    | 0.798 (0.441)    | -         |     6.35 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1840 | 2024-05-20 | BetBoom           | W   | 0.713      | 0.769        | 0.257 (0.141)    | 0.551 (0.302)    | -         |     2.99 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1868 | 2024-05-19 | BIG               | W   | 0.707      | -            | -                | -                | -         |     1.44 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2174 | 2024-05-11 | Vitality          | L   | 0.652      | -            | -                | -                | -         |    -6.40 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2193 | 2024-05-10 | Liquid            | W   | 0.646      | 0.889        | 0.321 (0.184)    | 0.467 (0.268)    | 1 (0.646) |     5.33 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2465 | 2024-04-27 | 3DMAX             | W   | 0.559      | 0.889        | 0.505 (0.251)    | 1.000 (0.497)    | 1 (0.559) |     6.75 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2536 | 2024-04-24 | FaZe              | W   | 0.540      | 0.889        | 0.637 (0.306)    | -                | 1 (0.540) |     9.52 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2558 | 2024-04-23 | Eternal Fire      | W   | 0.533      | 0.889        | 0.757 (0.358)    | 0.461 (0.218)    | 1 (0.533) |     8.93 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2853 | 2024-04-13 | FaZe              | L   | 0.465      | -            | -                | -                | -         |    -6.60 | br0, device, jabbi, Staehr, stavn    |
|            9 |     2954 | 2024-04-10 | Virtus.pro        | W   | 0.444      | 0.624        | 0.484 (0.134)    | -                | -         |     7.35 | br0, device, jabbi, Staehr, stavn    |
|            8 |     3002 | 2024-04-09 | FaZe              | W   | 0.438      | 0.624        | 0.637 (0.174)    | -                | -         |     7.79 | br0, device, jabbi, Staehr, stavn    |
|            7 |     3034 | 2024-04-08 | Steel Helmet      | W   | 0.431      | -            | -                | -                | -         |     0.03 | br0, device, jabbi, Staehr, stavn    |
|            6 |     4037 | 2024-02-23 | 9 Pandas          | L   | 0.131      | -            | -                | -                | -         |    -4.05 | blameF, device, jabbi, Staehr, stavn |
|            5 |     4057 | 2024-02-22 | ENCE              | L   | 0.125      | -            | -                | -                | -         |    -2.99 | blameF, device, jabbi, Staehr, stavn |
|            4 |     4086 | 2024-02-21 | Monte             | W   | 0.118      | -            | -                | -                | -         |     0.08 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4111 | 2024-02-20 | HEROIC            | L   | 0.112      | -            | -                | -                | -         |    -2.29 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4126 | 2024-02-19 | Spirit            | L   | 0.107      | -            | -                | -                | -         |    -0.76 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4136 | 2024-02-19 | Nexus             | W   | 0.105      | -            | -                | -                | -         |     0.03 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($117,219.91)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.36) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.892 | $20,000.00     | $17,844.44      |
| 2024-06-09 |      0.846 | $28,000.00     | $23,683.33      |
| 2024-05-23 |      0.732 | $50,000.00     | $36,604.17      |
| 2024-05-12 |      0.659 | $45,000.00     | $29,662.50      |
| 2024-04-14 |      0.471 | $20,000.00     | $9,425.46       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
