### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, fostar, Kaide, mo0N, sowalio<br />
Global Rank: [86](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  923.2<br />
<br />
Final Rank Value (923.2) = Starting Rank Value (944.8) + Head To Head Adjustments (-21.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.496[<sup>1</sup>](#table2)
- Bounty Collected: 0.379[<sup>2</sup>](#table1)
- Opponent Network: 0.183[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.265<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 944.8
- 400 + ( ( 0.265 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 944.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           48 |      241 | 2024-07-25 | 9z              | L   | 1.000      | -            | -                | -                | -         |    -4.63 | dekz, fostar, Kaide, mo0N, sowalio |
|           47 |      321 | 2024-07-23 | Metizport       | W   | 1.000      | 0.435        | 0.038 (0.017)    | 0.425 (0.185)    | 0 (0.000) |    16.61 | dekz, fostar, Kaide, mo0N, sowalio |
|           46 |      388 | 2024-07-20 | DMS             | W   | 1.000      | 0.435        | -                | 0.447 (0.194)    | 0 (0.000) |    15.10 | dekz, fostar, Kaide, mo0N, sowalio |
|           45 |      419 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -8.81 | dekz, fostar, Kaide, mo0N, sowalio |
|           44 |      578 | 2024-07-17 | VP.Prodigy      | W   | 1.000      | 0.435        | 0.026 (0.011)    | 0.405 (0.176)    | 0 (0.000) |    14.72 | dekz, fostar, Kaide, mo0N, sowalio |
|           43 |      625 | 2024-07-16 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -15.53 | dekz, fostar, Kaide, mo0N, sowalio |
|           42 |      899 | 2024-06-16 | ARCRED          | W   | 0.893      | 0.450        | 0.039 (0.015)    | 0.327 (0.132)    | 0 (0.000) |    16.18 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           41 |      918 | 2024-06-15 | System5         | L   | 0.888      | -            | -                | -                | -         |   -21.57 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           40 |      930 | 2024-06-15 | Spirit Academy  | W   | 0.887      | 0.450        | 0.014 (0.005)    | -                | 0 (0.000) |     8.28 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           39 |      955 | 2024-06-14 | Zero Tenacity   | L   | 0.881      | -            | -                | -                | -         |    -9.35 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           38 |      961 | 2024-06-14 | LEON            | W   | 0.881      | -            | -                | -                | 0 (0.000) |     6.47 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           37 |     1105 | 2024-06-09 | Insilio         | L   | 0.848      | -            | -                | -                | -         |   -11.05 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           36 |     1261 | 2024-06-07 | SINNERS         | L   | 0.833      | -            | -                | -                | -         |   -10.54 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           35 |     1379 | 2024-06-05 | ARCRED          | L   | 0.821      | -            | -                | -                | -         |   -13.73 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           34 |     1395 | 2024-06-05 | Rare Atom       | L   | 0.819      | -            | -                | -                | -         |   -21.84 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           33 |     1444 | 2024-06-03 | Insilio         | W   | 0.808      | 0.372        | 0.023 (0.007)    | 0.554 (0.167)    | 0 (0.000) |    12.56 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           32 |     1453 | 2024-06-03 | HAVU            | L   | 0.807      | -            | -                | -                | -         |   -20.04 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           31 |     1488 | 2024-06-01 | Zero Tenacity   | W   | 0.795      | 0.372        | 0.139 (0.041)    | 1.000 (0.296)    | 0 (0.000) |    17.45 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           30 |     1551 | 2024-05-30 | Portugal        | W   | 0.782      | -            | -                | -                | 0 (0.000) |     4.65 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           29 |     1564 | 2024-05-30 | FURIA           | L   | 0.780      | -            | -                | -                | -         |    -0.63 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           28 |     1608 | 2024-05-28 | MOUZ NXT        | L   | 0.767      | -            | -                | -                | -         |    -8.41 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           27 |     1651 | 2024-05-26 | Zero Tenacity   | L   | 0.753      | -            | -                | -                | -         |    -7.75 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           26 |     1661 | 2024-05-25 | B8              | L   | 0.749      | -            | -                | -                | -         |    -5.88 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           25 |     1699 | 2024-05-23 | Nexus           | W   | 0.734      | 0.435        | 0.014 (0.004)    | 0.504 (0.161)    | 0 (0.000) |     6.49 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           24 |     1807 | 2024-05-21 | Endpoint        | W   | 0.719      | 0.435        | -                | 0.555 (0.174)    | -         |    10.72 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           23 |     2165 | 2024-05-11 | 9 Pandas        | L   | 0.654      | -            | -                | -                | -         |    -8.72 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           22 |     2191 | 2024-05-10 | Nemiga          | W   | 0.646      | 0.435        | 0.324 (0.091)    | 0.697 (0.196)    | -         |    15.45 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           21 |     2250 | 2024-05-07 | Insilio         | W   | 0.628      | 0.435        | 0.023 (0.006)    | 0.554 (0.151)    | -         |     9.77 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           20 |     2293 | 2024-05-05 | HAVU            | W   | 0.614      | -            | -                | -                | -         |     4.24 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           19 |     2323 | 2024-05-03 | V1dar           | W   | 0.600      | -            | -                | -                | -         |     1.86 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           18 |     2382 | 2024-05-01 | GL Academy      | L   | 0.586      | -            | -                | -                | -         |   -13.56 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           17 |     2425 | 2024-04-29 | Permitta        | L   | 0.573      | -            | -                | -                | -         |    -9.16 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           16 |     2456 | 2024-04-27 | Astralis Talent | W   | 0.561      | -            | -                | -                | -         |     0.76 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           15 |     2622 | 2024-04-20 | Zero Tenacity   | L   | 0.514      | -            | -                | -                | -         |    -5.77 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           14 |     2704 | 2024-04-18 | Sashi           | L   | 0.501      | -            | -                | -                | -         |    -4.51 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           13 |     2714 | 2024-04-18 | Aurora          | W   | 0.501      | 0.143        | 0.432 (0.031)    | -                | -         |    15.46 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           12 |     2721 | 2024-04-18 | NOM             | W   | 0.501      | -            | -                | -                | -         |     1.59 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           11 |     2775 | 2024-04-17 | JANO            | W   | 0.493      | -            | -                | -                | -         |     3.01 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           10 |     3430 | 2024-03-19 | Sashi           | L   | 0.302      | -            | -                | -                | -         |    -2.43 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            9 |     3487 | 2024-03-16 | Permitta        | W   | 0.281      | -            | -                | -                | -         |     4.64 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            8 |     3629 | 2024-03-11 | Nexus           | L   | 0.248      | -            | -                | -                | -         |    -5.02 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            7 |     3667 | 2024-03-09 | Spirit Academy  | W   | 0.235      | -            | -                | -                | -         |     0.77 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            6 |     3693 | 2024-03-08 | ARCRED          | W   | 0.228      | -            | -                | -                | -         |     2.78 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            5 |     3930 | 2024-02-27 | Spirit Academy  | L   | 0.162      | -            | -                | -                | -         |    -4.60 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            4 |     3934 | 2024-02-27 | ALTERNATE aTTaX | W   | 0.161      | -            | -                | -                | -         |     2.90 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            3 |     4357 | 2024-02-09 | FORZE           | L   | 0.041      | -            | -                | -                | -         |    -0.73 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            2 |     4368 | 2024-02-08 | AMKAL           | L   | 0.035      | -            | -                | -                | -         |    -0.26 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            1 |     4371 | 2024-02-08 | ex-Guild Eagles | W   | 0.034      | -            | -                | -                | -         |     0.36 | dekz, Kaide, mo0N, sowalio, w1nt3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,626.82)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.893 | $30,000.00     | $26,800.00      |
| 2024-06-10 |      0.855 | $3,300.00      | $2,821.96       |
| 2024-05-12 |      0.661 | $2,000.00      | $1,322.64       |
| 2024-03-25 |      0.341 | $2,000.00      | $682.22         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
