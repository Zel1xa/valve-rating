### Roster Details<br />
Team Name: Chinggis Warriors<br />
Roster: fury5k, NEUZ, starDUST, xerolte, Zilkenberg<br />
Global Rank: [145](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [13]( ../standings_asia.md)<br />
<br />
Final Rank Value:  734.3<br />
<br />
Final Rank Value (734.3) = Starting Rank Value (731.1) + Head To Head Adjustments (3.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.308[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.334[<sup>2</sup>](#table1)

The average of these factors is 0.162<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 731.1
- 400 + ( ( 0.162 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 731.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |       23 | 2024-08-03 | Steel Helmet | W   | 1.000      | 0.380        | 0.006 (0.002)    | 0.000 (0.000)    | 1 (1.000) |     7.64 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            9 |      792 | 2024-07-12 | Alter Ego    | L   | 1.000      | -            | -                | -                | -         |   -24.01 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            8 |      796 | 2024-07-12 | TYLOO        | L   | 1.000      | -            | -                | -                | -         |   -16.26 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            7 |      798 | 2024-07-12 | GR           | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.076 (0.011)    | 0 (0.000) |    11.42 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            6 |     1577 | 2024-05-31 | Aurora       | L   | 0.775      | -            | -                | -                | -         |    -0.30 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            5 |     1626 | 2024-05-30 | OG           | W   | 0.763      | 0.500        | 0.140 (0.053)    | 0.129 (0.049)    | 1 (0.763) |    19.92 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            4 |     1655 | 2024-05-28 | BLEED        | L   | 0.755      | -            | -                | -                | -         |    -0.69 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            3 |     1982 | 2024-05-16 | The MongolZ  | L   | 0.675      | -            | -                | -                | -         |    -0.03 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            2 |     2347 | 2024-05-03 | IHC          | W   | 0.583      | 0.143        | 0.000 (0.000)    | 0.023 (0.002)    | 1 (0.583) |     2.98 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            1 |     2354 | 2024-05-02 | Eruption     | W   | 0.581      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.581) |     2.46 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
