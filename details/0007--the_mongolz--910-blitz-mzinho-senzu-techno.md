### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1698.9<br />
<br />
Final Rank Value (1698.9) = Starting Rank Value (1951.7) + Head To Head Adjustments (-252.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.618[<sup>2</sup>](#table1)
- Opponent Network: 0.408[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.756<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1951.7
- 400 + ( ( 0.756 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1951.7


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
|           53 |      299 | 2024-07-28 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -26.56 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |      317 | 2024-07-28 | Eternal Fire      | W   | 1.000      | 0.650        | 0.739 (0.481)    | 0.449 (0.292)    | 1 (1.000) |    11.76 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |      331 | 2024-07-27 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.464 (0.302)    | 1 (1.000) |     1.77 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |      361 | 2024-07-26 | Aurora            | W   | 1.000      | 0.650        | 0.421 (0.274)    | 0.777 (0.506)    | 1 (1.000) |     6.47 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |      399 | 2024-07-25 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -28.51 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |      421 | 2024-07-24 | ENCE              | W   | 1.000      | 0.650        | -                | 0.432 (0.281)    | 1 (1.000) |     3.87 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |      432 | 2024-07-24 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -30.77 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |      479 | 2024-07-23 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |      630 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |   -22.74 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |      634 | 2024-07-18 | M80               | W   | 1.000      | 1.000        | 0.188 (0.188)    | 0.576 (0.576)    | 1 (1.000) |     1.65 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |      646 | 2024-07-18 | MIBR              | W   | 1.000      | 1.000        | 0.208 (0.208)    | 0.648 (0.648)    | 1 (1.000) |     3.17 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |      720 | 2024-07-17 | G2                | L   | 1.000      | -            | -                | -                | -         |    -9.15 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |      875 | 2024-07-11 | CatEvil           | L   | 1.000      | -            | -                | -                | -         |   -31.46 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |      878 | 2024-07-11 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -31.37 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |      882 | 2024-07-11 | Steel Helmet      | W   | 1.000      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |     1063 | 2024-06-15 | Falcons           | L   | 0.857      | -            | -                | -                | -         |   -24.97 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |     1104 | 2024-06-14 | Aurora            | L   | 0.850      | -            | -                | -                | -         |   -24.90 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |     1117 | 2024-06-14 | Party Astronauts  | W   | 0.849      | -            | -                | -                | 1 (0.849) |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     1251 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.817      | 0.715        | 0.254 (0.148)    | 0.544 (0.318)    | 1 (0.817) |     4.21 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     1329 | 2024-06-08 | Astralis          | W   | 0.810      | 0.715        | 0.389 (0.225)    | -                | 1 (0.810) |     7.27 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     1431 | 2024-06-06 | Astralis          | L   | 0.798      | -            | -                | -                | -         |   -18.54 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     1448 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.797      | 0.715        | 0.254 (0.145)    | 0.544 (0.310)    | -         |     3.61 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     1470 | 2024-06-06 | HEROIC            | W   | 0.795      | 0.715        | 0.225 (0.128)    | -                | -         |     3.11 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     1500 | 2024-06-05 | ENCE              | W   | 0.791      | -            | -                | -                | -         |     1.07 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     1517 | 2024-06-05 | Sashi             | W   | 0.789      | 0.715        | -                | 0.982 (0.554)    | -         |     0.46 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     1603 | 2024-06-02 | BLEED             | W   | 0.769      | -            | -                | -                | -         |     1.30 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     1637 | 2024-06-01 | BLEED             | W   | 0.762      | -            | -                | -                | -         |     1.19 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     1716 | 2024-05-29 | Aurora            | W   | 0.743      | 0.500        | 0.421 (0.156)    | 0.777 (0.289)    | -         |     2.94 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     1737 | 2024-05-28 | Gaimin Gladiators | W   | 0.736      | -            | -                | -                | -         |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     2011 | 2024-05-18 | ATOX              | W   | 0.669      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     2046 | 2024-05-16 | Chinggis Warriors | W   | 0.662      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2316 | 2024-05-08 | Virtus.pro        | L   | 0.605      | -            | -                | -                | -         |   -14.79 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     2525 | 2024-04-28 | Vitality          | L   | 0.536      | -            | -                | -                | -         |   -10.01 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     2602 | 2024-04-25 | G2                | W   | 0.516      | 0.889        | 1.000 (0.459)    | -                | -         |     9.42 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     2621 | 2024-04-24 | Falcons           | W   | 0.510      | -            | -                | -                | -         |     0.94 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     2748 | 2024-04-19 | Rare Atom         | W   | 0.477      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     2797 | 2024-04-18 | TYLOO             | W   | 0.470      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     2808 | 2024-04-18 | Rare Atom         | W   | 0.469      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3237 | 2024-04-03 | Lynn Vision       | W   | 0.370      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3250 | 2024-04-03 | LYG               | W   | 0.369      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3276 | 2024-04-02 | ATOX              | W   | 0.363      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     3280 | 2024-04-02 | LYG               | L   | 0.362      | -            | -                | -                | -         |   -11.39 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     3427 | 2024-03-22 | paiN              | L   | 0.290      | -            | -                | -                | -         |    -8.68 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     3449 | 2024-03-21 | Vitality          | L   | 0.285      | -            | -                | -                | -         |    -5.56 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     3459 | 2024-03-21 | Natus Vincere     | L   | 0.283      | -            | -                | -                | -         |    -4.02 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     3478 | 2024-03-20 | Legacy            | W   | 0.276      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     3496 | 2024-03-19 | Lynn Vision       | W   | 0.270      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     3502 | 2024-03-18 | AMKAL             | W   | 0.264      | -            | -                | -                | -         |     0.09 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     3524 | 2024-03-17 | Gaimin Gladiators | L   | 0.258      | -            | -                | -                | -         |    -8.09 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     3537 | 2024-03-17 | Eternal Fire      | L   | 0.256      | -            | -                | -                | -         |    -6.51 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     3971 | 2024-02-27 | Lynn Vision       | W   | 0.134      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     4007 | 2024-02-25 | FlyQuest          | W   | 0.121      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     4013 | 2024-02-25 | MAG               | W   | 0.120      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($321,345.23)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-07-21 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-16 |      0.864 | $3,000.00      | $2,590.83       |
| 2024-06-09 |      0.817 | $200,000.00    | $163,444.44     |
| 2024-06-02 |      0.769 | $50,000.00     | $38,464.12      |
| 2024-05-12 |      0.631 | $23,500.00     | $14,818.06      |
| 2024-03-31 |      0.351 | $20,000.00     | $7,027.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
