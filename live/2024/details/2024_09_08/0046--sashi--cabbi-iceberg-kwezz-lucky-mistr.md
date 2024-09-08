### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [46](../../standings_global_2024_09_08.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_08.md)<br />
Regional Rank: [33]( ../../standings_europe_2024_09_08.md)<br />
<br />
Final Rank Value:  1044.6<br />
<br />
Final Rank Value (1044.6) = Starting Rank Value (1065.1) + Head To Head Adjustments (-20.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.549[<sup>1</sup>](#table2)
- Bounty Collected: 0.443[<sup>2</sup>](#table1)
- Opponent Network: 0.234[<sup>2</sup>](#table1)
- LAN Wins: 0.147[<sup>2</sup>](#table1)

The average of these factors is 0.343<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1065.1
- 400 + ( ( 0.343 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1065.1


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
|           89 |      160 | 2024-09-03 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |   -11.16 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           88 |      233 | 2024-08-30 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -8.77 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           87 |      259 | 2024-08-29 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -19.09 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           86 |      273 | 2024-08-29 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.18 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           85 |      448 | 2024-08-26 | Sampi             | L   | 1.000      | -            | -                | -                | -         |   -22.37 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           84 |      551 | 2024-08-23 | OG                | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.50 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           83 |      564 | 2024-08-23 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.22 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           82 |      596 | 2024-08-22 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.96 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           81 |      616 | 2024-08-21 | AMKAL             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.15 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           80 |      647 | 2024-08-21 | Qiang             | L   | 1.000      | -            | -                | -                | -         |   -22.25 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           79 |      710 | 2024-08-19 | B8                | L   | 1.000      | -            | -                | -                | -         |   -15.06 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           78 |      716 | 2024-08-19 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.87 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           77 |      727 | 2024-08-19 | Aurora            | W   | 1.000      | 0.500        | 0.290 (0.145)    | 0.603 (0.301)    | 0 (0.000) |    23.25 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           76 |      929 | 2024-08-12 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -2.94 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           75 |      978 | 2024-08-10 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -20.59 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           74 |     1013 | 2024-08-09 | Qiang             | W   | 0.999      | 0.426        | -                | 0.389 (0.165)    | 0 (0.000) |     8.57 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           73 |     1064 | 2024-08-07 | 1WIN              | W   | 0.988      | 0.426        | -                | 0.569 (0.239)    | 0 (0.000) |    10.96 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           72 |     1111 | 2024-08-06 | KOI               | W   | 0.981      | 0.500        | 0.053 (0.026)    | -                | -         |    11.30 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           71 |     1142 | 2024-08-05 | ECSTATIC          | L   | 0.974      | -            | -                | -                | -         |   -26.91 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           70 |     1146 | 2024-08-05 | TSM               | L   | 0.973      | -            | -                | -                | -         |   -19.80 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           69 |     1152 | 2024-08-05 | ECSTATIC          | W   | 0.973      | -            | -                | -                | -         |     2.88 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           68 |     1332 | 2024-07-31 | Insilio           | W   | 0.940      | 0.500        | -                | 0.654 (0.307)    | -         |     7.55 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           67 |     1363 | 2024-07-30 | EYEBALLERS        | W   | 0.935      | 0.500        | -                | 0.407 (0.190)    | -         |     2.47 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           66 |     1376 | 2024-07-30 | Zero Tenacity     | L   | 0.933      | -            | -                | -                | -         |   -14.70 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           65 |     1556 | 2024-07-24 | Monte             | W   | 0.895      | 0.500        | -                | 0.697 (0.312)    | -         |     7.61 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           64 |     1777 | 2024-07-18 | FURIA             | L   | 0.854      | -            | -                | -                | -         |    -1.94 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           63 |     1787 | 2024-07-18 | Qiang             | W   | 0.853      | 1.000        | 0.029 (0.025)    | -                | 1 (0.853) |     1.52 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           62 |     1857 | 2024-07-17 | MOUZ              | L   | 0.846      | -            | -                | -                | -         |    -0.37 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           61 |     1987 | 2024-07-13 | TSM               | L   | 0.820      | -            | -                | -                | -         |   -15.66 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           60 |     1996 | 2024-07-12 | FLuffy Gangsters  | W   | 0.813      | -            | -                | -                | -         |     1.70 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           59 |     2013 | 2024-07-11 | Endpoint          | W   | 0.807      | 0.358        | 0.065 (0.019)    | 0.723 (0.209)    | -         |     7.21 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           58 |     2037 | 2024-07-10 | Johnny Speeds     | L   | 0.800      | -            | -                | -                | -         |   -11.83 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           57 |     2040 | 2024-07-10 | 9INE              | W   | 0.799      | 0.358        | -                | 0.707 (0.202)    | -         |     6.06 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           56 |     2244 | 2024-06-14 | 3DMAX             | L   | 0.627      | -            | -                | -                | -         |    -1.64 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           55 |     2279 | 2024-06-13 | Sampi             | W   | 0.620      | -            | -                | -                | -         |     3.86 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           54 |     2296 | 2024-06-12 | CPH Wolves        | W   | 0.615      | -            | -                | -                | -         |     2.66 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           53 |     2305 | 2024-06-12 | Astralis Talent   | W   | 0.614      | -            | -                | -                | -         |     1.56 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           52 |     2561 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.575      | -            | -                | -                | -         |    -2.91 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           51 |     2597 | 2024-06-06 | HEROIC            | L   | 0.573      | -            | -                | -                | -         |    -2.99 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           50 |     2626 | 2024-06-05 | ENCE              | L   | 0.568      | -            | -                | -                | -         |    -7.33 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           49 |     2646 | 2024-06-05 | Astralis          | W   | 0.567      | 0.715        | 0.343 (0.139)    | -                | 1 (0.567) |    16.41 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           48 |     2656 | 2024-06-05 | The MongolZ       | L   | 0.566      | -            | -                | -                | -         |    -0.24 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           47 |     3091 | 2024-05-20 | Monte             | L   | 0.459      | -            | -                | -                | -         |    -9.87 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           46 |     3104 | 2024-05-19 | Passion UA        | W   | 0.454      | 0.500        | 0.164 (0.037)    | 1.000 (0.227)    | -         |     5.21 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           45 |     3131 | 2024-05-18 | B8                | L   | 0.448      | -            | -                | -                | -         |    -7.54 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           44 |     3140 | 2024-05-18 | Monte             | W   | 0.447      | -            | -                | -                | -         |     4.46 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           43 |     3148 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.446      | 0.500        | 0.102 (0.023)    | 0.837 (0.186)    | -         |     4.81 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           42 |     3179 | 2024-05-17 | ex-Guild Eagles   | W   | 0.439      | -            | -                | -                | -         |     1.60 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           41 |     3219 | 2024-05-16 | Passion UA        | L   | 0.432      | -            | -                | -                | -         |    -8.84 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           40 |     3266 | 2024-05-15 | Endpoint          | W   | 0.426      | -            | -                | -                | -         |     4.89 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           39 |     3438 | 2024-05-09 | 1WIN              | W   | 0.386      | -            | -                | -                | -         |     2.95 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           38 |     3461 | 2024-05-08 | Grannys Knockers  | W   | 0.380      | -            | -                | -                | -         |     1.27 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           37 |     3479 | 2024-05-07 | 9 Pandas          | W   | 0.373      | -            | -                | -                | -         |     4.48 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           36 |     3493 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.368      | -            | -                | -                | -         |     4.58 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           35 |     3507 | 2024-05-05 | Gaimin Gladiators | L   | 0.361      | -            | -                | -                | -         |    -8.58 | Cabbi, IceBerg, kwezz, Lucky, PR1mE  |
|           34 |     3515 | 2024-05-05 | Come on now dawg  | W   | 0.360      | -            | -                | -                | -         |     0.21 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           33 |     3567 | 2024-05-02 | fnatic            | W   | 0.341      | 0.384        | 0.294 (0.038)    | -                | -         |     8.29 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           32 |     3602 | 2024-05-01 | 3DMAX             | W   | 0.333      | 0.384        | 0.509 (0.065)    | -                | -         |    10.15 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           31 |     3619 | 2024-04-30 | OG                | W   | 0.327      | -            | -                | -                | -         |     3.63 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           30 |     3644 | 2024-04-29 | 500               | W   | 0.319      | -            | -                | -                | -         |     0.83 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           29 |     3672 | 2024-04-27 | 777               | W   | 0.308      | -            | -                | -                | -         |     0.87 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           28 |     3676 | 2024-04-27 | JANO              | W   | 0.308      | -            | -                | -                | -         |     0.79 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           27 |     3743 | 2024-04-25 | Passion UA        | W   | 0.293      | -            | -                | -                | -         |     3.64 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           26 |     3777 | 2024-04-23 | Gaimin Gladiators | W   | 0.280      | -            | -                | -                | -         |     2.54 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           25 |     3782 | 2024-04-23 | BLEED             | W   | 0.279      | -            | -                | -                | -         |     2.32 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           24 |     3833 | 2024-04-20 | Eternal Fire      | W   | 0.261      | 0.143        | 0.972 (0.036)    | -                | -         |     8.14 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           23 |     3840 | 2024-04-20 | Cloud9            | W   | 0.260      | -            | -                | -                | -         |     1.51 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           22 |     3879 | 2024-04-19 | Eternal Fire      | L   | 0.255      | -            | -                | -                | -         |    -0.09 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           21 |     3888 | 2024-04-19 | Cloud9            | W   | 0.253      | -            | -                | -                | -         |     1.44 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           20 |     3914 | 2024-04-18 | ex-Guild Eagles   | W   | 0.248      | -            | -                | -                | -         |     1.14 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           19 |     3918 | 2024-04-18 | RUBY              | W   | 0.248      | -            | -                | -                | -         |     2.14 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           18 |     3927 | 2024-04-18 | GamerLegion       | W   | 0.247      | -            | -                | -                | -         |     3.94 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           17 |     3971 | 2024-04-17 | Passion UA        | L   | 0.240      | -            | -                | -                | -         |    -4.28 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           16 |     4008 | 2024-04-16 | ex-Guild Eagles   | L   | 0.233      | -            | -                | -                | -         |    -6.36 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           15 |     4029 | 2024-04-15 | ex-Preasy         | W   | 0.226      | -            | -                | -                | -         |     0.72 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           14 |     4046 | 2024-04-14 | UNiTY             | W   | 0.219      | -            | -                | -                | -         |     1.92 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           13 |     4104 | 2024-04-11 | Enterprise        | W   | 0.199      | -            | -                | -                | -         |     1.64 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           12 |     4147 | 2024-04-10 | Passion UA        | L   | 0.193      | -            | -                | -                | -         |    -3.49 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           11 |     4280 | 2024-04-06 | UNiTY             | W   | 0.165      | -            | -                | -                | -         |     1.46 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|           10 |     4337 | 2024-04-04 | UNiTY             | W   | 0.153      | -            | -                | -                | -         |     1.35 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|            9 |     4421 | 2024-04-02 | Permitta          | W   | 0.139      | -            | -                | -                | -         |     1.51 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|            8 |     4430 | 2024-04-01 | Nexus             | L   | 0.133      | -            | -                | -                | -         |    -3.41 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|            7 |     4504 | 2024-03-27 | Rebels            | L   | 0.101      | -            | -                | -                | -         |    -2.22 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|            6 |     4539 | 2024-03-25 | Nexus             | W   | 0.087      | -            | -                | -                | -         |     0.50 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|            5 |     4563 | 2024-03-22 | Nemiga            | W   | 0.068      | -            | -                | -                | -         |     1.35 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|            4 |     4628 | 2024-03-19 | RUBY              | W   | 0.048      | -            | -                | -                | -         |     0.39 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|            3 |     4640 | 2024-03-18 | Insilio           | W   | 0.040      | -            | -                | -                | -         |     0.36 | Cabbi, IceBerg, kwezz, Lucky, MistR  |
|            2 |     4708 | 2024-03-15 | ECLOT             | W   | 0.019      | -            | -                | -                | -         |     0.31 | Cabbi, IceBerg, larsen, Lucky, MistR |
|            1 |     4782 | 2024-03-13 | BLEED             | L   | 0.006      | -            | -                | -                | -         |    -0.14 | Cabbi, IceBerg, kwezz, Lucky, MistR  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,964.75)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.15) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-11 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-21 |      0.875 | $15,000.00     | $13,120.83      |
| 2024-07-13 |      0.820 | $3,216.00      | $2,637.12       |
| 2024-06-12 |      0.615 | $9,365.00      | $5,754.92       |
| 2024-06-09 |      0.594 | $8,000.00      | $4,751.11       |
| 2024-05-18 |      0.448 | $5,000.00      | $2,238.89       |
| 2024-05-09 |      0.386 | $14,000.00     | $5,409.44       |
| 2024-05-02 |      0.341 | $12,500.00     | $4,260.42       |
| 2024-04-27 |      0.308 | $6,375.00      | $1,965.63       |
| 2024-04-06 |      0.165 | $5,000.00      | $826.39         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
