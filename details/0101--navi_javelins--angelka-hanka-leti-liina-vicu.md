### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [101](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [72]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.6<br />
<br />
Final Rank Value (855.6) = Starting Rank Value (817.9) + Head To Head Adjustments (37.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.088[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 817.9
- 400 + ( ( 0.204 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 817.9


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
|           20 |     1609 | 2024-06-01 | panelinha         | L   | 0.767      | -            | -                | -                | -         |   -12.09 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     1640 | 2024-05-31 | TSM Shimmer       | W   | 0.762      | 0.524        | 0.020 (0.008)    | 0.196 (0.078)    | 1 (0.762) |     7.54 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1648 | 2024-05-31 | Let Her Cook      | L   | 0.760      | -            | -                | -                | -         |   -10.54 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1964 | 2024-05-19 | Imperial fe       | W   | 0.679      | 0.281        | 0.128 (0.024)    | 0.294 (0.056)    | 0 (0.000) |    15.78 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     1971 | 2024-05-19 | BIG EQUIPA        | W   | 0.678      | 0.281        | 0.017 (0.003)    | 0.147 (0.028)    | 0 (0.000) |     8.73 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     1999 | 2024-05-18 | Spirit fe         | W   | 0.672      | 0.281        | 0.005 (0.001)    | 0.139 (0.026)    | 0 (0.000) |     5.14 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     2733 | 2024-04-19 | Crescent fe       | W   | 0.480      | 0.331        | 0.005 (0.001)    | 0.076 (0.012)    | 0 (0.000) |     3.83 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     2861 | 2024-04-16 | Imperial fe       | W   | 0.460      | 0.303        | 0.128 (0.018)    | 0.294 (0.041)    | 0 (0.000) |    11.18 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     2883 | 2024-04-15 | NIP Impact        | W   | 0.453      | 0.303        | 0.005 (0.001)    | 0.225 (0.031)    | 0 (0.000) |     5.39 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2900 | 2024-04-14 | Astralis W        | W   | 0.446      | -            | -                | -                | 0 (0.000) |     3.38 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2914 | 2024-04-13 | Imperial fe       | L   | 0.439      | -            | -                | -                | -         |    -3.07 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     2955 | 2024-04-11 | Spirit fe         | W   | 0.426      | 0.303        | 0.005 (0.001)    | 0.139 (0.018)    | 0 (0.000) |     3.85 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     3055 | 2024-04-09 | NIP Impact        | L   | 0.413      | -            | -                | -                | -         |    -8.29 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3181 | 2024-04-04 | Spirit fe         | W   | 0.380      | 0.331        | 0.005 (0.001)    | 0.139 (0.017)    | 0 (0.000) |     3.51 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3221 | 2024-04-03 | Let Her Cook      | L   | 0.373      | -            | -                | -                | -         |    -4.29 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3593 | 2024-03-14 | 1WIN Gang         | W   | 0.240      | -            | -                | -                | -         |     2.12 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3798 | 2024-03-06 | Fearless Cheetahs | W   | 0.187      | -            | -                | -                | -         |     1.84 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     4018 | 2024-02-25 | BIG EQUIPA        | W   | 0.119      | 0.238        | 0.017 (0.000)    | 0.147 (0.004)    | -         |     1.62 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     4023 | 2024-02-25 | ENCE Athena       | W   | 0.118      | -            | -                | -                | -         |     1.00 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     4052 | 2024-02-24 | Crescent fe       | W   | 0.112      | -            | -                | -                | -         |     1.06 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,464.79)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.774 | $7,000.00      | $5,421.11       |
| 2024-05-19 |      0.679 | $2,000.00      | $1,358.52       |
| 2024-04-16 |      0.460 | $3,500.00      | $1,610.00       |
| 2024-02-25 |      0.119 | $630.00        | $75.16          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
