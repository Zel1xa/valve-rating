### Roster Details<br />
Team Name: Chinggis Warriors<br />
Roster: fury5k, NEUZ, starDUST, xerolte, Zilkenberg<br />
Global Rank: [117](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [7]( ../standings_asia.md)<br />
<br />
Final Rank Value:  825.2<br />
<br />
Final Rank Value (825.2) = Starting Rank Value (804.7) + Head To Head Adjustments (20.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.327[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.448[<sup>2</sup>](#table1)

The average of these factors is 0.197<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 804.7
- 400 + ( ( 0.197 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 804.7


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
|           11 |       31 | 2024-08-05 | Lynn Vision  | W   | 1.000      | 0.380        | 0.086 (0.033)    | 0.182 (0.069)    | 1 (1.000) |    24.84 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|           10 |       95 | 2024-08-03 | Steel Helmet | W   | 1.000      | 0.380        | 0.005 (0.002)    | 0.000 (0.000)    | 1 (1.000) |     5.72 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            9 |      867 | 2024-07-12 | Alter Ego    | L   | 1.000      | -            | -                | -                | -         |   -25.86 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            8 |      871 | 2024-07-12 | TYLOO        | L   | 1.000      | -            | -                | -                | -         |   -13.37 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            7 |      873 | 2024-07-12 | GR           | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.072 (0.010)    | 0 (0.000) |     9.08 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            6 |     1652 | 2024-05-31 | Aurora       | L   | 0.758      | -            | -                | -                | -         |    -0.40 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            5 |     1701 | 2024-05-30 | OG           | W   | 0.746      | 0.500        | 0.137 (0.051)    | 0.120 (0.045)    | 1 (0.746) |    17.90 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            4 |     1730 | 2024-05-28 | BLEED        | L   | 0.738      | -            | -                | -                | -         |    -0.97 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            3 |     2057 | 2024-05-16 | The MongolZ  | L   | 0.658      | -            | -                | -                | -         |    -0.05 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            2 |     2422 | 2024-05-03 | IHC          | W   | 0.566      | 0.143        | 0.000 (0.000)    | 0.022 (0.002)    | 1 (0.566) |     2.04 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            1 |     2429 | 2024-05-02 | Eruption     | W   | 0.564      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.564) |     1.66 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
