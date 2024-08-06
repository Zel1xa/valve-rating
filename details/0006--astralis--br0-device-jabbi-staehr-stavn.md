### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1704.2<br />
<br />
Final Rank Value (1704.2) = Starting Rank Value (1728.0) + Head To Head Adjustments (-23.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.709[<sup>1</sup>](#table2)
- Bounty Collected: 0.619[<sup>2</sup>](#table1)
- Opponent Network: 0.313[<sup>2</sup>](#table1)
- LAN Wins: 0.941[<sup>2</sup>](#table1)

The average of these factors is 0.646<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1728.0
- 400 + ( ( 0.646 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1728.0


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
|           34 |       49 | 2024-08-04 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | 0.254 (0.147)    | 0.531 (0.309)    | 1 (1.000) |    10.64 | br0, device, jabbi, Staehr, stavn    |
|           33 |       81 | 2024-08-03 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.50 | br0, device, jabbi, Staehr, stavn    |
|           32 |      120 | 2024-08-02 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.73 | br0, device, jabbi, Staehr, stavn    |
|           31 |      245 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |   -10.03 | br0, device, jabbi, Staehr, stavn    |
|           30 |      273 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.62 | br0, device, jabbi, Staehr, stavn    |
|           29 |     1096 | 2024-06-14 | Virtus.pro        | L   | 0.848      | -            | -                | -                | -         |   -15.20 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1155 | 2024-06-13 | SAW               | W   | 0.840      | 0.729        | -                | 0.516 (0.316)    | 1 (0.840) |     1.15 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1178 | 2024-06-12 | Natus Vincere     | L   | 0.834      | -            | -                | -                | -         |    -6.58 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1339 | 2024-06-08 | The MongolZ       | L   | 0.807      | -            | -                | -                | -         |    -7.24 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1394 | 2024-06-07 | BetBoom           | W   | 0.800      | 0.715        | 0.248 (0.142)    | 0.514 (0.294)    | 1 (0.800) |     3.82 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1441 | 2024-06-06 | The MongolZ       | W   | 0.795      | 0.715        | 1.000 (0.568)    | 0.694 (0.394)    | 1 (0.795) |    18.48 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1461 | 2024-06-06 | ENCE              | W   | 0.793      | 0.715        | -                | 0.422 (0.239)    | 1 (0.793) |     3.07 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1471 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.793      | -            | -                | -                | -         |   -17.07 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1517 | 2024-06-05 | Sashi             | L   | 0.787      | -            | -                | -                | -         |   -23.63 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1530 | 2024-06-05 | HEROIC            | W   | 0.786      | 0.715        | -                | 0.355 (0.199)    | 1 (0.786) |     6.84 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1879 | 2024-05-22 | Liquid            | L   | 0.693      | -            | -                | -                | -         |   -15.22 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1920 | 2024-05-21 | Aurora            | W   | 0.687      | 0.769        | 0.420 (0.222)    | 0.759 (0.400)    | -         |     5.46 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1950 | 2024-05-20 | BetBoom           | W   | 0.681      | 0.769        | 0.248 (0.130)    | 0.514 (0.269)    | -         |     2.33 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1970 | 2024-05-19 | BIG               | W   | 0.675      | -            | -                | -                | -         |     1.63 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2266 | 2024-05-11 | Vitality          | L   | 0.621      | -            | -                | -                | -         |    -6.73 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2285 | 2024-05-10 | Liquid            | W   | 0.614      | 0.889        | 0.383 (0.209)    | 0.437 (0.239)    | 1 (0.614) |     5.66 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2552 | 2024-04-27 | 3DMAX             | W   | 0.527      | 0.889        | 0.510 (0.239)    | 1.000 (0.469)    | 1 (0.527) |     5.88 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2623 | 2024-04-24 | FaZe              | W   | 0.508      | 0.889        | 0.625 (0.283)    | -                | -         |     7.47 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2643 | 2024-04-23 | Eternal Fire      | W   | 0.501      | 0.889        | 0.739 (0.329)    | -                | -         |     7.18 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2930 | 2024-04-13 | FaZe              | L   | 0.433      | -            | -                | -                | -         |    -7.50 | br0, device, jabbi, Staehr, stavn    |
|            9 |     3030 | 2024-04-10 | Virtus.pro        | W   | 0.412      | -            | -                | -                | -         |     5.88 | br0, device, jabbi, Staehr, stavn    |
|            8 |     3078 | 2024-04-09 | FaZe              | W   | 0.406      | 0.624        | 0.625 (0.158)    | -                | -         |     5.86 | br0, device, jabbi, Staehr, stavn    |
|            7 |     3110 | 2024-04-08 | Steel Helmet      | W   | 0.399      | -            | -                | -                | -         |     0.02 | br0, device, jabbi, Staehr, stavn    |
|            6 |     4081 | 2024-02-23 | 9 Pandas          | L   | 0.100      | -            | -                | -                | -         |    -3.09 | blameF, device, jabbi, Staehr, stavn |
|            5 |     4100 | 2024-02-22 | ENCE              | L   | 0.093      | -            | -                | -                | -         |    -2.34 | blameF, device, jabbi, Staehr, stavn |
|            4 |     4127 | 2024-02-21 | Monte             | W   | 0.086      | -            | -                | -                | -         |     0.04 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4153 | 2024-02-20 | HEROIC            | L   | 0.080      | -            | -                | -                | -         |    -1.81 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4168 | 2024-02-19 | Spirit            | L   | 0.075      | -            | -                | -                | -         |    -0.64 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4178 | 2024-02-19 | Nexus             | W   | 0.074      | -            | -                | -                | -         |     0.02 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($124,543.15)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.39) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-16 |      0.860 | $20,000.00     | $17,209.26      |
| 2024-06-09 |      0.814 | $28,000.00     | $22,794.07      |
| 2024-05-23 |      0.700 | $50,000.00     | $35,016.20      |
| 2024-05-12 |      0.627 | $45,000.00     | $28,233.33      |
| 2024-04-14 |      0.440 | $20,000.00     | $8,790.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
