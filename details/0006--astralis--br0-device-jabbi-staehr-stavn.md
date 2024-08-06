### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1704.3<br />
<br />
Final Rank Value (1704.3) = Starting Rank Value (1728.2) + Head To Head Adjustments (-23.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.709[<sup>1</sup>](#table2)
- Bounty Collected: 0.619[<sup>2</sup>](#table1)
- Opponent Network: 0.313[<sup>2</sup>](#table1)
- LAN Wins: 0.941[<sup>2</sup>](#table1)

The average of these factors is 0.646<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1728.2
- 400 + ( ( 0.646 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1728.2


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
|           34 |       47 | 2024-08-04 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | 0.254 (0.147)    | 0.531 (0.309)    | 1 (1.000) |    10.63 | br0, device, jabbi, Staehr, stavn    |
|           33 |       79 | 2024-08-03 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.51 | br0, device, jabbi, Staehr, stavn    |
|           32 |      118 | 2024-08-02 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.73 | br0, device, jabbi, Staehr, stavn    |
|           31 |      243 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |   -10.03 | br0, device, jabbi, Staehr, stavn    |
|           30 |      271 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.63 | br0, device, jabbi, Staehr, stavn    |
|           29 |     1094 | 2024-06-14 | Virtus.pro        | L   | 0.849      | -            | -                | -                | -         |   -15.21 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1153 | 2024-06-13 | SAW               | W   | 0.840      | 0.729        | -                | 0.516 (0.316)    | 1 (0.840) |     1.15 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1176 | 2024-06-12 | Natus Vincere     | L   | 0.834      | -            | -                | -                | -         |    -6.59 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1337 | 2024-06-08 | The MongolZ       | L   | 0.807      | -            | -                | -                | -         |    -7.24 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1392 | 2024-06-07 | BetBoom           | W   | 0.801      | 0.715        | 0.248 (0.142)    | 0.514 (0.294)    | 1 (0.801) |     3.82 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1439 | 2024-06-06 | The MongolZ       | W   | 0.795      | 0.715        | 1.000 (0.569)    | 0.694 (0.395)    | 1 (0.795) |    18.48 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1459 | 2024-06-06 | ENCE              | W   | 0.794      | 0.715        | -                | 0.422 (0.239)    | 1 (0.794) |     3.06 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1469 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.793      | -            | -                | -                | -         |   -17.08 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1515 | 2024-06-05 | Sashi             | L   | 0.787      | -            | -                | -                | -         |   -23.64 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1528 | 2024-06-05 | HEROIC            | W   | 0.786      | 0.715        | -                | 0.355 (0.199)    | 1 (0.786) |     6.84 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1877 | 2024-05-22 | Liquid            | L   | 0.693      | -            | -                | -                | -         |   -15.23 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1918 | 2024-05-21 | Aurora            | W   | 0.687      | 0.769        | 0.421 (0.222)    | 0.759 (0.401)    | -         |     5.46 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1948 | 2024-05-20 | BetBoom           | W   | 0.681      | 0.769        | 0.248 (0.130)    | 0.514 (0.269)    | -         |     2.33 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1968 | 2024-05-19 | BIG               | W   | 0.675      | -            | -                | -                | -         |     1.63 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2264 | 2024-05-11 | Vitality          | L   | 0.621      | -            | -                | -                | -         |    -6.73 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2283 | 2024-05-10 | Liquid            | W   | 0.614      | 0.889        | 0.383 (0.209)    | 0.438 (0.239)    | 1 (0.614) |     5.66 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2550 | 2024-04-27 | 3DMAX             | W   | 0.528      | 0.889        | 0.510 (0.239)    | 1.000 (0.469)    | 1 (0.528) |     5.87 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2621 | 2024-04-24 | FaZe              | W   | 0.508      | 0.889        | 0.626 (0.283)    | -                | -         |     7.48 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2641 | 2024-04-23 | Eternal Fire      | W   | 0.501      | 0.889        | 0.739 (0.329)    | -                | -         |     7.18 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2928 | 2024-04-13 | FaZe              | L   | 0.433      | -            | -                | -                | -         |    -7.50 | br0, device, jabbi, Staehr, stavn    |
|            9 |     3028 | 2024-04-10 | Virtus.pro        | W   | 0.413      | -            | -                | -                | -         |     5.89 | br0, device, jabbi, Staehr, stavn    |
|            8 |     3076 | 2024-04-09 | FaZe              | W   | 0.406      | 0.624        | 0.626 (0.159)    | -                | -         |     5.87 | br0, device, jabbi, Staehr, stavn    |
|            7 |     3108 | 2024-04-08 | Steel Helmet      | W   | 0.399      | -            | -                | -                | -         |     0.02 | br0, device, jabbi, Staehr, stavn    |
|            6 |     4079 | 2024-02-23 | 9 Pandas          | L   | 0.100      | -            | -                | -                | -         |    -3.10 | blameF, device, jabbi, Staehr, stavn |
|            5 |     4098 | 2024-02-22 | ENCE              | L   | 0.093      | -            | -                | -                | -         |    -2.35 | blameF, device, jabbi, Staehr, stavn |
|            4 |     4125 | 2024-02-21 | Monte             | W   | 0.087      | -            | -                | -                | -         |     0.04 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4151 | 2024-02-20 | HEROIC            | L   | 0.080      | -            | -                | -                | -         |    -1.82 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4166 | 2024-02-19 | Spirit            | L   | 0.076      | -            | -                | -                | -         |    -0.65 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4176 | 2024-02-19 | Nexus             | W   | 0.074      | -            | -                | -                | -         |     0.02 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($124,603.52)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.39) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-16 |      0.861 | $20,000.00     | $17,216.67      |
| 2024-06-09 |      0.814 | $28,000.00     | $22,804.44      |
| 2024-05-23 |      0.701 | $50,000.00     | $35,034.72      |
| 2024-05-12 |      0.628 | $45,000.00     | $28,250.00      |
| 2024-04-14 |      0.440 | $20,000.00     | $8,797.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
