### Roster Details<br />
Team Name: Rhyno<br />
Roster: DDias, krazy, renatoohaxx, snapy, TMKj<br />
Global Rank: [78](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [57]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  917.7<br />
<br />
Final Rank Value (917.7) = Starting Rank Value (867.2) + Head To Head Adjustments (50.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.441[<sup>1</sup>](#table2)
- Bounty Collected: 0.321[<sup>2</sup>](#table1)
- Opponent Network: 0.108[<sup>2</sup>](#table1)
- LAN Wins: 0.086[<sup>2</sup>](#table1)

The average of these factors is 0.239<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 867.2
- 400 + ( ( 0.239 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 867.2


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
|           16 |     2287 | 2024-06-11 | Nemiga        | L   | 0.619      | -            | -                | -                | -         |    -4.05 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     2309 | 2024-06-10 | CYBERSHOKE    | W   | 0.612      | 0.500        | 0.037 (0.011)    | 0.720 (0.220)    | 0 (0.000) |     9.89 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     2340 | 2024-06-09 | Rebels        | W   | 0.607      | 0.500        | 0.028 (0.009)    | 0.677 (0.205)    | 0 (0.000) |    11.04 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     2437 | 2024-06-08 | NAVI Junior   | W   | 0.598      | 0.500        | 0.001 (0.000)    | 0.111 (0.033)    | 0 (0.000) |     4.66 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     2529 | 2024-06-06 | MOUZ NXT      | L   | 0.587      | -            | -                | -                | -         |    -5.50 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     2640 | 2024-06-04 | Endpoint      | W   | 0.573      | 0.500        | 0.064 (0.018)    | 0.742 (0.213)    | 0 (0.000) |    11.38 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     2837 | 2024-05-28 | Sampi         | L   | 0.525      | -            | -                | -                | -         |    -8.11 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     2861 | 2024-05-27 | Endpoint      | W   | 0.518      | 0.435        | 0.064 (0.014)    | 0.742 (0.167)    | 0 (0.000) |    10.58 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            8 |     2902 | 2024-05-25 | Zero Tenacity | L   | 0.504      | -            | -                | -                | -         |    -4.44 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            7 |     2969 | 2024-05-22 | MOUZ NXT      | W   | 0.485      | 0.435        | 0.111 (0.023)    | 0.845 (0.178)    | 0 (0.000) |     9.83 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            6 |     3006 | 2024-05-21 | B8            | L   | 0.480      | -            | -                | -                | -         |    -3.58 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            5 |     3112 | 2024-05-18 | LEON          | W   | 0.457      | 0.143        | 0.005 (0.000)    | 0.084 (0.005)    | 0 (0.000) |     3.29 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            4 |     3168 | 2024-05-16 | CPH Wolves    | W   | 0.446      | 0.143        | 0.003 (0.000)    | 0.524 (0.033)    | 0 (0.000) |     5.28 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            3 |     3233 | 2024-05-15 | EYEBALLERS    | W   | 0.437      | 0.143        | 0.003 (0.000)    | 0.312 (0.020)    | -         |     5.77 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            2 |     3328 | 2024-05-12 | AL QATRAO     | W   | 0.419      | 0.306        | 0.002 (0.000)    | 0.016 (0.002)    | 1 (0.419) |     2.88 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            1 |     3364 | 2024-05-11 | ALL-IN        | W   | 0.411      | -            | -                | -                | 1 (0.411) |     1.60 | DDias, krazy, renatoohaxx, snapy, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($16,606.59)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.619 | $25,000.00     | $15,478.59      |
| 2024-05-12 |      0.419 | $2,693.00      | $1,128.01       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
