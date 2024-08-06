### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [104](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.5<br />
<br />
Final Rank Value (855.5) = Starting Rank Value (818.2) + Head To Head Adjustments (37.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.387[<sup>1</sup>](#table2)
- Bounty Collected: 0.308[<sup>2</sup>](#table1)
- Opponent Network: 0.030[<sup>2</sup>](#table1)
- LAN Wins: 0.087[<sup>2</sup>](#table1)

The average of these factors is 0.203<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 818.2
- 400 + ( ( 0.203 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 818.2


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
|           20 |     1620 | 2024-06-01 | panelinha         | L   | 0.762      | -            | -                | -                | -         |   -11.99 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     1651 | 2024-05-31 | TSM Shimmer       | W   | 0.757      | 0.524        | 0.020 (0.008)    | 0.191 (0.076)    | 1 (0.757) |     7.51 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1659 | 2024-05-31 | Let Her Cook      | L   | 0.755      | -            | -                | -                | -         |   -10.44 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1975 | 2024-05-19 | Imperial fe       | W   | 0.674      | 0.281        | 0.128 (0.024)    | 0.287 (0.055)    | 0 (0.000) |    15.68 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     1982 | 2024-05-19 | BIG EQUIPA        | W   | 0.673      | 0.281        | 0.017 (0.003)    | 0.142 (0.027)    | 0 (0.000) |     8.67 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     2010 | 2024-05-18 | Spirit fe         | W   | 0.667      | 0.281        | 0.005 (0.001)    | 0.136 (0.025)    | 0 (0.000) |     5.12 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     2744 | 2024-04-19 | Crescent fe       | W   | 0.475      | 0.331        | 0.004 (0.001)    | 0.074 (0.012)    | 0 (0.000) |     3.80 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     2872 | 2024-04-16 | Imperial fe       | W   | 0.455      | 0.303        | 0.128 (0.018)    | 0.287 (0.040)    | 0 (0.000) |    11.06 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     2894 | 2024-04-15 | NIP Impact        | W   | 0.448      | 0.303        | 0.005 (0.001)    | 0.219 (0.030)    | 0 (0.000) |     5.33 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2911 | 2024-04-14 | Astralis W        | W   | 0.441      | -            | -                | -                | 0 (0.000) |     3.34 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2925 | 2024-04-13 | Imperial fe       | L   | 0.434      | -            | -                | -                | -         |    -3.03 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     2966 | 2024-04-11 | Spirit fe         | W   | 0.421      | 0.303        | 0.005 (0.001)    | 0.136 (0.017)    | 0 (0.000) |     3.81 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     3066 | 2024-04-09 | NIP Impact        | L   | 0.408      | -            | -                | -                | -         |    -8.19 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3192 | 2024-04-04 | Spirit fe         | W   | 0.375      | 0.331        | 0.005 (0.001)    | 0.136 (0.017)    | 0 (0.000) |     3.48 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3232 | 2024-04-03 | Let Her Cook      | L   | 0.368      | -            | -                | -                | -         |    -4.22 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3604 | 2024-03-14 | 1WIN Gang         | W   | 0.235      | -            | -                | -                | -         |     2.08 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3809 | 2024-03-06 | Fearless Cheetahs | W   | 0.182      | -            | -                | -                | -         |     1.79 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     4029 | 2024-02-25 | BIG EQUIPA        | W   | 0.114      | 0.238        | 0.017 (0.000)    | 0.142 (0.004)    | -         |     1.55 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     4034 | 2024-02-25 | ENCE Athena       | W   | 0.113      | -            | -                | -                | -         |     0.96 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     4063 | 2024-02-24 | Crescent fe       | W   | 0.107      | -            | -                | -                | -         |     1.01 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,399.14)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.769 | $7,000.00      | $5,386.11       |
| 2024-05-19 |      0.674 | $2,000.00      | $1,348.52       |
| 2024-04-16 |      0.455 | $3,500.00      | $1,592.50       |
| 2024-02-25 |      0.114 | $630.00        | $72.01          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
