### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [77](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
<br />
Final Rank Value:  945.7<br />
<br />
Final Rank Value (945.7) = Starting Rank Value (919.1) + Head To Head Adjustments (26.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.360[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.005[<sup>2</sup>](#table1)

The average of these factors is 0.253<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 919.1
- 400 + ( ( 0.253 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 919.1


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
|           61 |      259 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    17.90 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      484 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.89 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      499 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.40 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      506 | 2024-07-22 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.81 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      529 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.76 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      598 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.024 (0.009)    | -                | 0 (0.000) |    17.59 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      726 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.12 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      825 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.19 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      863 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.01 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      944 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.02 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |     1040 | 2024-06-16 | 3DMAX             | L   | 0.860      | -            | -                | -                | -         |    -1.47 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1128 | 2024-06-13 | PERA              | L   | 0.842      | -            | -                | -                | -         |   -12.12 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1145 | 2024-06-13 | Illuminar         | W   | 0.841      | 0.450        | -                | 0.347 (0.131)    | 0 (0.000) |    11.43 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1168 | 2024-06-12 | Sampi             | W   | 0.835      | 0.379        | 0.027 (0.009)    | 1.000 (0.316)    | 0 (0.000) |    10.97 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1209 | 2024-06-10 | SINNERS           | W   | 0.821      | 0.379        | 0.037 (0.012)    | 0.808 (0.251)    | 0 (0.000) |    16.50 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1225 | 2024-06-10 | Gaimin Gladiators | W   | 0.820      | 0.450        | 0.037 (0.014)    | -                | -         |    15.23 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1264 | 2024-06-09 | ECLOT             | L   | 0.814      | -            | -                | -                | -         |    -5.03 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1307 | 2024-06-08 | Nexus             | W   | 0.809      | 0.450        | -                | 0.457 (0.166)    | -         |     7.99 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1391 | 2024-06-07 | Entropiq          | W   | 0.801      | -            | -                | -                | -         |     1.43 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1445 | 2024-06-06 | Illuminar         | L   | 0.795      | -            | -                | -                | -         |   -15.61 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1490 | 2024-06-05 | Verdant           | L   | 0.789      | -            | -                | -                | -         |   -13.33 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1507 | 2024-06-05 | Serbia            | L   | 0.788      | -            | -                | -                | -         |   -16.69 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1564 | 2024-06-04 | Johnny Speeds     | W   | 0.779      | 0.371        | 0.122 (0.035)    | 1.000 (0.289)    | -         |    21.03 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1586 | 2024-06-03 | UNiTY             | W   | 0.773      | -            | -                | -                | -         |    13.78 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1628 | 2024-06-01 | ARCRED            | L   | 0.762      | -            | -                | -                | -         |   -11.67 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1643 | 2024-06-01 | Permitta          | W   | 0.759      | 0.371        | -                | 0.940 (0.264)    | -         |    11.90 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1681 | 2024-05-30 | RUSTEC            | W   | 0.749      | -            | -                | -                | -         |     1.28 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1697 | 2024-05-30 | brazylijski luz   | L   | 0.746      | -            | -                | -                | -         |   -14.33 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1710 | 2024-05-29 | FLuffy Gangsters  | W   | 0.742      | -            | -                | -                | -         |     2.82 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1736 | 2024-05-28 | Sampi             | W   | 0.735      | 0.379        | -                | 1.000 (0.278)    | -         |    11.59 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1817 | 2024-05-24 | Illuminar         | W   | 0.707      | -            | -                | -                | -         |     9.81 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1867 | 2024-05-22 | Entropiq          | W   | 0.695      | -            | -                | -                | -         |     1.26 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1953 | 2024-05-20 | ECSTATIC          | W   | 0.680      | -            | -                | -                | -         |     2.71 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2281 | 2024-05-10 | BetBoom           | L   | 0.614      | -            | -                | -                | -         |    -1.21 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2348 | 2024-05-07 | Permitta          | W   | 0.593      | 0.435        | -                | 0.940 (0.242)    | -         |    10.40 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2362 | 2024-05-06 | B8                | L   | 0.588      | -            | -                | -                | -         |    -5.41 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2390 | 2024-05-04 | MOUZ NXT          | W   | 0.576      | 0.435        | 0.139 (0.035)    | 0.984 (0.246)    | -         |    12.72 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2451 | 2024-05-01 | ENCE Academy      | W   | 0.556      | -            | -                | -                | -         |     5.27 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2479 | 2024-04-30 | EYEBALLERS        | L   | 0.548      | -            | -                | -                | -         |    -8.42 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2515 | 2024-04-29 | Nexus             | L   | 0.539      | -            | -                | -                | -         |    -9.80 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2557 | 2024-04-27 | Permitta          | L   | 0.526      | -            | -                | -                | -         |    -6.85 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2575 | 2024-04-26 | Insilio           | L   | 0.521      | -            | -                | -                | -         |    -7.75 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2649 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.500      | -            | -                | -                | -         |    -7.26 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2714 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.480      | -            | -                | -                | -         |    -6.67 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2799 | 2024-04-18 | MOUZ NXT          | L   | 0.468      | -            | -                | -                | -         |    -4.84 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2811 | 2024-04-18 | Nexus             | W   | 0.467      | -            | -                | -                | -         |     6.14 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2837 | 2024-04-17 | ENCE              | L   | 0.461      | -            | -                | -                | -         |    -0.77 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2969 | 2024-04-11 | Sashi             | L   | 0.420      | -            | -                | -                | -         |    -3.18 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     3013 | 2024-04-10 | AMKAL             | W   | 0.413      | 0.384        | 0.130 (0.021)    | -                | -         |    10.01 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3143 | 2024-04-06 | Sampi             | L   | 0.387      | -            | -                | -                | -         |    -6.20 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3232 | 2024-04-03 | Permitta          | W   | 0.368      | 0.384        | -                | 0.940 (0.133)    | -         |     6.63 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3292 | 2024-04-01 | BLEED             | W   | 0.354      | 0.384        | 0.090 (0.012)    | -                | -         |     6.62 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3731 | 2024-03-09 | kONO              | L   | 0.201      | -            | -                | -                | -         |    -4.07 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3743 | 2024-03-09 | Sampi             | L   | 0.200      | -            | -                | -                | -         |    -3.42 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3811 | 2024-03-06 | INGLORIOUS        | L   | 0.182      | -            | -                | -                | -         |    -5.14 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3817 | 2024-03-06 | Permitta          | L   | 0.180      | -            | -                | -                | -         |    -2.52 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3928 | 2024-03-02 | Sampi             | W   | 0.153      | -            | -                | -                | -         |     2.18 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4239 | 2024-02-16 | SAW               | L   | 0.055      | -            | -                | -                | -         |    -0.36 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4276 | 2024-02-15 | BetBoom           | L   | 0.047      | -            | -                | -                | -         |    -0.09 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4303 | 2024-02-14 | Natus Vincere     | L   | 0.043      | -            | -                | -                | -         |    -0.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4315 | 2024-02-14 | AMKAL             | W   | 0.041      | -            | -                | -                | 1 (0.041) |     1.01 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,582.48)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.867 | $5,000.00      | $4,334.72       |
| 2024-06-13 |      0.842 | $5,447.00      | $4,588.59       |
| 2024-06-06 |      0.793 | $3,000.00      | $2,378.33       |
| 2024-05-02 |      0.562 | $500.00        | $280.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
