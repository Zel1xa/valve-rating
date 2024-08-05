### Roster Details<br />
Team Name: Chinggis Warriors<br />
Roster: fury5k, NEUZ, starDUST, xerolte, Zilkenberg<br />
Global Rank: [148](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [13]( ../standings_asia.md)<br />
<br />
Final Rank Value:  736.7<br />
<br />
Final Rank Value (736.7) = Starting Rank Value (730.7) + Head To Head Adjustments (6.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.307[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.333[<sup>2</sup>](#table1)

The average of these factors is 0.162<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 730.7
- 400 + ( ( 0.162 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 730.7


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
|           10 |       60 | 2024-08-03 | Steel Helmet | W   | 1.000      | 0.380        | 0.006 (0.002)    | 0.000 (0.000)    | 1 (1.000) |     7.56 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            9 |      832 | 2024-07-12 | Alter Ego    | L   | 1.000      | -            | -                | -                | -         |   -24.02 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            8 |      836 | 2024-07-12 | TYLOO        | L   | 1.000      | -            | -                | -                | -         |   -13.18 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            7 |      838 | 2024-07-12 | GR           | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.075 (0.011)    | 0 (0.000) |    11.56 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            6 |     1617 | 2024-05-31 | Aurora       | L   | 0.768      | -            | -                | -                | -         |    -0.29 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            5 |     1666 | 2024-05-30 | OG           | W   | 0.756      | 0.500        | 0.138 (0.052)    | 0.127 (0.048)    | 1 (0.756) |    19.73 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            4 |     1695 | 2024-05-28 | BLEED        | L   | 0.748      | -            | -                | -                | -         |    -0.68 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            3 |     2022 | 2024-05-16 | The MongolZ  | L   | 0.668      | -            | -                | -                | -         |    -0.03 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            2 |     2387 | 2024-05-03 | IHC          | W   | 0.576      | 0.143        | 0.000 (0.000)    | 0.023 (0.002)    | 1 (0.576) |     2.95 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            1 |     2394 | 2024-05-02 | Eruption     | W   | 0.574      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.574) |     2.44 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
