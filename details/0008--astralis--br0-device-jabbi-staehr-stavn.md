### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1670.9<br />
<br />
Final Rank Value (1670.9) = Starting Rank Value (1694.3) + Head To Head Adjustments (-23.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.689[<sup>1</sup>](#table2)
- Bounty Collected: 0.622[<sup>2</sup>](#table1)
- Opponent Network: 0.329[<sup>2</sup>](#table1)
- LAN Wins: 0.890[<sup>2</sup>](#table1)

The average of these factors is 0.633<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1694.3
- 400 + ( ( 0.633 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1694.3


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
|           33 |        8 | 2024-08-03 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -8.68 | br0, device, jabbi, Staehr, stavn    |
|           32 |       41 | 2024-08-02 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     6.50 | br0, device, jabbi, Staehr, stavn    |
|           31 |      149 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.08 | br0, device, jabbi, Staehr, stavn    |
|           30 |      177 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     6.46 | br0, device, jabbi, Staehr, stavn    |
|           29 |      974 | 2024-06-14 | Virtus.pro        | L   | 0.867      | -            | -                | -                | -         |   -14.62 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1031 | 2024-06-13 | SAW               | W   | 0.858      | 0.729        | -                | 0.560 (0.350)    | 1 (0.858) |     1.34 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1052 | 2024-06-12 | Natus Vincere     | L   | 0.852      | -            | -                | -                | -         |    -5.95 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1207 | 2024-06-08 | The MongolZ       | L   | 0.826      | -            | -                | -                | -         |    -6.70 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1260 | 2024-06-07 | BetBoom           | W   | 0.819      | 0.715        | 0.252 (0.148)    | 0.563 (0.330)    | 1 (0.819) |     4.41 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1307 | 2024-06-06 | The MongolZ       | W   | 0.813      | 0.715        | 1.000 (0.582)    | 0.745 (0.433)    | 1 (0.813) |    19.62 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1327 | 2024-06-06 | ENCE              | W   | 0.812      | 0.715        | -                | 0.415 (0.241)    | 1 (0.812) |     3.21 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1337 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.811      | -            | -                | -                | -         |   -17.92 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1383 | 2024-06-05 | Sashi             | L   | 0.806      | -            | -                | -                | -         |   -23.98 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1396 | 2024-06-05 | HEROIC            | W   | 0.804      | 0.715        | -                | 0.388 (0.223)    | 1 (0.804) |     7.77 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1741 | 2024-05-22 | Liquid            | L   | 0.712      | -            | -                | -                | -         |   -16.75 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1782 | 2024-05-21 | Aurora            | W   | 0.705      | 0.769        | 0.425 (0.230)    | 0.809 (0.439)    | -         |     6.08 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1812 | 2024-05-20 | BetBoom           | W   | 0.700      | 0.769        | 0.252 (0.136)    | 0.563 (0.303)    | -         |     2.79 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1832 | 2024-05-19 | BIG               | W   | 0.694      | -            | -                | -                | -         |     2.00 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2127 | 2024-05-11 | Vitality          | L   | 0.639      | -            | -                | -                | -         |    -6.04 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2146 | 2024-05-10 | Liquid            | W   | 0.633      | 0.889        | 0.316 (0.178)    | 0.478 (0.269)    | 1 (0.633) |     4.79 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2412 | 2024-04-27 | 3DMAX             | W   | 0.546      | 0.889        | 0.504 (0.245)    | 1.000 (0.485)    | 1 (0.546) |     6.40 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2482 | 2024-04-24 | FaZe              | W   | 0.527      | 0.889        | 0.644 (0.302)    | -                | 1 (0.527) |     8.73 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2502 | 2024-04-23 | Eternal Fire      | W   | 0.520      | 0.889        | 0.746 (0.344)    | 0.474 (0.219)    | -         |     8.26 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2789 | 2024-04-13 | FaZe              | L   | 0.452      | -            | -                | -                | -         |    -6.91 | br0, device, jabbi, Staehr, stavn    |
|            9 |     2889 | 2024-04-10 | Virtus.pro        | W   | 0.431      | 0.624        | 0.496 (0.133)    | -                | -         |     6.87 | br0, device, jabbi, Staehr, stavn    |
|            8 |     2937 | 2024-04-09 | FaZe              | W   | 0.425      | 0.624        | 0.644 (0.171)    | -                | -         |     7.07 | br0, device, jabbi, Staehr, stavn    |
|            7 |     2969 | 2024-04-08 | Steel Helmet      | W   | 0.418      | -            | -                | -                | -         |     0.02 | br0, device, jabbi, Staehr, stavn    |
|            6 |     3932 | 2024-02-23 | 9 Pandas          | L   | 0.118      | -            | -                | -                | -         |    -3.65 | blameF, device, jabbi, Staehr, stavn |
|            5 |     3951 | 2024-02-22 | ENCE              | L   | 0.112      | -            | -                | -                | -         |    -2.74 | blameF, device, jabbi, Staehr, stavn |
|            4 |     3979 | 2024-02-21 | Monte             | W   | 0.105      | -            | -                | -                | -         |     0.07 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4004 | 2024-02-20 | HEROIC            | L   | 0.099      | -            | -                | -                | -         |    -2.09 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4019 | 2024-02-19 | Spirit            | L   | 0.094      | -            | -                | -                | -         |    -0.68 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4029 | 2024-02-19 | Nexus             | W   | 0.092      | -            | -                | -                | -         |     0.02 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($115,099.40)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.35) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.879 | $20,000.00     | $17,584.26      |
| 2024-06-09 |      0.833 | $28,000.00     | $23,319.07      |
| 2024-05-23 |      0.719 | $50,000.00     | $35,953.70      |
| 2024-05-12 |      0.646 | $45,000.00     | $29,077.08      |
| 2024-04-14 |      0.458 | $20,000.00     | $9,165.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
