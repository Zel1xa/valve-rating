### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1691.9<br />
<br />
Final Rank Value (1691.9) = Starting Rank Value (1956.1) + Head To Head Adjustments (-264.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.617[<sup>2</sup>](#table1)
- Opponent Network: 0.408[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.756<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1956.1
- 400 + ( ( 0.756 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1956.1


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
|           53 |      155 | 2024-07-28 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -26.67 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |      173 | 2024-07-28 | Eternal Fire      | W   | 1.000      | 0.650        | 0.757 (0.492)    | 0.461 (0.300)    | 1 (1.000) |    12.21 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |      187 | 2024-07-27 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.482 (0.313)    | 1 (1.000) |     1.83 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |      217 | 2024-07-26 | Aurora            | W   | 1.000      | 0.650        | 0.431 (0.281)    | 0.798 (0.519)    | 1 (1.000) |     6.47 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |      255 | 2024-07-25 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -28.41 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |      277 | 2024-07-24 | ENCE              | W   | 1.000      | 0.650        | -                | 0.403 (0.262)    | 1 (1.000) |     3.69 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |      288 | 2024-07-24 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -30.76 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |      335 | 2024-07-23 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |      495 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |   -22.75 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |      499 | 2024-07-18 | M80               | W   | 1.000      | 1.000        | 0.190 (0.190)    | 0.641 (0.641)    | 1 (1.000) |     1.90 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |      511 | 2024-07-18 | MIBR              | W   | 1.000      | 1.000        | 0.201 (0.201)    | 0.637 (0.637)    | 1 (1.000) |     2.52 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |      585 | 2024-07-17 | G2                | L   | 1.000      | -            | -                | -                | -         |    -9.05 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |      748 | 2024-07-11 | CatEvil           | L   | 1.000      | -            | -                | -                | -         |   -31.46 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |      751 | 2024-07-11 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -31.44 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |      755 | 2024-07-11 | Steel Helmet      | W   | 1.000      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |      932 | 2024-06-15 | Falcons           | L   | 0.886      | -            | -                | -                | -         |   -25.55 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |      966 | 2024-06-14 | Aurora            | L   | 0.879      | -            | -                | -                | -         |   -25.75 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |      979 | 2024-06-14 | Party Astronauts  | W   | 0.877      | -            | -                | -                | 1 (0.877) |     0.17 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     1115 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.846      | 0.715        | 0.207 (0.125)    | 0.447 (0.271)    | 1 (0.846) |     2.71 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     1197 | 2024-06-08 | Astralis          | W   | 0.839      | 0.715        | 0.359 (0.215)    | -                | 1 (0.839) |     6.69 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     1306 | 2024-06-06 | Astralis          | L   | 0.827      | -            | -                | -                | -         |   -20.06 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     1323 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.826      | 0.715        | 0.207 (0.122)    | 0.447 (0.264)    | -         |     2.18 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     1346 | 2024-06-06 | HEROIC            | W   | 0.824      | 0.715        | 0.208 (0.123)    | -                | -         |     3.13 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     1378 | 2024-06-05 | ENCE              | W   | 0.820      | -            | -                | -                | -         |     1.00 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     1395 | 2024-06-05 | Sashi             | W   | 0.818      | 0.715        | -                | 0.970 (0.568)    | -         |     0.48 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     1482 | 2024-06-02 | BLEED             | W   | 0.798      | -            | -                | -                | -         |     1.38 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     1516 | 2024-06-01 | BLEED             | W   | 0.791      | -            | -                | -                | -         |     1.26 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     1595 | 2024-05-29 | Aurora            | W   | 0.772      | 0.500        | 0.431 (0.166)    | 0.798 (0.308)    | -         |     3.02 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     1616 | 2024-05-28 | Gaimin Gladiators | W   | 0.765      | -            | -                | -                | -         |     0.17 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     1918 | 2024-05-18 | ATOX              | W   | 0.698      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     1953 | 2024-05-16 | Chinggis Warriors | W   | 0.690      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2234 | 2024-05-08 | Virtus.pro        | L   | 0.634      | -            | -                | -                | -         |   -15.40 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     2446 | 2024-04-28 | Vitality          | L   | 0.565      | -            | -                | -                | -         |   -10.76 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     2523 | 2024-04-25 | G2                | W   | 0.545      | 0.889        | 1.000 (0.485)    | -                | -         |     9.87 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     2542 | 2024-04-24 | Falcons           | W   | 0.538      | -            | -                | -                | -         |     1.11 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     2676 | 2024-04-19 | Rare Atom         | W   | 0.506      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     2726 | 2024-04-18 | TYLOO             | W   | 0.499      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     2737 | 2024-04-18 | Rare Atom         | W   | 0.498      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3175 | 2024-04-03 | Lynn Vision       | W   | 0.399      | -            | -                | -                | -         |     0.08 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3190 | 2024-04-03 | LYG               | W   | 0.398      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3216 | 2024-04-02 | ATOX              | W   | 0.392      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     3220 | 2024-04-02 | LYG               | L   | 0.391      | -            | -                | -                | -         |   -12.30 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     3372 | 2024-03-22 | paiN              | L   | 0.319      | -            | -                | -                | -         |    -9.64 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     3394 | 2024-03-21 | Vitality          | L   | 0.313      | -            | -                | -                | -         |    -6.28 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     3404 | 2024-03-21 | Natus Vincere     | L   | 0.312      | -            | -                | -                | -         |    -4.32 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     3423 | 2024-03-20 | Legacy            | W   | 0.305      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     3441 | 2024-03-19 | Lynn Vision       | W   | 0.299      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     3447 | 2024-03-18 | AMKAL             | W   | 0.292      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     3469 | 2024-03-17 | Gaimin Gladiators | L   | 0.287      | -            | -                | -                | -         |    -9.00 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     3482 | 2024-03-17 | Eternal Fire      | L   | 0.285      | -            | -                | -                | -         |    -7.13 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     3929 | 2024-02-27 | Lynn Vision       | W   | 0.163      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     3966 | 2024-02-25 | FlyQuest          | W   | 0.150      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     3972 | 2024-02-25 | MAG               | W   | 0.149      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($329,910.79)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-07-21 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-16 |      0.892 | $3,000.00      | $2,677.50       |
| 2024-06-09 |      0.846 | $200,000.00    | $169,222.22     |
| 2024-06-02 |      0.798 | $50,000.00     | $39,908.56      |
| 2024-05-12 |      0.659 | $23,500.00     | $15,496.94      |
| 2024-03-31 |      0.380 | $20,000.00     | $7,605.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
