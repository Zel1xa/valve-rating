### Roster Details<br />
Team Name: Revenant<br />
Roster: 0SAMAS, lauNX, NBK-, Nivera, reiko<br />
Global Rank: [74](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  918.8<br />
<br />
Final Rank Value (918.8) = Starting Rank Value (915.1) + Head To Head Adjustments (3.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.422[<sup>1</sup>](#table2)
- Bounty Collected: 0.353[<sup>2</sup>](#table1)
- Opponent Network: 0.289[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 915.1
- 400 + ( ( 0.266 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 915.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           48 |       27 | 2024-09-07 | DMS               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.09 | 0SAMAS, lauNX, NBK-, Nivera, reiko  |
|           47 |       42 | 2024-09-06 | JANO              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.86 | ADRON, lauNX, NBK-, Nivera, reiko   |
|           46 |       99 | 2024-09-05 | Gaimin Gladiators | L   | 1.000      | -            | -                | -                | -         |   -13.48 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           45 |      164 | 2024-09-03 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -12.61 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           44 |      176 | 2024-09-02 | FAVBET            | W   | 1.000      | 0.435        | -                | 0.655 (0.285)    | 0 (0.000) |    11.90 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           43 |      186 | 2024-09-02 | SINNERS           | L   | 1.000      | -            | -                | -                | -         |    -7.29 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           42 |      216 | 2024-08-31 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -15.09 | NBK-, Nivera, prosus, reiko, tiziaN |
|           41 |      231 | 2024-08-30 | Sampi             | W   | 1.000      | 0.435        | 0.032 (0.014)    | 1.000 (0.435)    | 0 (0.000) |    14.47 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           40 |      279 | 2024-08-29 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -17.86 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           39 |      288 | 2024-08-29 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.95 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           38 |      388 | 2024-08-27 | Endpoint          | W   | 1.000      | 0.435        | 0.065 (0.028)    | 0.723 (0.314)    | 0 (0.000) |    17.15 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           37 |      507 | 2024-08-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.05 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           36 |      526 | 2024-08-24 | ECSTATIC          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.63 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           35 |      553 | 2024-08-23 | Verdant           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.09 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           34 |      582 | 2024-08-22 | Alliance          | L   | 1.000      | -            | -                | -                | -         |   -21.16 | adeX, lauNX, NBK-, Nivera, reiko    |
|           33 |      654 | 2024-08-21 | DMS               | W   | 1.000      | 0.435        | -                | 0.486 (0.211)    | 0 (0.000) |    12.68 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           32 |      676 | 2024-08-21 | ENCE Academy      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.12 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           31 |      687 | 2024-08-20 | Monte Gen         | L   | 1.000      | -            | -                | -                | -         |   -19.36 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           30 |      696 | 2024-08-20 | Enterprise        | L   | 1.000      | -            | -                | -                | -         |   -18.10 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           29 |      741 | 2024-08-18 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -14.40 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           28 |      788 | 2024-08-16 | Nexus             | W   | 1.000      | 0.435        | -                | 0.432 (0.188)    | 0 (0.000) |     8.69 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           27 |      796 | 2024-08-16 | Sampi             | W   | 1.000      | 0.371        | 0.032 (0.012)    | 1.000 (0.371)    | -         |    10.92 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           26 |      844 | 2024-08-14 | Aurora Young Blud | W   | 1.000      | 0.435        | 0.019 (0.008)    | 0.711 (0.309)    | -         |    17.65 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           25 |      901 | 2024-08-13 | UNiTY             | W   | 1.000      | 0.333        | 0.026 (0.009)    | -                | -         |    15.36 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           24 |      942 | 2024-08-12 | kONO              | W   | 1.000      | 0.333        | 0.025 (0.008)    | -                | -         |    13.60 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           23 |      961 | 2024-08-11 | UNiTY             | L   | 1.000      | -            | -                | -                | -         |   -15.55 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           22 |     1010 | 2024-08-09 | TSM               | W   | 0.999      | 0.333        | 0.058 (0.019)    | 0.900 (0.300)    | -         |    19.30 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           21 |     1070 | 2024-08-07 | ECLOT             | W   | 0.987      | 0.333        | 0.047 (0.015)    | 0.698 (0.230)    | -         |    19.52 | lauNX, NBK-, Nivera, reiko, tiziaN  |
|           20 |     1168 | 2024-08-04 | Monte Gen         | L   | 0.967      | -            | -                | -                | -         |   -17.15 | HS, lauNX, NBK-, Nivera, reiko      |
|           19 |     1503 | 2024-07-26 | DMS               | L   | 0.905      | -            | -                | -                | -         |   -15.56 | adeX, Jeebs, NBK-, Nivera, reiko    |
|           18 |     1529 | 2024-07-25 | 3DMAX             | L   | 0.900      | -            | -                | -                | -         |    -1.22 | adeX, Jeebs, NBK-, Nivera, reiko    |
|           17 |     1559 | 2024-07-24 | AMKAL             | L   | 0.894      | -            | -                | -                | -         |    -6.32 | adeX, lauNX, NBK-, Nivera, reiko    |
|           16 |     1574 | 2024-07-24 | Eternal Fire      | L   | 0.892      | -            | -                | -                | -         |    -0.23 | adeX, lauNX, NBK-, Nivera, reiko    |
|           15 |     2002 | 2024-07-12 | Verdant           | W   | 0.812      | -            | -                | -                | -         |     9.32 | adeX, lauNX, NBK-, Nivera, reiko    |
|           14 |     2062 | 2024-07-09 | Johnny Speeds     | W   | 0.792      | 0.333        | 0.102 (0.027)    | 0.956 (0.252)    | -         |    19.55 | adeX, lauNX, NBK-, Nivera, reiko    |
|           13 |     2079 | 2024-07-08 | Enterprise        | L   | 0.786      | -            | -                | -                | -         |   -12.35 | adeX, lauNX, NBK-, Nivera, reiko    |
|           12 |     2082 | 2024-07-08 | lajtbitexe        | W   | 0.785      | -            | -                | -                | -         |     6.13 | adeX, lauNX, NBK-, Nivera, reiko    |
|           11 |     2086 | 2024-07-07 | kONO              | W   | 0.779      | 0.333        | 0.025 (0.006)    | -                | -         |    10.63 | adeX, lauNX, NBK-, Nivera, reiko    |
|           10 |     2089 | 2024-07-06 | 777               | W   | 0.774      | -            | -                | -                | -         |     5.65 | adeX, lauNX, NBK-, Nivera, reiko    |
|            9 |     2094 | 2024-07-05 | lajtbitexe        | L   | 0.766      | -            | -                | -                | -         |   -18.13 | adeX, lauNX, NBK-, Nivera, reiko    |
|            8 |     2125 | 2024-06-27 | Johnny Speeds     | L   | 0.712      | -            | -                | -                | -         |    -5.00 | adeX, lauNX, NBK-, Nivera, reiko    |
|            7 |     2128 | 2024-06-26 | lajtbitexe        | W   | 0.705      | -            | -                | -                | -         |     5.24 | adeX, lauNX, NBK-, Nivera, reiko    |
|            6 |     2129 | 2024-06-25 | Johnny Speeds     | L   | 0.699      | -            | -                | -                | -         |    -5.01 | adeX, lauNX, NBK-, Nivera, reiko    |
|            5 |     2137 | 2024-06-23 | Heimo             | W   | 0.685      | -            | -                | -                | -         |     3.88 | adeX, lauNX, NBK-, Nivera, reiko    |
|            4 |     2160 | 2024-06-16 | CYBERSHOKE        | L   | 0.641      | -            | -                | -                | -         |    -9.99 | adeX, lauNX, NBK-, Nivera, reiko    |
|            3 |     2189 | 2024-06-15 | Verdant           | W   | 0.635      | -            | -                | -                | -         |     8.27 | adeX, lauNX, NBK-, Nivera, reiko    |
|            2 |     2247 | 2024-06-14 | Astralis Talent   | W   | 0.626      | -            | -                | -                | -         |     4.18 | adeX, lauNX, NBK-, Nivera, reiko    |
|            1 |     2274 | 2024-06-13 | Verdant           | L   | 0.621      | -            | -                | -                | -         |   -11.32 | adeX, lauNX, NBK-, Nivera, reiko    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,887.50)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-13 |      1.000 | $6,000.00      | $6,000.00       |
| 2024-07-09 |      0.792 | $6,000.00      | $4,751.67       |
| 2024-06-27 |      0.712 | $3,000.00      | $2,135.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
