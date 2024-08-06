### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1126.6<br />
<br />
Final Rank Value (1126.6) = Starting Rank Value (1160.1) + Head To Head Adjustments (-33.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.576[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.237[<sup>2</sup>](#table1)
- LAN Wins: 0.206[<sup>2</sup>](#table1)

The average of these factors is 0.371<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1160.1
- 400 + ( ( 0.371 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1160.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           97 |        6 | 2024-08-05 | ECSTATIC          | L   | 1.000      | -            | -                | -                | -         |   -30.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           96 |       10 | 2024-08-05 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -23.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           95 |       16 | 2024-08-05 | ECSTATIC          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           94 |      196 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.552 (0.276)    | 0 (0.000) |     6.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      227 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.500 (0.250)    | 0 (0.000) |     3.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      239 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -17.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      420 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.080 (0.040)    | 0.611 (0.306)    | 0 (0.000) |    10.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      641 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.84 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      651 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      721 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.62 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      848 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      857 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |      874 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.514 (0.184)    | 0 (0.000) |     4.76 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |      898 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.76 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |      901 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.533 (0.191)    | 0 (0.000) |     5.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1105 | 2024-06-14 | 3DMAX             | L   | 0.850      | -            | -                | -                | -         |    -5.68 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1140 | 2024-06-13 | Sampi             | W   | 0.843      | -            | -                | -                | 0 (0.000) |     3.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1157 | 2024-06-12 | CPH Wolves        | W   | 0.838      | -            | -                | -                | -         |     2.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1166 | 2024-06-12 | Astralis Talent   | W   | 0.837      | -            | -                | -                | -         |     1.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1422 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.798      | -            | -                | -                | -         |    -2.63 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1458 | 2024-06-06 | HEROIC            | L   | 0.796      | -            | -                | -                | -         |    -3.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1487 | 2024-06-05 | ENCE              | L   | 0.792      | -            | -                | -                | -         |    -7.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1507 | 2024-06-05 | Astralis          | W   | 0.790      | 0.715        | 0.389 (0.220)    | 0.413 (0.233)    | 1 (0.790) |    23.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1517 | 2024-06-05 | The MongolZ       | L   | 0.789      | -            | -                | -                | -         |    -0.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1952 | 2024-05-20 | Monte             | L   | 0.682      | -            | -                | -                | -         |   -15.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1965 | 2024-05-19 | Passion UA        | W   | 0.677      | 0.500        | 0.173 (0.059)    | 1.000 (0.339)    | -         |     5.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     1992 | 2024-05-18 | B8                | L   | 0.671      | -            | -                | -                | -         |   -12.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     2001 | 2024-05-18 | Monte             | W   | 0.670      | -            | -                | -                | -         |     5.55 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     2009 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.669      | 0.500        | -                | 0.550 (0.184)    | -         |     3.89 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     2040 | 2024-05-17 | ex-Guild Eagles   | W   | 0.662      | -            | -                | -                | -         |     2.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2080 | 2024-05-16 | Passion UA        | L   | 0.656      | -            | -                | -                | -         |   -15.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2127 | 2024-05-15 | Endpoint          | W   | 0.649      | -            | -                | -                | -         |     3.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           65 |     2299 | 2024-05-09 | 1WIN              | W   | 0.610      | -            | -                | -                | -         |     4.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2322 | 2024-05-08 | Grannys Knockers  | W   | 0.603      | -            | -                | -                | -         |     1.65 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2340 | 2024-05-07 | 9 Pandas          | W   | 0.597      | -            | -                | -                | -         |     4.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2354 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.591      | -            | -                | -                | -         |     4.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2368 | 2024-05-05 | Gaimin Gladiators | L   | 0.584      | -            | -                | -                | -         |   -14.10 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           60 |     2376 | 2024-05-05 | Come on now dawg  | W   | 0.584      | -            | -                | -                | -         |     0.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2428 | 2024-05-02 | fnatic            | W   | 0.564      | 0.384        | 0.371 (0.080)    | -                | -         |    15.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2463 | 2024-05-01 | 3DMAX             | W   | 0.556      | 0.384        | 0.509 (0.109)    | 1.000 (0.214)    | -         |    16.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2480 | 2024-04-30 | OG                | W   | 0.550      | 0.384        | 0.137 (0.029)    | -                | -         |     6.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2505 | 2024-04-29 | 500               | W   | 0.543      | -            | -                | -                | -         |     1.29 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2533 | 2024-04-27 | 777               | W   | 0.532      | -            | -                | -                | -         |     1.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2537 | 2024-04-27 | JANO              | W   | 0.531      | -            | -                | -                | -         |     1.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2604 | 2024-04-25 | Passion UA        | W   | 0.516      | 0.384        | 0.173 (0.034)    | 1.000 (0.198)    | -         |     5.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2638 | 2024-04-23 | Gaimin Gladiators | W   | 0.503      | -            | -                | -                | -         |     4.99 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2643 | 2024-04-23 | BLEED             | W   | 0.502      | -            | -                | -                | -         |     5.69 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2694 | 2024-04-20 | Eternal Fire      | W   | 0.485      | 0.143        | 0.739 (0.051)    | -                | -         |    14.64 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2701 | 2024-04-20 | Cloud9            | W   | 0.483      | -            | -                | -                | -         |     6.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2740 | 2024-04-19 | Eternal Fire      | L   | 0.478      | -            | -                | -                | -         |    -0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2749 | 2024-04-19 | Cloud9            | W   | 0.477      | -            | -                | -                | -         |     6.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2775 | 2024-04-18 | ex-Guild Eagles   | W   | 0.472      | -            | -                | -                | -         |     2.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2779 | 2024-04-18 | RUBY              | W   | 0.471      | -            | -                | -                | -         |     3.97 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2788 | 2024-04-18 | GamerLegion       | W   | 0.471      | -            | -                | -                | -         |     7.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2832 | 2024-04-17 | Passion UA        | L   | 0.463      | -            | -                | -                | -         |    -8.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     2869 | 2024-04-16 | ex-Guild Eagles   | L   | 0.457      | -            | -                | -                | -         |   -12.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     2890 | 2024-04-15 | ex-Preasy         | W   | 0.450      | -            | -                | -                | -         |     2.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     2907 | 2024-04-14 | UNiTY             | W   | 0.442      | -            | -                | -                | -         |     3.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     2965 | 2024-04-11 | Enterprise        | W   | 0.422      | -            | -                | -                | -         |     3.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     3008 | 2024-04-10 | Passion UA        | L   | 0.416      | -            | -                | -                | -         |    -8.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3141 | 2024-04-06 | UNiTY             | W   | 0.389      | -            | -                | -                | -         |     3.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3198 | 2024-04-04 | UNiTY             | W   | 0.376      | -            | -                | -                | -         |     3.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3282 | 2024-04-02 | Permitta          | W   | 0.362      | -            | -                | -                | -         |     3.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3291 | 2024-04-01 | Nexus             | L   | 0.356      | -            | -                | -                | -         |    -9.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3365 | 2024-03-27 | Rebels            | L   | 0.325      | -            | -                | -                | -         |    -7.17 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           32 |     3400 | 2024-03-25 | Nexus             | W   | 0.311      | -            | -                | -                | -         |     1.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3424 | 2024-03-22 | Nemiga            | W   | 0.291      | 0.372        | 0.315 (0.034)    | -                | -         |     4.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           30 |     3489 | 2024-03-19 | RUBY              | W   | 0.271      | -            | -                | -                | -         |     2.05 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           29 |     3501 | 2024-03-18 | Insilio           | W   | 0.264      | -            | -                | -                | -         |     1.79 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     3569 | 2024-03-15 | ECLOT             | W   | 0.242      | -            | -                | -                | -         |     4.54 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3643 | 2024-03-13 | BLEED             | L   | 0.229      | -            | -                | -                | -         |    -5.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3690 | 2024-03-11 | Nemiga            | L   | 0.217      | -            | -                | -                | -         |    -3.08 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           25 |     3713 | 2024-03-10 | Sampi             | L   | 0.209      | -            | -                | -                | -         |    -5.32 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           24 |     3737 | 2024-03-09 | Permitta          | W   | 0.203      | -            | -                | -                | -         |     1.81 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           23 |     3758 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.196      | -            | -                | -                | -         |    -4.39 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           22 |     3768 | 2024-03-07 | Insilio           | W   | 0.192      | -            | -                | -                | -         |     1.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3782 | 2024-03-07 | ex-sYnck          | W   | 0.190      | -            | -                | -                | -         |     0.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3814 | 2024-03-06 | Alliance          | W   | 0.183      | -            | -                | -                | -         |     0.96 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3848 | 2024-03-05 | Johnny Speeds     | L   | 0.178      | -            | -                | -                | -         |    -1.62 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3857 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.176      | -            | -                | -                | -         |    -4.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3873 | 2024-03-04 | Entropiq          | L   | 0.169      | -            | -                | -                | -         |    -5.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3918 | 2024-03-02 | brazylijski luz   | W   | 0.157      | -            | -                | -                | -         |     0.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3952 | 2024-02-29 | JANO              | W   | 0.142      | -            | -                | -                | -         |     0.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3962 | 2024-02-28 | Sampi             | W   | 0.137      | -            | -                | -                | -         |     0.80 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     3977 | 2024-02-27 | V1dar             | L   | 0.131      | -            | -                | -                | -         |    -4.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4018 | 2024-02-25 | Sangal            | L   | 0.118      | -            | -                | -                | -         |    -1.84 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4024 | 2024-02-25 | PGE Turow         | L   | 0.116      | -            | -                | -                | -         |    -3.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4064 | 2024-02-24 | MOUZ NXT          | L   | 0.109      | -            | -                | -                | -         |    -2.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4115 | 2024-02-21 | Sampi             | W   | 0.090      | -            | -                | -                | -         |     0.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4213 | 2024-02-17 | Zero Tenacity     | W   | 0.064      | -            | -                | -                | -         |     0.85 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4361 | 2024-02-11 | ARCRED            | W   | 0.023      | -            | -                | -                | -         |     0.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4363 | 2024-02-10 | Nemiga            | L   | 0.019      | -            | -                | -                | -         |    -0.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4371 | 2024-02-10 | AMKAL             | W   | 0.017      | -            | -                | -                | -         |     0.26 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4380 | 2024-02-09 | FORZE             | W   | 0.012      | -            | -                | -                | -         |     0.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4386 | 2024-02-09 | Insilio           | W   | 0.010      | -            | -                | -                | -         |     0.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4394 | 2024-02-08 | Nemiga            | L   | 0.005      | -            | -                | -                | -         |    -0.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4398 | 2024-02-08 | FORZE             | W   | 0.004      | -            | -                | -                | -         |     0.02 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($59,052.23)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.838 | $9,365.00      | $7,846.44       |
| 2024-06-09 |      0.817 | $8,000.00      | $6,537.78       |
| 2024-05-18 |      0.671 | $5,000.00      | $3,355.56       |
| 2024-05-09 |      0.610 | $14,000.00     | $8,536.11       |
| 2024-05-02 |      0.564 | $12,500.00     | $7,052.08       |
| 2024-04-27 |      0.532 | $6,375.00      | $3,389.37       |
| 2024-04-06 |      0.389 | $5,000.00      | $1,943.06       |
| 2024-03-25 |      0.311 | $7,000.00      | $2,175.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
