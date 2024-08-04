### Roster Details<br />
Team Name: Nexus<br />
Roster: 7kick, BTN, Ciocardau, ragga, XELLOW<br />
Global Rank: [129](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [90]( ../standings_europe.md)<br />
<br />
Final Rank Value:  784.8<br />
<br />
Final Rank Value (784.8) = Starting Rank Value (836.4) + Head To Head Adjustments (-51.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.349[<sup>1</sup>](#table2)
- Bounty Collected: 0.356[<sup>2</sup>](#table1)
- Opponent Network: 0.149[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.213<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 836.4
- 400 + ( ( 0.213 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 836.4


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
|           61 |      178 | 2024-07-31 | EYEBALLERS        | W   | 1.000      | 0.143        | -                | 0.509 (0.073)    | 0 (0.000) |    15.74 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           60 |      240 | 2024-07-29 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -4.67 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           59 |      373 | 2024-07-25 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -13.92 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           58 |      517 | 2024-07-20 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.98 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           57 |      560 | 2024-07-19 | PERA              | W   | 1.000      | 0.333        | 0.048 (0.016)    | 0.453 (0.151)    | 0 (0.000) |    23.94 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           56 |      603 | 2024-07-18 | TSM               | W   | 1.000      | 0.333        | 0.040 (0.013)    | 0.394 (0.131)    | 0 (0.000) |    26.06 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           55 |      619 | 2024-07-18 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -6.23 | 7kick, BTN, Ciocardau, Ed1m, ragga   |
|           54 |      697 | 2024-07-17 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -10.99 | 7kick, BTN, Ed1m, ragga, XELLOW      |
|           53 |      723 | 2024-07-16 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -0.28 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           52 |      788 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.333        | 0.037 (0.012)    | 0.797 (0.266)    | 0 (0.000) |    25.54 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           51 |      796 | 2024-07-14 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.56 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           50 |      815 | 2024-07-13 | Serbia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.08 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           49 |      858 | 2024-07-10 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.30 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           48 |      889 | 2024-07-09 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.18 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           47 |     1130 | 2024-06-12 | Permitta          | L   | 0.847      | -            | -                | -                | -         |    -6.66 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           46 |     1153 | 2024-06-11 | FAVBET            | L   | 0.840      | -            | -                | -                | -         |   -10.70 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           45 |     1249 | 2024-06-09 | EYEBALLERS        | L   | 0.825      | -            | -                | -                | -         |    -7.54 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           44 |     1274 | 2024-06-08 | Enterprise        | L   | 0.821      | -            | -                | -                | -         |    -8.10 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           43 |     1349 | 2024-06-07 | Astralis Talent   | W   | 0.813      | -            | -                | -                | 0 (0.000) |    13.13 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           42 |     1361 | 2024-06-07 | 9INE              | L   | 0.812      | -            | -                | -                | -         |    -8.15 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           41 |     1387 | 2024-06-06 | 3DMAX             | L   | 0.808      | -            | -                | -                | -         |    -0.42 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           40 |     1483 | 2024-06-05 | BLEED             | L   | 0.799      | -            | -                | -                | -         |    -0.75 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           39 |     1723 | 2024-05-27 | The Prodigies     | L   | 0.741      | -            | -                | -                | -         |   -18.30 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           38 |     1731 | 2024-05-27 | MOUZ NXT          | L   | 0.738      | -            | -                | -                | -         |    -4.01 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           37 |     1766 | 2024-05-25 | Permitta          | L   | 0.726      | -            | -                | -                | -         |    -8.04 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           36 |     1793 | 2024-05-23 | RUBY              | L   | 0.713      | -            | -                | -                | -         |    -6.62 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           35 |     1908 | 2024-05-20 | ALTERNATE aTTaX   | W   | 0.694      | 0.435        | 0.031 (0.009)    | 0.560 (0.169)    | 0 (0.000) |    14.87 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           34 |     1913 | 2024-05-20 | PERA              | L   | 0.693      | -            | -                | -                | -         |    -6.57 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           33 |     2010 | 2024-05-17 | Passion UA        | L   | 0.672      | -            | -                | -                | -         |    -4.45 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           32 |     2107 | 2024-05-15 | Space             | L   | 0.658      | -            | -                | -                | -         |    -9.19 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           31 |     2176 | 2024-05-13 | Sampi             | L   | 0.645      | -            | -                | -                | -         |    -6.98 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           30 |     2386 | 2024-05-03 | ENCE Academy      | L   | 0.578      | -            | -                | -                | -         |   -11.45 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     2431 | 2024-05-01 | Insilio           | L   | 0.566      | -            | -                | -                | -         |    -6.54 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     2463 | 2024-04-30 | fnatic            | L   | 0.558      | -            | -                | -                | -         |    -0.36 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     2467 | 2024-04-29 | Endpoint          | L   | 0.554      | -            | -                | -                | -         |    -7.22 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     2472 | 2024-04-29 | VP.Prodigy        | L   | 0.553      | -            | -                | -                | -         |    -8.12 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     2477 | 2024-04-29 | LEON              | W   | 0.552      | -            | -                | -                | 0 (0.000) |     5.28 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     2482 | 2024-04-29 | Enterprise        | W   | 0.551      | 0.384        | 0.039 (0.008)    | 0.625 (0.132)    | 0 (0.000) |    10.05 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     2498 | 2024-04-28 | brazylijski luz   | L   | 0.545      | -            | -                | -                | -         |    -8.70 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     2566 | 2024-04-25 | Metizport         | W   | 0.527      | 0.384        | 0.033 (0.007)    | -                | -         |     9.68 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     2574 | 2024-04-25 | Grannys Knockers  | L   | 0.526      | -            | -                | -                | -         |   -10.24 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     2595 | 2024-04-24 | AMKAL             | L   | 0.519      | -            | -                | -                | -         |    -2.63 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     2613 | 2024-04-23 | Illuminar         | L   | 0.512      | -            | -                | -                | -         |   -13.62 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     2626 | 2024-04-22 | Zero Tenacity     | L   | 0.506      | -            | -                | -                | -         |    -3.70 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     2637 | 2024-04-21 | Young Ninjas      | W   | 0.501      | -            | -                | -                | -         |     5.96 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     2641 | 2024-04-21 | PARIVISION        | L   | 0.500      | -            | -                | -                | -         |    -3.98 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     2677 | 2024-04-20 | Permitta          | W   | 0.492      | 0.500        | -                | 0.876 (0.216)    | -         |    10.17 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           14 |     2747 | 2024-04-18 | Young Ninjas      | L   | 0.481      | -            | -                | -                | -         |    -9.46 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     2778 | 2024-04-18 | Enterprise        | L   | 0.479      | -            | -                | -                | -         |    -6.27 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           12 |     2976 | 2024-04-10 | B8                | W   | 0.426      | 0.384        | 0.165 (0.027)    | 0.912 (0.149)    | -         |    10.16 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           11 |     3120 | 2024-04-05 | SINNERS           | L   | 0.393      | -            | -                | -                | -         |    -2.02 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           10 |     3262 | 2024-04-01 | Sashi             | W   | 0.365      | 0.384        | 0.184 (0.026)    | 0.962 (0.135)    | -         |     9.59 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            9 |     3371 | 2024-03-25 | Sashi             | L   | 0.320      | -            | -                | -                | -         |    -1.62 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            8 |     3632 | 2024-03-12 | Nemiga            | W   | 0.234      | 0.372        | 0.317 (0.028)    | 0.734 (0.064)    | -         |     6.40 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            7 |     3654 | 2024-03-11 | RUBY              | W   | 0.227      | 0.372        | 0.095 (0.008)    | -                | -         |     4.48 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            6 |     3694 | 2024-03-09 | INGLORIOUS        | W   | 0.214      | -            | -                | -                | -         |     1.11 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            5 |     3718 | 2024-03-08 | FAVBET            | W   | 0.207      | -            | -                | -                | -         |     2.60 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            4 |     3864 | 2024-03-03 | TSM               | L   | 0.174      | -            | -                | -                | -         |    -3.91 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            3 |     4112 | 2024-02-20 | ex-Guild Eagles   | L   | 0.093      | -            | -                | -                | -         |    -1.56 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            2 |     4133 | 2024-02-19 | Monte             | L   | 0.087      | -            | -                | -                | -         |    -0.81 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            1 |     4139 | 2024-02-19 | Astralis          | L   | 0.086      | -            | -                | -                | -         |    -0.02 | BTN, ERSIN, ragga, s0und, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,450.31)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-05-02 |      0.574 | $1,000.00      | $573.52         |
| 2024-03-25 |      0.320 | $4,300.00      | $1,376.80       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
