### Roster Details<br />
Team Name: Chinggis Warriors<br />
Roster: fury5k, NEUZ, sergelen19k, xerolte, Zilkenberg<br />
Global Rank: [96](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [6]( ../standings_asia.md)<br />
<br />
Final Rank Value:  836.8<br />
<br />
Final Rank Value (836.8) = Starting Rank Value (886.1) + Head To Head Adjustments (-49.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.310[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.327[<sup>2</sup>](#table1)

The average of these factors is 0.251<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 886.1
- 400 + ( ( 0.251 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 886.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      248 | 2024-08-30 | ATOX         | L   | 1.000      | -            | -                | -                | -         |   -18.07 | fury5k, NEUZ, sergelen19k, xerolte, Zilkenberg |
|           14 |      291 | 2024-08-29 | GR           | L   | 1.000      | -            | -                | -                | -         |   -23.80 | fury5k, NEUZ, sergelen19k, xerolte, Zilkenberg |
|           13 |      344 | 2024-08-28 | THE          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.113 (0.016)    | 0 (0.000) |     3.98 | fury5k, NEUZ, sergelen19k, xerolte, Zilkenberg |
|           12 |     1131 | 2024-08-06 | TYLOO        | L   | 0.979      | -            | -                | -                | -         |   -12.06 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg    |
|           11 |     1157 | 2024-08-05 | Lynn Vision  | W   | 0.972      | 0.380        | 0.073 (0.027)    | 0.114 (0.042)    | 1 (0.972) |    17.28 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg    |
|           10 |     1220 | 2024-08-03 | Steel Helmet | W   | 0.959      | 0.380        | 0.003 (0.001)    | 0.038 (0.014)    | 1 (0.959) |     3.65 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg    |
|            9 |     1995 | 2024-07-12 | Alter Ego    | L   | 0.813      | -            | -                | -                | -         |   -22.11 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg    |
|            8 |     1999 | 2024-07-12 | TYLOO        | L   | 0.813      | -            | -                | -                | -         |   -11.50 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg    |
|            7 |     2001 | 2024-07-12 | GR           | W   | 0.812      | 0.143        | 0.006 (0.001)    | 0.169 (0.020)    | 0 (0.000) |     5.64 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg    |
|            6 |     2780 | 2024-05-31 | Aurora       | L   | 0.538      | -            | -                | -                | -         |    -1.08 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg    |
|            5 |     2829 | 2024-05-30 | OG           | W   | 0.526      | 0.500        | 0.118 (0.031)    | 0.352 (0.093)    | 1 (0.526) |     9.80 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg    |
|            4 |     2858 | 2024-05-28 | BLEED        | L   | 0.517      | -            | -                | -                | -         |    -2.36 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg    |
|            3 |     3185 | 2024-05-16 | The MongolZ  | L   | 0.438      | -            | -                | -                | -         |    -0.06 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg    |
|            2 |     3550 | 2024-05-03 | IHC          | W   | 0.346      | 0.143        | 0.000 (0.000)    | 0.164 (0.008)    | 1 (0.346) |     0.76 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg    |
|            1 |     3557 | 2024-05-02 | ARAVT        | W   | 0.344      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.344) |     0.67 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,038.90)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
