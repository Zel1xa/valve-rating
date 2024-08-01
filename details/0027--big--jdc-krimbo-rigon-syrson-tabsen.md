### Roster Details<br />
Team Name: BIG<br />
Roster: JDC, Krimbo, rigoN, syrsoN, tabseN<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1234.6<br />
<br />
Final Rank Value (1234.6) = Starting Rank Value (1237.3) + Head To Head Adjustments (-2.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.532[<sup>1</sup>](#table2)
- Bounty Collected: 0.461[<sup>2</sup>](#table1)
- Opponent Network: 0.157[<sup>2</sup>](#table1)
- LAN Wins: 0.478[<sup>2</sup>](#table1)

The average of these factors is 0.407<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1237.3
- 400 + ( ( 0.407 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1237.3


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
|           32 |       45 | 2024-07-31 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.52 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           31 |      942 | 2024-06-15 | Permitta      | L   | 0.884      | -            | -                | -                | -         |   -23.67 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           30 |      964 | 2024-06-14 | Space         | W   | 0.879      | 0.435        | -                | 0.406 (0.155)    | 0 (0.000) |     3.09 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           29 |     1296 | 2024-06-06 | fnatic        | L   | 0.827      | -            | -                | -                | -         |   -10.26 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           28 |     1336 | 2024-06-06 | Eternal Fire  | L   | 0.825      | -            | -                | -                | -         |    -2.78 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           27 |     1361 | 2024-06-05 | BetBoom       | L   | 0.820      | -            | -                | -                | -         |    -9.30 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           26 |     1384 | 2024-06-05 | Complexity    | L   | 0.819      | -            | -                | -                | -         |    -2.78 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           25 |     1394 | 2024-06-05 | FURIA         | W   | 0.818      | 0.715        | 0.286 (0.168)    | 0.494 (0.289)    | 1 (0.818) |    21.75 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           24 |     1577 | 2024-05-29 | HEROIC        | L   | 0.775      | -            | -                | -                | -         |    -3.59 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           23 |     1588 | 2024-05-29 | Virtus.pro    | W   | 0.773      | 0.624        | 0.484 (0.233)    | 0.326 (0.157)    | 1 (0.773) |    22.12 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           22 |     1604 | 2024-05-28 | FlyQuest      | W   | 0.767      | 0.624        | 0.106 (0.051)    | 0.323 (0.155)    | 1 (0.767) |    11.78 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           21 |     1628 | 2024-05-27 | Natus Vincere | L   | 0.761      | -            | -                | -                | -         |    -0.40 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           20 |     1847 | 2024-05-20 | MIBR          | L   | 0.712      | -            | -                | -                | -         |    -5.49 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           19 |     1866 | 2024-05-19 | Astralis      | L   | 0.707      | -            | -                | -                | -         |    -1.44 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           18 |     2256 | 2024-05-07 | G2            | L   | 0.626      | -            | -                | -                | -         |    -0.37 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           17 |     2320 | 2024-05-03 | HEROIC        | W   | 0.600      | 0.889        | 0.208 (0.111)    | 0.380 (0.203)    | 1 (0.600) |    16.50 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           16 |     2330 | 2024-05-03 | PERA          | W   | 0.598      | 0.889        | 0.048 (0.026)    | 0.452 (0.241)    | 1 (0.598) |     3.03 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           15 |     2358 | 2024-05-02 | Natus Vincere | L   | 0.592      | -            | -                | -                | -         |    -0.25 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           14 |     2381 | 2024-05-01 | BOSS          | W   | 0.585      | 0.889        | 0.014 (0.007)    | 0.334 (0.174)    | 1 (0.585) |     1.92 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           13 |     2599 | 2024-04-21 | BLEED         | L   | 0.518      | -            | -                | -                | -         |   -12.10 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           12 |     2627 | 2024-04-20 | GamerLegion   | W   | 0.512      | 0.384        | 0.176 (0.035)    | -                | 0 (0.000) |     5.85 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           11 |     2739 | 2024-04-18 | LEON          | W   | 0.498      | -            | -                | -                | 0 (0.000) |     0.81 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           10 |     2850 | 2024-04-13 | OG            | L   | 0.465      | -            | -                | -                | -         |   -10.97 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            9 |     2859 | 2024-04-12 | FORZE         | W   | 0.460      | 0.684        | 0.060 (0.019)    | 0.186 (0.058)    | 0 (0.000) |     2.49 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            8 |     2931 | 2024-04-10 | Gods Reign    | W   | 0.447      | 0.684        | 0.042 (0.013)    | 0.205 (0.063)    | -         |     1.16 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            7 |     2993 | 2024-04-09 | BetBoom       | L   | 0.439      | -            | -                | -                | -         |    -3.68 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            6 |     3174 | 2024-04-03 | EYEBALLERS    | W   | 0.399      | 0.384        | -                | 0.512 (0.079)    | -         |     1.78 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            5 |     3669 | 2024-03-09 | Spirit        | L   | 0.234      | -            | -                | -                | -         |    -0.16 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            4 |     3700 | 2024-03-08 | GamerLegion   | W   | 0.226      | -            | -                | -                | -         |     0.59 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            3 |     3835 | 2024-03-03 | Young Ninjas  | L   | 0.194      | -            | -                | -                | -         |    -5.70 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            2 |     3896 | 2024-03-01 | AMKAL         | W   | 0.178      | 0.500        | 0.132 (0.012)    | -                | -         |     2.15 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            1 |     3924 | 2024-02-28 | BLEED         | L   | 0.165      | -            | -                | -                | -         |    -4.26 | JDC, Krimbo, prosus, syrsoN, tabseN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43,243.99)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.893 | $2,000.00      | $1,786.11       |
| 2024-06-09 |      0.846 | $8,000.00      | $6,768.89       |
| 2024-06-02 |      0.800 | $6,000.00      | $4,801.67       |
| 2024-05-12 |      0.659 | $17,500.00     | $11,540.28      |
| 2024-04-14 |      0.473 | $35,000.00     | $16,542.36      |
| 2024-03-10 |      0.241 | $7,500.00      | $1,804.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
