### Roster Details<br />
Team Name: Rhyno<br />
Roster: DDias, krazy, renatoohaxx, snapy, TMKj<br />
Global Rank: [80](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [59]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  916.9<br />
<br />
Final Rank Value (916.9) = Starting Rank Value (866.6) + Head To Head Adjustments (50.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.441[<sup>1</sup>](#table2)
- Bounty Collected: 0.321[<sup>2</sup>](#table1)
- Opponent Network: 0.107[<sup>2</sup>](#table1)
- LAN Wins: 0.086[<sup>2</sup>](#table1)

The average of these factors is 0.239<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 866.6
- 400 + ( ( 0.239 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 866.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |     2292 | 2024-06-11 | Nemiga        | L   | 0.615      | -            | -                | -                | -         |    -4.01 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     2314 | 2024-06-10 | CYBERSHOKE    | W   | 0.608      | 0.500        | 0.037 (0.011)    | 0.722 (0.220)    | 0 (0.000) |     9.87 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     2345 | 2024-06-09 | Rebels        | W   | 0.603      | 0.500        | 0.028 (0.009)    | 0.677 (0.204)    | 0 (0.000) |    10.96 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     2442 | 2024-06-08 | NAVI Junior   | W   | 0.594      | 0.500        | 0.001 (0.000)    | 0.110 (0.033)    | 0 (0.000) |     4.63 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     2534 | 2024-06-06 | MOUZ NXT      | L   | 0.583      | -            | -                | -                | -         |    -5.47 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     2645 | 2024-06-04 | Endpoint      | W   | 0.569      | 0.500        | 0.064 (0.018)    | 0.744 (0.212)    | 0 (0.000) |    11.32 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     2842 | 2024-05-28 | Sampi         | L   | 0.521      | -            | -                | -                | -         |    -8.03 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     2866 | 2024-05-27 | Endpoint      | W   | 0.514      | 0.435        | 0.064 (0.014)    | 0.744 (0.166)    | 0 (0.000) |    10.52 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            8 |     2907 | 2024-05-25 | Zero Tenacity | L   | 0.500      | -            | -                | -                | -         |    -4.40 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            7 |     2974 | 2024-05-22 | MOUZ NXT      | W   | 0.481      | 0.435        | 0.111 (0.023)    | 0.844 (0.176)    | 0 (0.000) |     9.76 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            6 |     3011 | 2024-05-21 | B8            | L   | 0.476      | -            | -                | -                | -         |    -3.54 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            5 |     3117 | 2024-05-18 | LEON          | W   | 0.453      | 0.143        | 0.005 (0.000)    | 0.084 (0.005)    | 0 (0.000) |     3.27 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            4 |     3173 | 2024-05-16 | CPH Wolves    | W   | 0.442      | 0.143        | 0.003 (0.000)    | 0.525 (0.033)    | 0 (0.000) |     5.25 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            3 |     3238 | 2024-05-15 | EYEBALLERS    | W   | 0.433      | 0.143        | 0.003 (0.000)    | 0.311 (0.019)    | -         |     5.72 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            2 |     3333 | 2024-05-12 | AL QATRAO     | W   | 0.415      | 0.306        | 0.002 (0.000)    | 0.016 (0.002)    | 1 (0.415) |     2.85 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            1 |     3369 | 2024-05-11 | ALL-IN        | W   | 0.407      | -            | -                | -                | 1 (0.407) |     1.59 | DDias, krazy, renatoohaxx, snapy, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($16,495.69)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.615 | $25,000.00     | $15,378.47      |
| 2024-05-12 |      0.415 | $2,693.00      | $1,117.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
