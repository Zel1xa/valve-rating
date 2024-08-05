### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [98](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [71]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.8<br />
<br />
Final Rank Value (855.8) = Starting Rank Value (817.8) + Head To Head Adjustments (38.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.088[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 817.8
- 400 + ( ( 0.204 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 817.8


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
|           20 |     1588 | 2024-06-01 | panelinha         | L   | 0.772      | -            | -                | -                | -         |   -12.16 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     1619 | 2024-05-31 | TSM Shimmer       | W   | 0.767      | 0.524        | 0.020 (0.008)    | 0.199 (0.080)    | 1 (0.767) |     7.57 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1627 | 2024-05-31 | Let Her Cook      | L   | 0.765      | -            | -                | -                | -         |   -10.63 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1943 | 2024-05-19 | Imperial fe       | W   | 0.684      | 0.281        | 0.128 (0.025)    | 0.299 (0.058)    | 0 (0.000) |    15.87 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     1950 | 2024-05-19 | BIG EQUIPA        | W   | 0.683      | 0.281        | 0.017 (0.003)    | 0.150 (0.029)    | 0 (0.000) |     8.78 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     1978 | 2024-05-18 | Spirit fe         | W   | 0.677      | 0.281        | 0.005 (0.001)    | 0.141 (0.027)    | 0 (0.000) |     5.15 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     2712 | 2024-04-19 | Crescent fe       | W   | 0.485      | 0.331        | 0.005 (0.001)    | 0.078 (0.012)    | 0 (0.000) |     3.85 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     2840 | 2024-04-16 | Imperial fe       | W   | 0.464      | 0.303        | 0.128 (0.018)    | 0.299 (0.042)    | 0 (0.000) |    11.28 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     2862 | 2024-04-15 | NIP Impact        | W   | 0.458      | 0.303        | 0.005 (0.001)    | 0.228 (0.032)    | 0 (0.000) |     5.44 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2879 | 2024-04-14 | Astralis W        | W   | 0.450      | -            | -                | -                | 0 (0.000) |     3.41 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2893 | 2024-04-13 | Imperial fe       | L   | 0.444      | -            | -                | -                | -         |    -3.10 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     2934 | 2024-04-11 | Spirit fe         | W   | 0.430      | 0.303        | 0.005 (0.001)    | 0.141 (0.018)    | 0 (0.000) |     3.88 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     3034 | 2024-04-09 | NIP Impact        | L   | 0.417      | -            | -                | -                | -         |    -8.38 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3160 | 2024-04-04 | Spirit fe         | W   | 0.385      | 0.331        | 0.005 (0.001)    | 0.141 (0.018)    | 0 (0.000) |     3.55 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3200 | 2024-04-03 | Let Her Cook      | L   | 0.378      | -            | -                | -                | -         |    -4.34 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3572 | 2024-03-14 | 1WIN Gang         | W   | 0.245      | -            | -                | -                | -         |     2.15 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3777 | 2024-03-06 | Fearless Cheetahs | W   | 0.192      | -            | -                | -                | -         |     1.88 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     3997 | 2024-02-25 | BIG EQUIPA        | W   | 0.124      | 0.238        | 0.017 (0.001)    | 0.150 (0.004)    | -         |     1.68 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     4002 | 2024-02-25 | ENCE Athena       | W   | 0.123      | -            | -                | -                | -         |     1.04 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     4031 | 2024-02-24 | Crescent fe       | W   | 0.117      | -            | -                | -                | -         |     1.10 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,523.15)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.779 | $7,000.00      | $5,452.22       |
| 2024-05-19 |      0.684 | $2,000.00      | $1,367.41       |
| 2024-04-16 |      0.464 | $3,500.00      | $1,625.56       |
| 2024-02-25 |      0.124 | $630.00        | $77.96          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
