### Roster Details<br />
Team Name: Chinggis Warriors<br />
Roster: fury5k, NEUZ, starDUST, xerolte, Zilkenberg<br />
Global Rank: [145](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [13]( ../standings_asia.md)<br />
<br />
Final Rank Value:  734.7<br />
<br />
Final Rank Value (734.7) = Starting Rank Value (731.9) + Head To Head Adjustments (2.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.308[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.334[<sup>2</sup>](#table1)

The average of these factors is 0.162<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 731.9
- 400 + ( ( 0.162 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 731.9


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
|           10 |       20 | 2024-08-03 | Steel Helmet | W   | 1.000      | 0.380        | 0.006 (0.002)    | 0.000 (0.000)    | 1 (1.000) |     7.63 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            9 |      763 | 2024-07-12 | Alter Ego    | L   | 1.000      | -            | -                | -                | -         |   -24.02 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            8 |      766 | 2024-07-12 | TYLOO        | L   | 1.000      | -            | -                | -                | -         |   -16.38 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            7 |      769 | 2024-07-12 | GR           | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.078 (0.011)    | 0 (0.000) |    11.41 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            6 |     1514 | 2024-05-31 | Aurora       | L   | 0.777      | -            | -                | -                | -         |    -0.30 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            5 |     1563 | 2024-05-30 | OG           | W   | 0.765      | 0.500        | 0.140 (0.054)    | 0.133 (0.051)    | 1 (0.765) |    19.76 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            4 |     1592 | 2024-05-28 | BLEED        | L   | 0.756      | -            | -                | -                | -         |    -0.68 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            3 |     1917 | 2024-05-16 | The MongolZ  | L   | 0.677      | -            | -                | -                | -         |    -0.03 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            2 |     2281 | 2024-05-03 | IHC          | W   | 0.585      | 0.143        | 0.000 (0.000)    | 0.024 (0.002)    | 1 (0.585) |     2.98 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |
|            1 |     2288 | 2024-05-02 | Eruption     | W   | 0.583      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.583) |     2.46 | fury5k, NEUZ, starDUST, xerolte, Zilkenberg |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
