### Roster Details<br />
Team Name: FURIA Academy<br />
Roster: GYZER, Jotag3, max, mello, msr<br />
Global Rank: [209](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [55]( ../standings_americas.md)<br />
<br />
Final Rank Value:  526.3<br />
<br />
Final Rank Value (526.3) = Starting Rank Value (518.3) + Head To Head Adjustments (8.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.061<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 518.3
- 400 + ( ( 0.061 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 518.3


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
|           14 |     1653 | 2024-07-21 | Patins da Ferrari | L   | 0.874      | -            | -                | -                | -         |    -6.58 | GYZER, Jotag3, max, mello, msr           |
|           13 |     1716 | 2024-07-19 | Hawks             | W   | 0.861      | 0.371        | 0.008 (0.003)    | 0.038 (0.012)    | 0 (0.000) |    18.47 | GYZER, Jotag3, max, mello, msr           |
|           12 |     1827 | 2024-07-17 | Galorys           | L   | 0.849      | -            | -                | -                | -         |    -4.96 | Bruninho, GYZER, Jotag3, max, mello      |
|           11 |     1946 | 2024-07-15 | Bounty Hunters    | L   | 0.834      | -            | -                | -                | -         |    -2.74 | GYZER, Jotag3, max, mello, souz4h        |
|           10 |     1971 | 2024-07-14 | KRÜ               | L   | 0.828      | -            | -                | -                | -         |    -3.65 | GYZER, Jotag3, max, mello, souz4h        |
|            9 |     2051 | 2024-07-09 | MIBR Academy      | W   | 0.794      | 0.333        | 0.001 (0.000)    | 0.038 (0.010)    | 0 (0.000) |    12.40 | GYZER, Jotag3, max, mello, souz4h        |
|            8 |     2092 | 2024-07-05 | KRÜ               | L   | 0.768      | -            | -                | -                | -         |    -3.42 | GYZER, Jotag3, max, mello, souz4h        |
|            7 |     2793 | 2024-05-31 | Dusty Roots       | L   | 0.535      | -            | -                | -                | -         |    -3.19 | Bruninho, cerolzin, GYZER, Jotag3, mello |
|            6 |     2847 | 2024-05-29 | Bounty Hunters    | L   | 0.521      | -            | -                | -                | -         |    -2.50 | Bruninho, cerolzin, GYZER, Jotag3, mello |
|            5 |     2860 | 2024-05-28 | Intense           | L   | 0.516      | -            | -                | -                | -         |    -4.37 | Bruninho, cerolzin, GYZER, Jotag3, mello |
|            4 |     3161 | 2024-05-17 | ODDIK             | L   | 0.442      | -            | -                | -                | -         |    -0.67 | Bruninho, cerolzin, GYZER, Jotag3, mello |
|            3 |     3192 | 2024-05-16 | KRÜ               | W   | 0.436      | 0.303        | 0.017 (0.002)    | 0.629 (0.083)    | 0 (0.000) |    12.02 | Bruninho, cerolzin, GYZER, Jotag3, mello |
|            2 |     3302 | 2024-05-14 | Solid             | L   | 0.422      | -            | -                | -                | -         |    -1.92 | Bruninho, cerolzin, GYZER, Jotag3, mello |
|            1 |     3359 | 2024-05-12 | RED Canids        | L   | 0.408      | -            | -                | -                | -         |    -0.84 | Bruninho, cerolzin, GYZER, Jotag3, mello |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
