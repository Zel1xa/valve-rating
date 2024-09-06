### Roster Details<br />
Team Name: NOM<br />
Roster: dan1, m4tthi, MOREE, shushan, Zax1e<br />
Global Rank: [202](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Asia]( ../../standings_asia_2024_09_06.md)<br />
Regional Rank: [25]( ../../standings_asia_2024_09_06.md)<br />
<br />
Final Rank Value:  573.3<br />
<br />
Final Rank Value (573.3) = Starting Rank Value (542.4) + Head To Head Adjustments (30.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.269[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.073<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 542.4
- 400 + ( ( 0.073 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 542.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      203 | 2024-08-30 | DRILLAS     | L   | 1.000      | -            | -                | -                | -         |   -17.39 | dan1, m4tthi, MOREE, shushan, Zax1e  |
|           14 |      234 | 2024-08-29 | Onyx Ravens | L   | 1.000      | -            | -                | -                | -         |   -21.73 | dan1, m4tthi, MOREE, shushan, Zax1e  |
|           13 |      285 | 2024-08-28 | Qiang       | W   | 1.000      | 0.143        | 0.029 (0.004)    | 0.154 (0.022)    | 0 (0.000) |    16.48 | dan1, m4tthi, MOREE, shushan, Zax1e  |
|           12 |      293 | 2024-08-28 | Al-Ittihad  | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.047 (0.007)    | 0 (0.000) |    15.75 | dan1, m4tthi, MOREE, shushan, Zax1e  |
|           11 |     1255 | 2024-08-01 | GUN5        | L   | 0.957      | -            | -                | -                | -         |    -4.35 | dan1, m4tthi, MOREE, suraniZ, Zax1e  |
|           10 |     1373 | 2024-07-29 | 1WIN        | L   | 0.938      | -            | -                | -                | -         |    -3.18 | dan1, m4tthi, MOREE, suraniZ, Zax1e  |
|            9 |     1415 | 2024-07-28 | GUN5        | W   | 0.931      | 0.143        | 0.091 (0.012)    | 0.908 (0.121)    | 0 (0.000) |    25.23 | dan1, m4tthi, MOREE, suraniZ, Zax1e  |
|            8 |     3092 | 2024-05-18 | GUN5        | L   | 0.460      | -            | -                | -                | -         |    -1.23 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            7 |     3126 | 2024-05-17 | Rare Atom   | W   | 0.453      | 0.143        | 0.025 (0.002)    | 0.464 (0.030)    | 0 (0.000) |    11.94 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            6 |     3288 | 2024-05-14 | Heimo       | W   | 0.431      | 0.143        | 0.004 (0.000)    | 0.075 (0.005)    | 0 (0.000) |     8.87 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            5 |     3309 | 2024-05-13 | Rare Atom   | L   | 0.424      | -            | -                | -                | -         |    -1.96 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            4 |     3846 | 2024-04-19 | JANO        | L   | 0.266      | -            | -                | -                | -         |    -3.03 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            3 |     3898 | 2024-04-18 | RUBY        | L   | 0.259      | -            | -                | -                | -         |    -1.07 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            2 |     3937 | 2024-04-17 | Sampi       | W   | 0.252      | 0.143        | 0.033 (0.001)    | 1.000 (0.036)    | 0 (0.000) |     7.06 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            1 |     4290 | 2024-04-04 | KOI         | L   | 0.166      | -            | -                | -                | -         |    -0.46 | dan1, meztal, MOREE, shushan, tN1R   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
