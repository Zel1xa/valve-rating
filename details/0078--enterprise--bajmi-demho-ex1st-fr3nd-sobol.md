### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
<br />
Final Rank Value:  945.2<br />
<br />
Final Rank Value (945.2) = Starting Rank Value (918.3) + Head To Head Adjustments (26.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.360[<sup>2</sup>](#table1)
- Opponent Network: 0.230[<sup>2</sup>](#table1)
- LAN Wins: 0.005[<sup>2</sup>](#table1)

The average of these factors is 0.253<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 918.3
- 400 + ( ( 0.253 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 918.3


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
|           61 |      255 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    17.92 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      480 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.89 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      495 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.41 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      502 | 2024-07-22 | Illuminar         | W   | 1.000      | 0.371        | -                | 0.347 (0.129)    | 0 (0.000) |    15.82 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      525 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.77 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      594 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    17.61 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      722 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.11 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      821 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.20 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      859 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.02 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      940 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.04 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |     1036 | 2024-06-16 | 3DMAX             | L   | 0.863      | -            | -                | -                | -         |    -1.48 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1124 | 2024-06-13 | PERA              | L   | 0.845      | -            | -                | -                | -         |   -12.14 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1141 | 2024-06-13 | Illuminar         | W   | 0.843      | 0.450        | -                | 0.347 (0.132)    | 0 (0.000) |    11.47 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1164 | 2024-06-12 | Sampi             | W   | 0.837      | 0.379        | 0.027 (0.009)    | 1.000 (0.317)    | 0 (0.000) |    11.01 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1205 | 2024-06-10 | SINNERS           | W   | 0.824      | 0.379        | 0.037 (0.012)    | 0.808 (0.252)    | 0 (0.000) |    16.55 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1221 | 2024-06-10 | Gaimin Gladiators | W   | 0.823      | 0.450        | 0.037 (0.014)    | -                | -         |    15.31 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1260 | 2024-06-09 | ECLOT             | L   | 0.817      | -            | -                | -                | -         |    -5.03 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1303 | 2024-06-08 | Nexus             | W   | 0.811      | 0.450        | -                | 0.457 (0.167)    | -         |     7.96 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1387 | 2024-06-07 | Entropiq          | W   | 0.803      | -            | -                | -                | -         |     1.44 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1441 | 2024-06-06 | Illuminar         | L   | 0.797      | -            | -                | -                | -         |   -15.65 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1486 | 2024-06-05 | Verdant           | L   | 0.792      | -            | -                | -                | -         |   -13.37 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1503 | 2024-06-05 | Serbia            | L   | 0.790      | -            | -                | -                | -         |   -16.73 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1560 | 2024-06-04 | Johnny Speeds     | W   | 0.782      | 0.371        | 0.122 (0.035)    | 1.000 (0.290)    | -         |    21.09 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1582 | 2024-06-03 | UNiTY             | W   | 0.775      | -            | -                | -                | -         |    13.85 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1624 | 2024-06-01 | ARCRED            | L   | 0.764      | -            | -                | -                | -         |   -11.70 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1639 | 2024-06-01 | Permitta          | W   | 0.762      | 0.371        | -                | 0.901 (0.254)    | -         |    11.94 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1677 | 2024-05-30 | RUSTEC            | W   | 0.752      | -            | -                | -                | -         |     1.29 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1693 | 2024-05-30 | brazylijski luz   | L   | 0.749      | -            | -                | -                | -         |   -14.34 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1706 | 2024-05-29 | FLuffy Gangsters  | W   | 0.745      | -            | -                | -                | -         |     2.83 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1732 | 2024-05-28 | Sampi             | W   | 0.737      | 0.379        | -                | 1.000 (0.279)    | -         |    11.64 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1813 | 2024-05-24 | Illuminar         | W   | 0.709      | -            | -                | -                | -         |     9.87 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1863 | 2024-05-22 | Entropiq          | W   | 0.697      | -            | -                | -                | -         |     1.27 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1949 | 2024-05-20 | ECSTATIC          | W   | 0.683      | -            | -                | -                | -         |     2.73 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2277 | 2024-05-10 | BetBoom           | L   | 0.616      | -            | -                | -                | -         |    -1.20 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2344 | 2024-05-07 | Permitta          | W   | 0.596      | 0.435        | -                | 0.901 (0.233)    | -         |    10.45 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2358 | 2024-05-06 | B8                | L   | 0.590      | -            | -                | -                | -         |    -5.42 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2386 | 2024-05-04 | MOUZ NXT          | W   | 0.578      | 0.435        | 0.139 (0.035)    | 0.986 (0.248)    | -         |    12.79 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2447 | 2024-05-01 | ENCE Academy      | W   | 0.558      | -            | -                | -                | -         |     5.31 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2475 | 2024-04-30 | EYEBALLERS        | L   | 0.551      | -            | -                | -                | -         |    -8.47 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2511 | 2024-04-29 | Nexus             | L   | 0.542      | -            | -                | -                | -         |    -9.89 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2553 | 2024-04-27 | Permitta          | L   | 0.529      | -            | -                | -                | -         |    -6.87 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2571 | 2024-04-26 | Insilio           | L   | 0.523      | -            | -                | -                | -         |    -7.79 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2645 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.502      | -            | -                | -                | -         |    -7.29 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2710 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.482      | -            | -                | -                | -         |    -6.70 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2795 | 2024-04-18 | MOUZ NXT          | L   | 0.471      | -            | -                | -                | -         |    -4.86 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2807 | 2024-04-18 | Nexus             | W   | 0.469      | -            | -                | -                | -         |     6.14 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2833 | 2024-04-17 | ENCE              | L   | 0.463      | -            | -                | -                | -         |    -0.77 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2965 | 2024-04-11 | Sashi             | L   | 0.422      | -            | -                | -                | -         |    -3.19 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     3009 | 2024-04-10 | AMKAL             | W   | 0.416      | 0.384        | 0.130 (0.021)    | -                | -         |    10.06 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3139 | 2024-04-06 | Sampi             | L   | 0.389      | -            | -                | -                | -         |    -6.23 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3228 | 2024-04-03 | Permitta          | W   | 0.371      | -            | -                | -                | -         |     6.69 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3288 | 2024-04-01 | BLEED             | W   | 0.357      | 0.384        | 0.090 (0.012)    | -                | -         |     6.68 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3727 | 2024-03-09 | kONO              | L   | 0.204      | -            | -                | -                | -         |    -4.14 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3739 | 2024-03-09 | Sampi             | L   | 0.203      | -            | -                | -                | -         |    -3.47 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3807 | 2024-03-06 | INGLORIOUS        | L   | 0.184      | -            | -                | -                | -         |    -5.20 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3813 | 2024-03-06 | Permitta          | L   | 0.183      | -            | -                | -                | -         |    -2.54 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3924 | 2024-03-02 | Sampi             | W   | 0.156      | -            | -                | -                | -         |     2.21 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4235 | 2024-02-16 | SAW               | L   | 0.058      | -            | -                | -                | -         |    -0.38 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4272 | 2024-02-15 | BetBoom           | L   | 0.050      | -            | -                | -                | -         |    -0.09 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4299 | 2024-02-14 | Natus Vincere     | L   | 0.045      | -            | -                | -                | -         |    -0.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4311 | 2024-02-14 | AMKAL             | W   | 0.043      | -            | -                | -                | 1 (0.043) |     1.07 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,617.35)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.869 | $5,000.00      | $4,347.22       |
| 2024-06-13 |      0.845 | $5,447.00      | $4,602.21       |
| 2024-06-06 |      0.795 | $3,000.00      | $2,385.83       |
| 2024-05-02 |      0.564 | $500.00        | $282.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
