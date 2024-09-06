### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [11](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [9]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  1582.1<br />
<br />
Final Rank Value (1582.1) = Starting Rank Value (1531.2) + Head To Head Adjustments (50.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.683[<sup>1</sup>](#table2)
- Bounty Collected: 0.587[<sup>2</sup>](#table1)
- Opponent Network: 0.290[<sup>2</sup>](#table1)
- LAN Wins: 0.754[<sup>2</sup>](#table1)

The average of these factors is 0.579<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1531.2
- 400 + ( ( 0.579 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 1531.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |      887 | 2024-08-12 | G2                | L   | 1.000      | -            | -                | -                | -         |    -3.22 | br0, device, jabbi, Staehr, stavn |
|           30 |      917 | 2024-08-11 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -3.84 | br0, device, jabbi, Staehr, stavn |
|           29 |      937 | 2024-08-10 | 9z                | W   | 1.000      | 1.000        | 0.342 (0.342)    | 0.550 (0.550)    | 1 (1.000) |     9.89 | br0, device, jabbi, Staehr, stavn |
|           28 |     1138 | 2024-08-04 | Ninjas in Pyjamas | W   | 0.978      | 0.581        | 0.210 (0.119)    | 0.445 (0.253)    | 1 (0.978) |     9.97 | br0, device, jabbi, Staehr, stavn |
|           27 |     1170 | 2024-08-03 | Vitality          | L   | 0.972      | -            | -                | -                | -         |    -4.12 | br0, device, jabbi, Staehr, stavn |
|           26 |     1209 | 2024-08-02 | Falcons           | W   | 0.965      | 0.581        | 0.296 (0.166)    | 0.489 (0.274)    | 1 (0.965) |    12.10 | br0, device, jabbi, Staehr, stavn |
|           25 |     1334 | 2024-07-30 | Vitality          | L   | 0.946      | -            | -                | -                | -         |    -3.93 | br0, device, jabbi, Staehr, stavn |
|           24 |     1362 | 2024-07-29 | Falcons           | W   | 0.940      | 0.581        | 0.296 (0.162)    | 0.489 (0.267)    | 1 (0.940) |    12.53 | br0, device, jabbi, Staehr, stavn |
|           23 |     2188 | 2024-06-14 | Virtus.pro        | L   | 0.640      | -            | -                | -                | -         |   -10.50 | br0, device, jabbi, Staehr, stavn |
|           22 |     2247 | 2024-06-13 | SAW               | W   | 0.631      | 0.729        | 0.326 (0.150)    | 0.770 (0.354)    | 1 (0.631) |     6.35 | br0, device, jabbi, Staehr, stavn |
|           21 |     2270 | 2024-06-12 | Natus Vincere     | L   | 0.625      | -            | -                | -                | -         |    -1.98 | br0, device, jabbi, Staehr, stavn |
|           20 |     2431 | 2024-06-08 | The MongolZ       | L   | 0.599      | -            | -                | -                | -         |    -3.69 | br0, device, jabbi, Staehr, stavn |
|           19 |     2486 | 2024-06-07 | BetBoom           | W   | 0.592      | 0.715        | -                | 0.555 (0.235)    | 1 (0.592) |     3.42 | br0, device, jabbi, Staehr, stavn |
|           18 |     2533 | 2024-06-06 | The MongolZ       | W   | 0.586      | 0.715        | 0.865 (0.363)    | 0.642 (0.269)    | 1 (0.586) |    15.22 | br0, device, jabbi, Staehr, stavn |
|           17 |     2553 | 2024-06-06 | ENCE              | W   | 0.585      | -            | -                | -                | 1 (0.585) |     2.45 | br0, device, jabbi, Staehr, stavn |
|           16 |     2563 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.584      | -            | -                | -                | -         |   -12.73 | br0, device, jabbi, Staehr, stavn |
|           15 |     2609 | 2024-06-05 | Sashi             | L   | 0.579      | -            | -                | -                | -         |   -16.82 | br0, device, jabbi, Staehr, stavn |
|           14 |     2622 | 2024-06-05 | HEROIC            | W   | 0.577      | -            | -                | -                | 1 (0.577) |     5.07 | br0, device, jabbi, Staehr, stavn |
|           13 |     2971 | 2024-05-22 | Liquid            | L   | 0.485      | -            | -                | -                | -         |    -7.32 | br0, device, jabbi, Staehr, stavn |
|           12 |     3012 | 2024-05-21 | Aurora            | W   | 0.478      | 0.769        | -                | 0.629 (0.231)    | -         |     4.14 | br0, device, jabbi, Staehr, stavn |
|           11 |     3042 | 2024-05-20 | BetBoom           | W   | 0.473      | 0.769        | -                | 0.555 (0.202)    | -         |     2.11 | br0, device, jabbi, Staehr, stavn |
|           10 |     3062 | 2024-05-19 | BIG               | W   | 0.467      | -            | -                | -                | -         |     1.78 | br0, device, jabbi, Staehr, stavn |
|            9 |     3358 | 2024-05-11 | Vitality          | L   | 0.412      | -            | -                | -                | -         |    -1.42 | br0, device, jabbi, Staehr, stavn |
|            8 |     3377 | 2024-05-10 | Liquid            | W   | 0.406      | 0.889        | 0.370 (0.133)    | -                | 1 (0.406) |     6.84 | br0, device, jabbi, Staehr, stavn |
|            7 |     3644 | 2024-04-27 | 3DMAX             | W   | 0.319      | 0.889        | 0.470 (0.133)    | 0.946 (0.268)    | -         |     6.52 | br0, device, jabbi, Staehr, stavn |
|            6 |     3715 | 2024-04-24 | FaZe              | W   | 0.300      | 0.889        | 0.592 (0.158)    | -                | -         |     7.38 | br0, device, jabbi, Staehr, stavn |
|            5 |     3735 | 2024-04-23 | Eternal Fire      | W   | 0.292      | 0.889        | 0.969 (0.252)    | -                | -         |     8.00 | br0, device, jabbi, Staehr, stavn |
|            4 |     4022 | 2024-04-13 | FaZe              | L   | 0.225      | -            | -                | -                | -         |    -1.53 | br0, device, jabbi, Staehr, stavn |
|            3 |     4122 | 2024-04-10 | Virtus.pro        | W   | 0.204      | -            | -                | -                | -         |     3.22 | br0, device, jabbi, Staehr, stavn |
|            2 |     4170 | 2024-04-09 | FaZe              | W   | 0.198      | -            | -                | -                | -         |     4.94 | br0, device, jabbi, Staehr, stavn |
|            1 |     4202 | 2024-04-08 | Steel Helmet      | W   | 0.191      | -            | -                | -                | -         |     0.02 | br0, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($106,333.98)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.34) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-18 |      1.000 | $16,000.00     | $16,000.00      |
| 2024-08-04 |      0.979 | $12,500.00     | $12,237.85      |
| 2024-06-16 |      0.652 | $20,000.00     | $13,043.98      |
| 2024-06-09 |      0.606 | $28,000.00     | $16,962.69      |
| 2024-05-23 |      0.492 | $50,000.00     | $24,603.01      |
| 2024-05-12 |      0.419 | $45,000.00     | $18,861.46      |
| 2024-04-14 |      0.231 | $20,000.00     | $4,625.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
