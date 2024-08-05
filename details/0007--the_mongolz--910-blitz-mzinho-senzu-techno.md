### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1698.7<br />
<br />
Final Rank Value (1698.7) = Starting Rank Value (1952.4) + Head To Head Adjustments (-253.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.619[<sup>2</sup>](#table1)
- Opponent Network: 0.414[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.758<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1952.4
- 400 + ( ( 0.758 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1952.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           53 |      288 | 2024-07-28 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -26.61 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |      306 | 2024-07-28 | Eternal Fire      | W   | 1.000      | 0.650        | 0.740 (0.482)    | 0.455 (0.296)    | 1 (1.000) |    11.76 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |      320 | 2024-07-27 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.472 (0.307)    | 1 (1.000) |     1.77 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |      350 | 2024-07-26 | Aurora            | W   | 1.000      | 0.650        | 0.422 (0.274)    | 0.788 (0.513)    | 1 (1.000) |     6.40 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |      388 | 2024-07-25 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -28.54 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |      410 | 2024-07-24 | ENCE              | W   | 1.000      | 0.650        | -                | 0.438 (0.285)    | 1 (1.000) |     3.83 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |      421 | 2024-07-24 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -30.77 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |      468 | 2024-07-23 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |      619 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |   -22.74 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |      623 | 2024-07-18 | M80               | W   | 1.000      | 1.000        | 0.188 (0.188)    | 0.584 (0.584)    | 1 (1.000) |     1.66 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |      635 | 2024-07-18 | MIBR              | W   | 1.000      | 1.000        | 0.208 (0.208)    | 0.657 (0.657)    | 1 (1.000) |     3.19 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |      709 | 2024-07-17 | G2                | L   | 1.000      | -            | -                | -                | -         |    -9.15 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |      864 | 2024-07-11 | CatEvil           | L   | 1.000      | -            | -                | -                | -         |   -31.46 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |      867 | 2024-07-11 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -31.37 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |      871 | 2024-07-11 | Steel Helmet      | W   | 1.000      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |     1052 | 2024-06-15 | Falcons           | L   | 0.860      | -            | -                | -                | -         |   -25.06 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |     1093 | 2024-06-14 | Aurora            | L   | 0.854      | -            | -                | -                | -         |   -25.03 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |     1106 | 2024-06-14 | Party Astronauts  | W   | 0.852      | -            | -                | -                | 1 (0.852) |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     1240 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.821      | 0.715        | 0.254 (0.149)    | 0.551 (0.324)    | 1 (0.821) |     4.23 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     1318 | 2024-06-08 | Astralis          | W   | 0.813      | 0.715        | 0.390 (0.227)    | -                | 1 (0.813) |     7.32 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     1420 | 2024-06-06 | Astralis          | L   | 0.801      | -            | -                | -                | -         |   -18.60 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     1437 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.800      | 0.715        | 0.254 (0.145)    | 0.551 (0.316)    | -         |     3.63 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     1459 | 2024-06-06 | HEROIC            | W   | 0.799      | 0.715        | 0.225 (0.129)    | -                | -         |     3.14 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     1489 | 2024-06-05 | ENCE              | W   | 0.794      | -            | -                | -                | -         |     1.06 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     1506 | 2024-06-05 | Sashi             | W   | 0.792      | 0.715        | -                | 0.996 (0.564)    | -         |     0.46 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     1592 | 2024-06-02 | BLEED             | W   | 0.773      | -            | -                | -                | -         |     1.29 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     1626 | 2024-06-01 | BLEED             | W   | 0.766      | -            | -                | -                | -         |     1.18 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     1705 | 2024-05-29 | Aurora            | W   | 0.746      | 0.500        | 0.422 (0.157)    | 0.788 (0.294)    | -         |     2.91 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     1726 | 2024-05-28 | Gaimin Gladiators | W   | 0.739      | -            | -                | -                | -         |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     2000 | 2024-05-18 | ATOX              | W   | 0.672      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     2035 | 2024-05-16 | Chinggis Warriors | W   | 0.665      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2305 | 2024-05-08 | Virtus.pro        | L   | 0.608      | -            | -                | -                | -         |   -14.86 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     2514 | 2024-04-28 | Vitality          | L   | 0.540      | -            | -                | -                | -         |   -10.07 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     2591 | 2024-04-25 | G2                | W   | 0.520      | 0.889        | 1.000 (0.462)    | -                | -         |     9.47 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     2610 | 2024-04-24 | Falcons           | W   | 0.513      | -            | -                | -                | -         |     0.95 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     2737 | 2024-04-19 | Rare Atom         | W   | 0.480      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     2786 | 2024-04-18 | TYLOO             | W   | 0.473      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     2797 | 2024-04-18 | Rare Atom         | W   | 0.472      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3226 | 2024-04-03 | Lynn Vision       | W   | 0.373      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3239 | 2024-04-03 | LYG               | W   | 0.372      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3265 | 2024-04-02 | ATOX              | W   | 0.367      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     3269 | 2024-04-02 | LYG               | L   | 0.365      | -            | -                | -                | -         |   -11.50 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     3416 | 2024-03-22 | paiN              | L   | 0.294      | -            | -                | -                | -         |    -8.77 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     3438 | 2024-03-21 | Vitality          | L   | 0.288      | -            | -                | -                | -         |    -5.63 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     3448 | 2024-03-21 | Natus Vincere     | L   | 0.286      | -            | -                | -                | -         |    -4.07 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     3467 | 2024-03-20 | Legacy            | W   | 0.280      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     3485 | 2024-03-19 | Lynn Vision       | W   | 0.273      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     3491 | 2024-03-18 | AMKAL             | W   | 0.267      | -            | -                | -                | -         |     0.09 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     3513 | 2024-03-17 | Gaimin Gladiators | L   | 0.261      | -            | -                | -                | -         |    -8.20 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     3526 | 2024-03-17 | Eternal Fire      | L   | 0.260      | -            | -                | -                | -         |    -6.60 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     3960 | 2024-02-27 | Lynn Vision       | W   | 0.137      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     3996 | 2024-02-25 | FlyQuest          | W   | 0.125      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     4002 | 2024-02-25 | MAG               | W   | 0.124      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($322,333.56)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-07-21 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-16 |      0.867 | $3,000.00      | $2,600.83       |
| 2024-06-09 |      0.821 | $200,000.00    | $164,111.11     |
| 2024-06-02 |      0.773 | $50,000.00     | $38,630.79      |
| 2024-05-12 |      0.634 | $23,500.00     | $14,896.39      |
| 2024-03-31 |      0.355 | $20,000.00     | $7,094.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
