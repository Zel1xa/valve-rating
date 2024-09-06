### Roster Details<br />
Team Name: Crescent fe<br />
Roster: akiyanora, amore, ayaka, Margo, meo<br />
Global Rank: [169](../../standings_global_2024_08_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_08_06.md)<br />
Regional Rank: [109]( ../../standings_europe_2024_08_06.md)<br />
<br />
Final Rank Value:  667.6<br />
<br />
Final Rank Value (667.6) = Starting Rank Value (666.4) + Head To Head Adjustments (1.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.299[<sup>1</sup>](#table2)
- Bounty Collected: 0.214[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 666.4
- 400 + ( ( 0.130 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 666.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |        3 | 2024-08-06 | ENCE Athena       | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.033 (0.005)    | 0 (0.000) |    13.62 | akiyanora, amore, ayaka, Margo, meo |
|           15 |     1331 | 2024-06-08 | NOFEAR5           | L   | 0.807      | -            | -                | -                | -         |   -12.08 | akiyanora, amore, ayaka, Margo, meo |
|           14 |     1353 | 2024-06-08 | ENCE Athena       | W   | 0.806      | 0.270        | 0.002 (0.001)    | 0.033 (0.007)    | 0 (0.000) |    11.51 | akiyanora, amore, ayaka, Margo, meo |
|           13 |     1790 | 2024-05-26 | NIP Impact        | W   | 0.720      | 0.250        | 0.005 (0.001)    | 0.219 (0.039)    | 0 (0.000) |    13.87 | akiyanora, amore, ayaka, Margo, meo |
|           12 |     2016 | 2024-05-18 | Imperial fe       | L   | 0.666      | -            | -                | -                | -         |    -1.98 | akiyanora, amore, ayaka, Margo, meo |
|           11 |     2398 | 2024-05-05 | Imperial fe       | L   | 0.579      | -            | -                | -                | -         |    -1.76 | akiyanora, amore, ayaka, Margo, meo |
|           10 |     2759 | 2024-04-19 | NAVI Javelins     | L   | 0.474      | -            | -                | -                | -         |    -3.82 | akiyanora, amore, ayaka, Margo, meo |
|            9 |     2973 | 2024-04-11 | Fearless Cheetahs | L   | 0.420      | -            | -                | -                | -         |    -5.82 | akiyanora, amore, ayaka, Margo, meo |
|            8 |     3026 | 2024-04-10 | Permitta W        | L   | 0.413      | -            | -                | -                | -         |    -9.31 | akiyanora, amore, ayaka, Margo, meo |
|            7 |     3109 | 2024-04-08 | Imperial fe       | L   | 0.399      | -            | -                | -                | -         |    -1.37 | akiyanora, amore, ayaka, Margo, meo |
|            6 |     3344 | 2024-03-28 | 1WIN Gang         | W   | 0.327      | 0.331        | 0.001 (0.000)    | 0.016 (0.002)    | 0 (0.000) |     5.04 | akiyanora, amore, ayaka, Margo, meo |
|            5 |     3496 | 2024-03-20 | Spirit fe         | L   | 0.274      | -            | -                | -                | -         |    -4.26 | akiyanora, amore, ayaka, Margo, meo |
|            4 |     3650 | 2024-03-13 | Let Her Cook      | L   | 0.227      | -            | -                | -                | -         |    -1.34 | akiyanora, amore, ayaka, Margo, meo |
|            3 |     3651 | 2024-03-13 | Let Her Cook      | L   | 0.227      | -            | -                | -                | -         |    -1.32 | akiyanora, amore, ayaka, Margo, meo |
|            2 |     4078 | 2024-02-24 | NAVI Javelins     | L   | 0.106      | -            | -                | -                | -         |    -1.00 | akiyanora, amore, ayaka, Margo, meo |
|            1 |     4209 | 2024-02-18 | dream catchers fe | W   | 0.067      | 0.143        | 0.016 (0.000)    | 0.206 (0.002)    | 0 (0.000) |     1.22 | akiyanora, amore, ayaka, Margo, meo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,438.32)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.807 | $300.00        | $242.08         |
| 2024-05-26 |      0.720 | $750.00        | $540.12         |
| 2024-05-05 |      0.579 | $250.00        | $144.83         |
| 2024-04-21 |      0.487 | $1,050.00      | $511.29         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
