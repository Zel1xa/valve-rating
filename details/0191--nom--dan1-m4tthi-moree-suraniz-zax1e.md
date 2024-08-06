### Roster Details<br />
Team Name: NOM<br />
Roster: dan1, m4tthi, MOREE, suraniZ, Zax1e<br />
Global Rank: [191](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [21]( ../standings_asia.md)<br />
<br />
Final Rank Value:  593.7<br />
<br />
Final Rank Value (593.7) = Starting Rank Value (543.0) + Head To Head Adjustments (50.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.258[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.070<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 543.0
- 400 + ( ( 0.070 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 543.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      173 | 2024-08-01 | GUN5      | L   | 1.000      | -            | -                | -                | -         |    -5.38 | dan1, m4tthi, MOREE, suraniZ, Zax1e  |
|            9 |      291 | 2024-07-29 | 1WIN      | L   | 1.000      | -            | -                | -                | -         |    -2.81 | dan1, m4tthi, MOREE, suraniZ, Zax1e  |
|            8 |      333 | 2024-07-28 | GUN5      | W   | 1.000      | 0.143        | 0.072 (0.010)    | 0.550 (0.079)    | 0 (0.000) |    26.18 | dan1, m4tthi, MOREE, suraniZ, Zax1e  |
|            7 |     2007 | 2024-05-18 | GUN5      | L   | 0.667      | -            | -                | -                | -         |    -2.36 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            6 |     2041 | 2024-05-17 | Rare Atom | W   | 0.661      | 0.143        | 0.009 (0.001)    | 0.465 (0.044)    | 0 (0.000) |    17.45 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            5 |     2203 | 2024-05-14 | Heimo     | W   | 0.638      | 0.143        | 0.006 (0.001)    | 0.103 (0.009)    | 0 (0.000) |    13.85 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            4 |     2224 | 2024-05-13 | Rare Atom | L   | 0.632      | -            | -                | -                | -         |    -2.69 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            3 |     2761 | 2024-04-19 | JANO      | L   | 0.473      | -            | -                | -                | -         |    -4.87 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            2 |     2813 | 2024-04-18 | RUBY      | L   | 0.466      | -            | -                | -                | -         |    -1.55 | dan1, hotd0g , m4tthi, meztal, MOREE |
|            1 |     2852 | 2024-04-17 | Sampi     | W   | 0.459      | 0.143        | 0.027 (0.002)    | 1.000 (0.066)    | 0 (0.000) |    12.87 | dan1, hotd0g , m4tthi, meztal, MOREE |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
