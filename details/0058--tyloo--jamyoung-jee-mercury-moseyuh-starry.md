### Roster Details<br />
Team Name: TYLOO<br />
Roster: JamYoung, Jee, Mercury, Moseyuh, Starry<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [4]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1018.3<br />
<br />
Final Rank Value (1018.3) = Starting Rank Value (982.9) + Head To Head Adjustments (35.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.444[<sup>1</sup>](#table2)
- Bounty Collected: 0.285[<sup>2</sup>](#table1)
- Opponent Network: 0.059[<sup>2</sup>](#table1)
- LAN Wins: 0.347[<sup>2</sup>](#table1)

The average of these factors is 0.283<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 982.9
- 400 + ( ( 0.283 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 982.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |       15 | 2024-08-06 | Chinggis Warriors | W   | 1.000      | 0.380        | 0.013 (0.005)    | 0.187 (0.071)    | 1 (1.000) |    13.88 | JamYoung, Jee, Mercury, Moseyuh, Starry  |
|           14 |       30 | 2024-08-05 | Rare Atom         | W   | 1.000      | 0.380        | 0.009 (0.003)    | 0.465 (0.177)    | 1 (1.000) |    13.49 | JamYoung, Jee, Mercury, Moseyuh, Starry  |
|           13 |       59 | 2024-08-04 | Gaimin Gladiators | W   | 1.000      | 0.380        | 0.037 (0.014)    | 0.331 (0.126)    | 1 (1.000) |    13.79 | JamYoung, Jee, Mercury, Moseyuh, Starry  |
|           12 |      127 | 2024-08-02 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -17.65 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|           11 |      167 | 2024-08-01 | Rare Atom         | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.465 (0.066)    | 0 (0.000) |    13.06 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|           10 |      177 | 2024-08-01 | CatEvil           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.231 (0.033)    | 0 (0.000) |     4.41 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            9 |      866 | 2024-07-13 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -19.59 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            8 |      868 | 2024-07-13 | CatEvil           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.231 (0.033)    | 0 (0.000) |     3.52 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            7 |      879 | 2024-07-12 | Chinggis Warriors | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.187 (0.027)    | 0 (0.000) |    15.95 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            6 |      883 | 2024-07-12 | Alter Ego         | W   | 1.000      | 0.143        | -                | 0.077 (0.011)    | 0 (0.000) |     2.20 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            5 |     1352 | 2024-06-08 | Lynn Vision       | L   | 0.806      | -            | -                | -                | -         |   -10.16 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            4 |     1405 | 2024-06-07 | GR                | W   | 0.799      | 0.416        | 0.008 (0.003)    | 0.072 (0.024)    | 0 (0.000) |     3.85 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            3 |     1472 | 2024-06-06 | The QUBE          | W   | 0.792      | 0.416        | 0.005 (0.002)    | 0.060 (0.020)    | 0 (0.000) |     3.97 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            2 |     1529 | 2024-06-05 | Lynn Vision       | L   | 0.786      | -            | -                | -                | -         |    -9.72 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            1 |     1571 | 2024-06-04 | LYG               | W   | 0.779      | 0.416        | 0.003 (0.001)    | -                | -         |     4.29 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,813.33)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $13,755.00     | $13,755.00      |
| 2024-06-09 |      0.812 | $5,000.00      | $4,058.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
