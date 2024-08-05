### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1706.2<br />
<br />
Final Rank Value (1706.2) = Starting Rank Value (1731.9) + Head To Head Adjustments (-25.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.710[<sup>1</sup>](#table2)
- Bounty Collected: 0.623[<sup>2</sup>](#table1)
- Opponent Network: 0.329[<sup>2</sup>](#table1)
- LAN Wins: 0.943[<sup>2</sup>](#table1)

The average of these factors is 0.651<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1731.9
- 400 + ( ( 0.651 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1731.9


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
|           34 |       15 | 2024-08-04 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | 0.254 (0.148)    | 0.553 (0.321)    | 1 (1.000) |    10.57 | br0, device, jabbi, Staehr, stavn    |
|           33 |       47 | 2024-08-03 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.51 | br0, device, jabbi, Staehr, stavn    |
|           32 |       87 | 2024-08-02 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.74 | br0, device, jabbi, Staehr, stavn    |
|           31 |      211 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |   -10.03 | br0, device, jabbi, Staehr, stavn    |
|           30 |      239 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.64 | br0, device, jabbi, Staehr, stavn    |
|           29 |     1062 | 2024-06-14 | Virtus.pro        | L   | 0.858      | -            | -                | -                | -         |   -15.35 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1121 | 2024-06-13 | SAW               | W   | 0.849      | 0.729        | -                | 0.539 (0.334)    | 1 (0.849) |     1.17 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1144 | 2024-06-12 | Natus Vincere     | L   | 0.843      | -            | -                | -                | -         |    -6.72 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1305 | 2024-06-08 | The MongolZ       | L   | 0.817      | -            | -                | -                | -         |    -7.41 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1360 | 2024-06-07 | BetBoom           | W   | 0.810      | 0.715        | 0.250 (0.145)    | 0.540 (0.313)    | 1 (0.810) |     3.85 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1407 | 2024-06-06 | The MongolZ       | W   | 0.804      | 0.715        | 1.000 (0.575)    | 0.721 (0.415)    | 1 (0.804) |    18.62 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1427 | 2024-06-06 | ENCE              | W   | 0.803      | 0.715        | -                | 0.439 (0.252)    | 1 (0.803) |     2.99 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1437 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.802      | -            | -                | -                | -         |   -17.36 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1483 | 2024-06-05 | Sashi             | L   | 0.797      | -            | -                | -                | -         |   -23.94 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1496 | 2024-06-05 | HEROIC            | W   | 0.795      | 0.715        | -                | 0.372 (0.212)    | 1 (0.795) |     6.94 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1845 | 2024-05-22 | Liquid            | L   | 0.703      | -            | -                | -                | -         |   -15.49 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1886 | 2024-05-21 | Aurora            | W   | 0.697      | 0.769        | 0.423 (0.226)    | 0.792 (0.424)    | -         |     5.29 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1916 | 2024-05-20 | BetBoom           | W   | 0.691      | 0.769        | 0.250 (0.133)    | 0.540 (0.287)    | -         |     2.34 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1936 | 2024-05-19 | BIG               | W   | 0.685      | -            | -                | -                | -         |     1.63 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2232 | 2024-05-11 | Vitality          | L   | 0.630      | -            | -                | -                | -         |    -6.86 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2251 | 2024-05-10 | Liquid            | W   | 0.624      | 0.889        | 0.384 (0.213)    | 0.459 (0.254)    | 1 (0.624) |     5.69 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2518 | 2024-04-27 | 3DMAX             | W   | 0.537      | 0.889        | 0.507 (0.242)    | 1.000 (0.477)    | 1 (0.537) |     5.77 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2589 | 2024-04-24 | FaZe              | W   | 0.518      | 0.889        | 0.635 (0.293)    | -                | -         |     7.69 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2609 | 2024-04-23 | Eternal Fire      | W   | 0.511      | 0.889        | 0.741 (0.336)    | -                | -         |     7.27 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2896 | 2024-04-13 | FaZe              | L   | 0.443      | -            | -                | -                | -         |    -7.60 | br0, device, jabbi, Staehr, stavn    |
|            9 |     2996 | 2024-04-10 | Virtus.pro        | W   | 0.422      | -            | -                | -                | -         |     6.02 | br0, device, jabbi, Staehr, stavn    |
|            8 |     3044 | 2024-04-09 | FaZe              | W   | 0.416      | 0.624        | 0.635 (0.165)    | -                | -         |     6.07 | br0, device, jabbi, Staehr, stavn    |
|            7 |     3076 | 2024-04-08 | Steel Helmet      | W   | 0.409      | -            | -                | -                | -         |     0.02 | br0, device, jabbi, Staehr, stavn    |
|            6 |     4047 | 2024-02-23 | 9 Pandas          | L   | 0.109      | -            | -                | -                | -         |    -3.39 | blameF, device, jabbi, Staehr, stavn |
|            5 |     4066 | 2024-02-22 | ENCE              | L   | 0.103      | -            | -                | -                | -         |    -2.61 | blameF, device, jabbi, Staehr, stavn |
|            4 |     4093 | 2024-02-21 | Monte             | W   | 0.096      | -            | -                | -                | -         |     0.05 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4119 | 2024-02-20 | HEROIC            | L   | 0.090      | -            | -                | -                | -         |    -2.04 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4134 | 2024-02-19 | Spirit            | L   | 0.085      | -            | -                | -                | -         |    -0.74 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4144 | 2024-02-19 | Nexus             | W   | 0.083      | -            | -                | -                | -         |     0.02 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($126,142.96)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.39) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-16 |      0.870 | $20,000.00     | $17,405.56      |
| 2024-06-09 |      0.824 | $28,000.00     | $23,068.89      |
| 2024-05-23 |      0.710 | $50,000.00     | $35,506.94      |
| 2024-05-12 |      0.637 | $45,000.00     | $28,675.00      |
| 2024-04-14 |      0.449 | $20,000.00     | $8,986.57       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
