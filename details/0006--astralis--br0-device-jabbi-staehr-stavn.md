### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1705.8<br />
<br />
Final Rank Value (1705.8) = Starting Rank Value (1732.0) + Head To Head Adjustments (-26.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.710[<sup>1</sup>](#table2)
- Bounty Collected: 0.624[<sup>2</sup>](#table1)
- Opponent Network: 0.329[<sup>2</sup>](#table1)
- LAN Wins: 0.943[<sup>2</sup>](#table1)

The average of these factors is 0.651<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1732.0
- 400 + ( ( 0.651 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1732.0


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
|           34 |        0 | 2024-08-04 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | 0.255 (0.148)    | 0.553 (0.321)    | 1 (1.000) |    10.57 | br0, device, jabbi, Staehr, stavn    |
|           33 |       21 | 2024-08-03 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.49 | br0, device, jabbi, Staehr, stavn    |
|           32 |       61 | 2024-08-02 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.76 | br0, device, jabbi, Staehr, stavn    |
|           31 |      183 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |   -10.01 | br0, device, jabbi, Staehr, stavn    |
|           30 |      211 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.66 | br0, device, jabbi, Staehr, stavn    |
|           29 |     1034 | 2024-06-14 | Virtus.pro        | L   | 0.862      | -            | -                | -                | -         |   -15.40 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1093 | 2024-06-13 | SAW               | W   | 0.853      | 0.729        | -                | 0.540 (0.336)    | 1 (0.853) |     1.17 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1116 | 2024-06-12 | Natus Vincere     | L   | 0.847      | -            | -                | -                | -         |    -6.79 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1277 | 2024-06-08 | The MongolZ       | L   | 0.820      | -            | -                | -                | -         |    -7.48 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1332 | 2024-06-07 | BetBoom           | W   | 0.814      | 0.715        | 0.251 (0.146)    | 0.541 (0.315)    | 1 (0.814) |     3.89 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1379 | 2024-06-06 | The MongolZ       | W   | 0.808      | 0.715        | 1.000 (0.578)    | 0.721 (0.416)    | 1 (0.808) |    18.66 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1399 | 2024-06-06 | ENCE              | W   | 0.807      | 0.715        | -                | 0.400 (0.231)    | 1 (0.807) |     2.93 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1409 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.806      | -            | -                | -                | -         |   -17.44 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1455 | 2024-06-05 | Sashi             | L   | 0.800      | -            | -                | -                | -         |   -24.04 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1468 | 2024-06-05 | HEROIC            | W   | 0.799      | 0.715        | -                | 0.373 (0.213)    | 1 (0.799) |     6.96 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1817 | 2024-05-22 | Liquid            | L   | 0.706      | -            | -                | -                | -         |   -15.63 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1858 | 2024-05-21 | Aurora            | W   | 0.700      | 0.769        | 0.423 (0.228)    | 0.793 (0.427)    | -         |     5.25 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1888 | 2024-05-20 | BetBoom           | W   | 0.694      | 0.769        | 0.251 (0.134)    | 0.541 (0.289)    | -         |     2.37 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1908 | 2024-05-19 | BIG               | W   | 0.688      | -            | -                | -                | -         |     1.64 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2204 | 2024-05-11 | Vitality          | L   | 0.634      | -            | -                | -                | -         |    -6.89 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2223 | 2024-05-10 | Liquid            | W   | 0.627      | 0.889        | 0.384 (0.214)    | 0.460 (0.256)    | 1 (0.627) |     5.65 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2490 | 2024-04-27 | 3DMAX             | W   | 0.541      | 0.889        | 0.506 (0.243)    | 1.000 (0.481)    | 1 (0.541) |     5.77 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2561 | 2024-04-24 | FaZe              | W   | 0.521      | 0.889        | 0.639 (0.296)    | -                | -         |     7.76 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2581 | 2024-04-23 | Eternal Fire      | W   | 0.514      | 0.889        | 0.742 (0.339)    | -                | -         |     7.34 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2868 | 2024-04-13 | FaZe              | L   | 0.446      | -            | -                | -                | -         |    -7.65 | br0, device, jabbi, Staehr, stavn    |
|            9 |     2968 | 2024-04-10 | Virtus.pro        | W   | 0.426      | -            | -                | -                | -         |     6.07 | br0, device, jabbi, Staehr, stavn    |
|            8 |     3016 | 2024-04-09 | FaZe              | W   | 0.419      | 0.624        | 0.639 (0.167)    | -                | -         |     6.13 | br0, device, jabbi, Staehr, stavn    |
|            7 |     3048 | 2024-04-08 | Steel Helmet      | W   | 0.412      | -            | -                | -                | -         |     0.02 | br0, device, jabbi, Staehr, stavn    |
|            6 |     4019 | 2024-02-23 | 9 Pandas          | L   | 0.113      | -            | -                | -                | -         |    -3.50 | blameF, device, jabbi, Staehr, stavn |
|            5 |     4038 | 2024-02-22 | ENCE              | L   | 0.106      | -            | -                | -                | -         |    -2.72 | blameF, device, jabbi, Staehr, stavn |
|            4 |     4065 | 2024-02-21 | Monte             | W   | 0.100      | -            | -                | -                | -         |     0.05 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4091 | 2024-02-20 | HEROIC            | L   | 0.093      | -            | -                | -                | -         |    -2.12 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4106 | 2024-02-19 | Spirit            | L   | 0.089      | -            | -                | -                | -         |    -0.77 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4116 | 2024-02-19 | Nexus             | W   | 0.087      | -            | -                | -                | -         |     0.02 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($126,705.16)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.39) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-16 |      0.874 | $20,000.00     | $17,474.54      |
| 2024-06-09 |      0.827 | $28,000.00     | $23,165.46      |
| 2024-05-23 |      0.714 | $50,000.00     | $35,679.40      |
| 2024-05-12 |      0.641 | $45,000.00     | $28,830.21      |
| 2024-04-14 |      0.453 | $20,000.00     | $9,055.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
