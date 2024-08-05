### Roster Details<br />
Team Name: BIG<br />
Roster: JDC, Krimbo, rigoN, syrsoN, tabseN<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1252.8<br />
<br />
Final Rank Value (1252.8) = Starting Rank Value (1253.7) + Head To Head Adjustments (-0.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.555[<sup>1</sup>](#table2)
- Bounty Collected: 0.464[<sup>2</sup>](#table1)
- Opponent Network: 0.158[<sup>2</sup>](#table1)
- LAN Wins: 0.480[<sup>2</sup>](#table1)

The average of these factors is 0.414<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1253.7
- 400 + ( ( 0.414 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1253.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |       13 | 2024-07-31 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.55 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           31 |      897 | 2024-06-15 | Permitta      | L   | 0.890      | -            | -                | -                | -         |   -24.22 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           30 |      925 | 2024-06-14 | Space         | W   | 0.885      | 0.435        | -                | 0.406 (0.156)    | 0 (0.000) |     2.85 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           29 |     1244 | 2024-06-06 | fnatic        | L   | 0.833      | -            | -                | -                | -         |    -6.36 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           28 |     1283 | 2024-06-06 | Eternal Fire  | L   | 0.831      | -            | -                | -                | -         |    -2.82 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           27 |     1307 | 2024-06-05 | BetBoom       | L   | 0.826      | -            | -                | -                | -         |    -9.33 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           26 |     1329 | 2024-06-05 | Complexity    | L   | 0.825      | -            | -                | -                | -         |    -2.81 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           25 |     1339 | 2024-06-05 | FURIA         | W   | 0.824      | 0.715        | 0.284 (0.167)    | 0.495 (0.292)    | 1 (0.824) |    21.81 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           24 |     1521 | 2024-05-29 | HEROIC        | L   | 0.781      | -            | -                | -                | -         |    -3.48 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           23 |     1532 | 2024-05-29 | Virtus.pro    | W   | 0.779      | 0.624        | 0.494 (0.240)    | 0.327 (0.159)    | 1 (0.779) |    22.37 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           22 |     1548 | 2024-05-28 | FlyQuest      | W   | 0.773      | 0.624        | 0.105 (0.051)    | 0.298 (0.144)    | 1 (0.773) |    11.58 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           21 |     1572 | 2024-05-27 | Natus Vincere | L   | 0.767      | -            | -                | -                | -         |    -0.43 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           20 |     1768 | 2024-05-20 | MIBR          | L   | 0.718      | -            | -                | -                | -         |    -5.44 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           19 |     1783 | 2024-05-19 | Astralis      | L   | 0.713      | -            | -                | -                | -         |    -1.45 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           18 |     2161 | 2024-05-07 | G2            | L   | 0.632      | -            | -                | -                | -         |    -0.40 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           17 |     2225 | 2024-05-03 | HEROIC        | W   | 0.606      | 0.889        | 0.234 (0.126)    | 0.382 (0.206)    | 1 (0.606) |    16.76 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           16 |     2235 | 2024-05-03 | PERA          | W   | 0.604      | 0.889        | 0.048 (0.026)    | 0.452 (0.243)    | 1 (0.604) |     2.92 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           15 |     2262 | 2024-05-02 | Natus Vincere | L   | 0.598      | -            | -                | -                | -         |    -0.26 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           14 |     2284 | 2024-05-01 | BOSS          | W   | 0.591      | 0.889        | 0.014 (0.007)    | 0.334 (0.176)    | 1 (0.591) |     1.76 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           13 |     2497 | 2024-04-21 | BLEED         | L   | 0.524      | -            | -                | -                | -         |   -12.37 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           12 |     2523 | 2024-04-20 | GamerLegion   | W   | 0.518      | 0.384        | 0.175 (0.035)    | -                | 0 (0.000) |     5.75 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           11 |     2633 | 2024-04-18 | LEON          | W   | 0.504      | -            | -                | -                | 0 (0.000) |     0.76 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           10 |     2742 | 2024-04-13 | OG            | L   | 0.471      | -            | -                | -                | -         |   -11.10 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            9 |     2751 | 2024-04-12 | FORZE         | W   | 0.465      | 0.684        | 0.060 (0.019)    | 0.188 (0.060)    | 0 (0.000) |     2.39 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            8 |     2822 | 2024-04-10 | Gods Reign    | W   | 0.452      | 0.684        | 0.042 (0.013)    | 0.206 (0.064)    | -         |     1.09 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            7 |     2884 | 2024-04-09 | BetBoom       | L   | 0.445      | -            | -                | -                | -         |    -3.81 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            6 |     3059 | 2024-04-03 | EYEBALLERS    | W   | 0.405      | 0.384        | -                | 0.513 (0.080)    | -         |     1.69 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            5 |     3541 | 2024-03-09 | Spirit        | L   | 0.240      | -            | -                | -                | -         |    -0.17 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            4 |     3572 | 2024-03-08 | GamerLegion   | W   | 0.232      | -            | -                | -                | -         |     0.58 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            3 |     3702 | 2024-03-03 | Young Ninjas  | L   | 0.200      | -            | -                | -                | -         |    -5.90 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            2 |     3762 | 2024-03-01 | AMKAL         | W   | 0.184      | 0.500        | 0.131 (0.012)    | -                | -         |     2.13 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            1 |     3789 | 2024-02-28 | BLEED         | L   | 0.170      | -            | -                | -                | -         |    -4.47 | JDC, Krimbo, prosus, syrsoN, tabseN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($52,179.23)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.899 | $2,000.00      | $1,797.56       |
| 2024-06-09 |      0.852 | $8,000.00      | $6,814.70       |
| 2024-06-02 |      0.806 | $6,000.00      | $4,836.03       |
| 2024-05-12 |      0.665 | $17,500.00     | $11,640.50      |
| 2024-04-14 |      0.478 | $35,000.00     | $16,742.80      |
| 2024-03-10 |      0.246 | $7,500.00      | $1,847.64       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
