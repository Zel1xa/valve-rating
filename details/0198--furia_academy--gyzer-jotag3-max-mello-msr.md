### Roster Details<br />
Team Name: FURIA Academy<br />
Roster: GYZER, Jotag3, max, mello, msr<br />
Global Rank: [198](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [54]( ../standings_americas.md)<br />
<br />
Final Rank Value:  529.2<br />
<br />
Final Rank Value (529.2) = Starting Rank Value (523.6) + Head To Head Adjustments (5.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.060<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 523.6
- 400 + ( ( 0.060 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 523.6


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
|           14 |      521 | 2024-07-21 | Patins da Ferrari | L   | 1.000      | -            | -                | -                | -         |    -5.96 | GYZER, Jotag3, max, mello, msr           |
|           13 |      584 | 2024-07-19 | Hawks             | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.029 (0.011)    | 0 (0.000) |    15.41 | GYZER, Jotag3, max, mello, msr           |
|           12 |      695 | 2024-07-17 | Galorys           | L   | 1.000      | -            | -                | -                | -         |    -5.02 | Bruninho, GYZER, Jotag3, max, mello      |
|           11 |      812 | 2024-07-15 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |    -2.39 | GYZER, Jotag3, max, mello, souz4h        |
|           10 |      836 | 2024-07-14 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |    -3.99 | GYZER, Jotag3, max, mello, souz4h        |
|            9 |      916 | 2024-07-09 | MIBR Academy      | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    10.11 | GYZER, Jotag3, max, mello, souz4h        |
|            8 |      957 | 2024-07-05 | KRÜ               | L   | 0.989      | -            | -                | -                | -         |    -4.03 | GYZER, Jotag3, max, mello, souz4h        |
|            7 |     1658 | 2024-05-31 | Dusty Roots       | L   | 0.755      | -            | -                | -                | -         |    -3.67 | Bruninho, cerolzin, GYZER, Jotag3, mello |
|            6 |     1712 | 2024-05-29 | Bounty Hunters    | L   | 0.742      | -            | -                | -                | -         |    -2.80 | Bruninho, cerolzin, GYZER, Jotag3, mello |
|            5 |     1725 | 2024-05-28 | Intense           | L   | 0.737      | -            | -                | -                | -         |    -5.56 | Bruninho, cerolzin, GYZER, Jotag3, mello |
|            4 |     2026 | 2024-05-17 | ODDIK             | L   | 0.663      | -            | -                | -                | -         |    -1.83 | Bruninho, cerolzin, GYZER, Jotag3, mello |
|            3 |     2057 | 2024-05-16 | KRÜ               | W   | 0.657      | 0.303        | 0.023 (0.005)    | 0.489 (0.097)    | 0 (0.000) |    18.40 | Bruninho, cerolzin, GYZER, Jotag3, mello |
|            2 |     2167 | 2024-05-14 | Solid             | L   | 0.643      | -            | -                | -                | -         |    -2.36 | Bruninho, cerolzin, GYZER, Jotag3, mello |
|            1 |     2224 | 2024-05-12 | RED Canids        | L   | 0.629      | -            | -                | -                | -         |    -0.76 | Bruninho, cerolzin, GYZER, Jotag3, mello |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
