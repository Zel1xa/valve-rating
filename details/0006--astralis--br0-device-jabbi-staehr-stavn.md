### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, device, jabbi, Staehr, stavn<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1704.5<br />
<br />
Final Rank Value (1704.5) = Starting Rank Value (1728.4) + Head To Head Adjustments (-23.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.709[<sup>1</sup>](#table2)
- Bounty Collected: 0.619[<sup>2</sup>](#table1)
- Opponent Network: 0.319[<sup>2</sup>](#table1)
- LAN Wins: 0.941[<sup>2</sup>](#table1)

The average of these factors is 0.647<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1728.4
- 400 + ( ( 0.647 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1728.4


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
|           34 |       43 | 2024-08-04 | Ninjas in Pyjamas | W   | 1.000      | 0.581        | 0.254 (0.147)    | 0.543 (0.316)    | 1 (1.000) |    10.65 | br0, device, jabbi, Staehr, stavn    |
|           33 |       75 | 2024-08-03 | Vitality          | L   | 1.000      | -            | -                | -                | -         |    -9.51 | br0, device, jabbi, Staehr, stavn    |
|           32 |      114 | 2024-08-02 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.72 | br0, device, jabbi, Staehr, stavn    |
|           31 |      239 | 2024-07-30 | Vitality          | L   | 1.000      | -            | -                | -                | -         |   -10.03 | br0, device, jabbi, Staehr, stavn    |
|           30 |      267 | 2024-07-29 | Falcons           | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.62 | br0, device, jabbi, Staehr, stavn    |
|           29 |     1090 | 2024-06-14 | Virtus.pro        | L   | 0.849      | -            | -                | -                | -         |   -15.21 | br0, device, jabbi, Staehr, stavn    |
|           28 |     1149 | 2024-06-13 | SAW               | W   | 0.840      | 0.729        | -                | 0.528 (0.324)    | 1 (0.840) |     1.16 | br0, device, jabbi, Staehr, stavn    |
|           27 |     1172 | 2024-06-12 | Natus Vincere     | L   | 0.834      | -            | -                | -                | -         |    -6.60 | br0, device, jabbi, Staehr, stavn    |
|           26 |     1333 | 2024-06-08 | The MongolZ       | L   | 0.807      | -            | -                | -                | -         |    -7.22 | br0, device, jabbi, Staehr, stavn    |
|           25 |     1388 | 2024-06-07 | BetBoom           | W   | 0.801      | 0.715        | 0.248 (0.142)    | 0.526 (0.301)    | 1 (0.801) |     3.82 | br0, device, jabbi, Staehr, stavn    |
|           24 |     1435 | 2024-06-06 | The MongolZ       | W   | 0.795      | 0.715        | 1.000 (0.569)    | 0.709 (0.404)    | 1 (0.795) |    18.51 | br0, device, jabbi, Staehr, stavn    |
|           23 |     1455 | 2024-06-06 | ENCE              | W   | 0.794      | 0.715        | -                | 0.431 (0.245)    | 1 (0.794) |     3.06 | br0, device, jabbi, Staehr, stavn    |
|           22 |     1465 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.793      | -            | -                | -                | -         |   -17.06 | br0, device, jabbi, Staehr, stavn    |
|           21 |     1511 | 2024-06-05 | Sashi             | L   | 0.788      | -            | -                | -                | -         |   -23.64 | br0, device, jabbi, Staehr, stavn    |
|           20 |     1524 | 2024-06-05 | HEROIC            | W   | 0.786      | 0.715        | -                | 0.363 (0.204)    | 1 (0.786) |     6.86 | br0, device, jabbi, Staehr, stavn    |
|           19 |     1873 | 2024-05-22 | Liquid            | L   | 0.693      | -            | -                | -                | -         |   -15.24 | br0, device, jabbi, Staehr, stavn    |
|           18 |     1914 | 2024-05-21 | Aurora            | W   | 0.687      | 0.769        | 0.421 (0.222)    | 0.776 (0.410)    | -         |     5.41 | br0, device, jabbi, Staehr, stavn    |
|           17 |     1944 | 2024-05-20 | BetBoom           | W   | 0.682      | 0.769        | 0.248 (0.130)    | 0.526 (0.275)    | -         |     2.33 | br0, device, jabbi, Staehr, stavn    |
|           16 |     1964 | 2024-05-19 | BIG               | W   | 0.676      | -            | -                | -                | -         |     1.63 | br0, device, jabbi, Staehr, stavn    |
|           15 |     2260 | 2024-05-11 | Vitality          | L   | 0.621      | -            | -                | -                | -         |    -6.74 | br0, device, jabbi, Staehr, stavn    |
|           14 |     2279 | 2024-05-10 | Liquid            | W   | 0.615      | 0.889        | 0.383 (0.209)    | 0.448 (0.244)    | 1 (0.615) |     5.66 | br0, device, jabbi, Staehr, stavn    |
|           13 |     2546 | 2024-04-27 | 3DMAX             | W   | 0.528      | 0.889        | 0.509 (0.239)    | 1.000 (0.469)    | 1 (0.528) |     5.87 | br0, device, jabbi, Staehr, stavn    |
|           12 |     2617 | 2024-04-24 | FaZe              | W   | 0.509      | 0.889        | 0.626 (0.283)    | -                | -         |     7.48 | br0, device, jabbi, Staehr, stavn    |
|           11 |     2637 | 2024-04-23 | Eternal Fire      | W   | 0.501      | 0.889        | 0.739 (0.329)    | -                | -         |     7.17 | br0, device, jabbi, Staehr, stavn    |
|           10 |     2924 | 2024-04-13 | FaZe              | L   | 0.434      | -            | -                | -                | -         |    -7.51 | br0, device, jabbi, Staehr, stavn    |
|            9 |     3024 | 2024-04-10 | Virtus.pro        | W   | 0.413      | -            | -                | -                | -         |     5.89 | br0, device, jabbi, Staehr, stavn    |
|            8 |     3072 | 2024-04-09 | FaZe              | W   | 0.406      | 0.624        | 0.626 (0.159)    | -                | -         |     5.87 | br0, device, jabbi, Staehr, stavn    |
|            7 |     3104 | 2024-04-08 | Steel Helmet      | W   | 0.399      | -            | -                | -                | -         |     0.02 | br0, device, jabbi, Staehr, stavn    |
|            6 |     4075 | 2024-02-23 | 9 Pandas          | L   | 0.100      | -            | -                | -                | -         |    -3.11 | blameF, device, jabbi, Staehr, stavn |
|            5 |     4094 | 2024-02-22 | ENCE              | L   | 0.094      | -            | -                | -                | -         |    -2.36 | blameF, device, jabbi, Staehr, stavn |
|            4 |     4121 | 2024-02-21 | Monte             | W   | 0.087      | -            | -                | -                | -         |     0.04 | blameF, device, jabbi, Staehr, stavn |
|            3 |     4147 | 2024-02-20 | HEROIC            | L   | 0.081      | -            | -                | -                | -         |    -1.83 | blameF, device, jabbi, Staehr, stavn |
|            2 |     4162 | 2024-02-19 | Spirit            | L   | 0.076      | -            | -                | -                | -         |    -0.65 | blameF, device, jabbi, Staehr, stavn |
|            1 |     4172 | 2024-02-19 | Nexus             | W   | 0.074      | -            | -                | -                | -         |     0.02 | blameF, device, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($124,648.80)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.39) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-16 |      0.861 | $20,000.00     | $17,222.22      |
| 2024-06-09 |      0.815 | $28,000.00     | $22,812.22      |
| 2024-05-23 |      0.701 | $50,000.00     | $35,048.61      |
| 2024-05-12 |      0.628 | $45,000.00     | $28,262.50      |
| 2024-04-14 |      0.440 | $20,000.00     | $8,803.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
