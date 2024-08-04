### Roster Details<br />
Team Name: Chinggis Warriors<br />
Roster: fury5k, NEUZ, starDUST, xerolte, Zilkenberg<br />
Global Rank: [145](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [13]( ../standings_asia.md)<br />
<br />
Final Rank Value:  737.0<br />
<br />
Final Rank Value (737.0) = Starting Rank Value (730.9) + Head To Head Adjustments (6.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.308[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.334[<sup>2</sup>](#table1)

The average of these factors is 0.162<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 730.9
- 400 + ( ( 0.162 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 730.9


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
|           10 |       34 | 2024-08-03 | Steel Helmet | W   | 1.000      | 0.380        | 0.006 (0.002)    | 0.000 (0.000)    | 1 (1.000) |     7.55 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            9 |      804 | 2024-07-12 | Alter Ego    | L   | 1.000      | -            | -                | -                | -         |   -24.03 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            8 |      808 | 2024-07-12 | TYLOO        | L   | 1.000      | -            | -                | -                | -         |   -13.20 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            7 |      810 | 2024-07-12 | GR           | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.076 (0.011)    | 0 (0.000) |    11.55 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            6 |     1589 | 2024-05-31 | Aurora       | L   | 0.771      | -            | -                | -                | -         |    -0.29 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            5 |     1638 | 2024-05-30 | OG           | W   | 0.760      | 0.500        | 0.139 (0.053)    | 0.128 (0.049)    | 1 (0.760) |    19.82 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            4 |     1667 | 2024-05-28 | BLEED        | L   | 0.751      | -            | -                | -                | -         |    -0.69 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            3 |     1994 | 2024-05-16 | The MongolZ  | L   | 0.672      | -            | -                | -                | -         |    -0.03 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            2 |     2359 | 2024-05-03 | IHC          | W   | 0.580      | 0.143        | 0.000 (0.000)    | 0.023 (0.002)    | 1 (0.580) |     2.96 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            1 |     2366 | 2024-05-02 | Eruption     | W   | 0.578      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.578) |     2.45 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
