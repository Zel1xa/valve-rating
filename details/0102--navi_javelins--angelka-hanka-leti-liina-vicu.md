### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.5<br />
<br />
Final Rank Value (855.5) = Starting Rank Value (817.9) + Head To Head Adjustments (37.7)<br />

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
|           20 |     1610 | 2024-06-01 | panelinha         | L   | 0.767      | -            | -                | -                | -         |   -12.08 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     1641 | 2024-05-31 | TSM Shimmer       | W   | 0.762      | 0.524        | 0.020 (0.008)    | 0.196 (0.078)    | 1 (0.762) |     7.54 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1649 | 2024-05-31 | Let Her Cook      | L   | 0.760      | -            | -                | -                | -         |   -10.53 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1965 | 2024-05-19 | Imperial fe       | W   | 0.679      | 0.281        | 0.128 (0.024)    | 0.294 (0.056)    | 0 (0.000) |    15.77 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     1972 | 2024-05-19 | BIG EQUIPA        | W   | 0.678      | 0.281        | 0.017 (0.003)    | 0.147 (0.028)    | 0 (0.000) |     8.72 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     2000 | 2024-05-18 | Spirit fe         | W   | 0.672      | 0.281        | 0.005 (0.001)    | 0.139 (0.026)    | 0 (0.000) |     5.14 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     2734 | 2024-04-19 | Crescent fe       | W   | 0.480      | 0.331        | 0.005 (0.001)    | 0.076 (0.012)    | 0 (0.000) |     3.82 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     2862 | 2024-04-16 | Imperial fe       | W   | 0.460      | 0.303        | 0.128 (0.018)    | 0.294 (0.041)    | 0 (0.000) |    11.17 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     2884 | 2024-04-15 | NIP Impact        | W   | 0.453      | 0.303        | 0.005 (0.001)    | 0.225 (0.031)    | 0 (0.000) |     5.38 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2901 | 2024-04-14 | Astralis W        | W   | 0.445      | -            | -                | -                | 0 (0.000) |     3.37 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2915 | 2024-04-13 | Imperial fe       | L   | 0.439      | -            | -                | -                | -         |    -3.06 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     2956 | 2024-04-11 | Spirit fe         | W   | 0.425      | 0.303        | 0.005 (0.001)    | 0.139 (0.018)    | 0 (0.000) |     3.84 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     3056 | 2024-04-09 | NIP Impact        | L   | 0.412      | -            | -                | -                | -         |    -8.28 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3182 | 2024-04-04 | Spirit fe         | W   | 0.380      | 0.331        | 0.005 (0.001)    | 0.139 (0.017)    | 0 (0.000) |     3.51 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3222 | 2024-04-03 | Let Her Cook      | L   | 0.373      | -            | -                | -                | -         |    -4.28 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3594 | 2024-03-14 | 1WIN Gang         | W   | 0.240      | -            | -                | -                | -         |     2.11 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3799 | 2024-03-06 | Fearless Cheetahs | W   | 0.187      | -            | -                | -                | -         |     1.83 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     4019 | 2024-02-25 | BIG EQUIPA        | W   | 0.119      | 0.238        | 0.017 (0.000)    | 0.147 (0.004)    | -         |     1.62 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     4024 | 2024-02-25 | ENCE Athena       | W   | 0.118      | -            | -                | -                | -         |     1.00 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     4053 | 2024-02-24 | Crescent fe       | W   | 0.112      | -            | -                | -                | -         |     1.05 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,459.32)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.774 | $7,000.00      | $5,418.19       |
| 2024-05-19 |      0.679 | $2,000.00      | $1,357.69       |
| 2024-04-16 |      0.460 | $3,500.00      | $1,608.54       |
| 2024-02-25 |      0.119 | $630.00        | $74.90          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
