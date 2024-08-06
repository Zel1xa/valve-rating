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
|           20 |     1623 | 2024-06-01 | panelinha         | L   | 0.762      | -            | -                | -                | -         |   -11.99 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     1654 | 2024-05-31 | TSM Shimmer       | W   | 0.757      | 0.524        | 0.020 (0.008)    | 0.191 (0.076)    | 1 (0.757) |     7.51 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1662 | 2024-05-31 | Let Her Cook      | L   | 0.755      | -            | -                | -                | -         |   -10.43 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1978 | 2024-05-19 | Imperial fe       | W   | 0.674      | 0.281        | 0.128 (0.024)    | 0.287 (0.054)    | 0 (0.000) |    15.67 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     1985 | 2024-05-19 | BIG EQUIPA        | W   | 0.673      | 0.281        | 0.017 (0.003)    | 0.142 (0.027)    | 0 (0.000) |     8.67 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     2013 | 2024-05-18 | Spirit fe         | W   | 0.667      | 0.281        | 0.005 (0.001)    | 0.136 (0.025)    | 0 (0.000) |     5.12 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     2747 | 2024-04-19 | Crescent fe       | W   | 0.475      | 0.331        | 0.004 (0.001)    | 0.074 (0.012)    | 0 (0.000) |     3.80 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     2875 | 2024-04-16 | Imperial fe       | W   | 0.455      | 0.303        | 0.128 (0.018)    | 0.287 (0.040)    | 0 (0.000) |    11.05 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     2897 | 2024-04-15 | NIP Impact        | W   | 0.448      | 0.303        | 0.005 (0.001)    | 0.219 (0.030)    | 0 (0.000) |     5.32 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2914 | 2024-04-14 | Astralis W        | W   | 0.440      | -            | -                | -                | 0 (0.000) |     3.34 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2928 | 2024-04-13 | Imperial fe       | L   | 0.434      | -            | -                | -                | -         |    -3.03 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     2969 | 2024-04-11 | Spirit fe         | W   | 0.420      | 0.303        | 0.005 (0.001)    | 0.136 (0.017)    | 0 (0.000) |     3.81 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     3069 | 2024-04-09 | NIP Impact        | L   | 0.407      | -            | -                | -                | -         |    -8.18 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3195 | 2024-04-04 | Spirit fe         | W   | 0.375      | 0.331        | 0.005 (0.001)    | 0.136 (0.017)    | 0 (0.000) |     3.47 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3235 | 2024-04-03 | Let Her Cook      | L   | 0.368      | -            | -                | -                | -         |    -4.21 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3607 | 2024-03-14 | 1WIN Gang         | W   | 0.235      | -            | -                | -                | -         |     2.08 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3812 | 2024-03-06 | Fearless Cheetahs | W   | 0.182      | -            | -                | -                | -         |     1.79 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     4032 | 2024-02-25 | BIG EQUIPA        | W   | 0.114      | 0.238        | 0.017 (0.000)    | 0.142 (0.004)    | -         |     1.55 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     4037 | 2024-02-25 | ENCE Athena       | W   | 0.113      | -            | -                | -                | -         |     0.96 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     4066 | 2024-02-24 | Crescent fe       | W   | 0.107      | -            | -                | -                | -         |     1.01 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,394.28)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.769 | $7,000.00      | $5,383.52       |
| 2024-05-19 |      0.674 | $2,000.00      | $1,347.78       |
| 2024-04-16 |      0.455 | $3,500.00      | $1,591.20       |
| 2024-02-25 |      0.114 | $630.00        | $71.78          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
