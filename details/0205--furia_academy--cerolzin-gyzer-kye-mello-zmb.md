### Roster Details<br />
Team Name: FURIA Academy<br />
Roster: cerolzin, GYZER, kye, mello, zmb<br />
Global Rank: [205](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [58]( ../standings_americas.md)<br />
<br />
Final Rank Value:  492.5<br />
<br />
Final Rank Value (492.5) = Starting Rank Value (490.5) + Head To Head Adjustments (2.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.176[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.044<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 490.5
- 400 + ( ( 0.044 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 490.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     2828 | 2024-04-11 | Case        | L   | 0.439      | -            | -                | -                | -         |    -1.25 | cerolzin, GYZER, kye, mello, zmb      |
|            9 |     2983 | 2024-04-07 | Imperial    | L   | 0.413      | -            | -                | -                | -         |    -0.18 | Bruninho, cerolzin, GYZER, kye, mello |
|            8 |     3460 | 2024-03-14 | Case        | L   | 0.254      | -            | -                | -                | -         |    -0.66 | Bruninho, cerolzin, GYZER, kye, mello |
|            7 |     3533 | 2024-03-11 | BESTIA      | L   | 0.235      | -            | -                | -                | -         |    -0.40 | Bruninho, cerolzin, GYZER, kye, mello |
|            6 |     3558 | 2024-03-10 | Case        | L   | 0.228      | -            | -                | -                | -         |    -0.56 | Bruninho, cerolzin, GYZER, kye, mello |
|            5 |     3562 | 2024-03-10 | Flamengo    | W   | 0.227      | 0.435        | 0.000 (0.000)    | 0.016 (0.002)    | 0 (0.000) |     3.60 | Bruninho, cerolzin, GYZER, kye, mello |
|            4 |     3604 | 2024-03-08 | BESTIA      | L   | 0.215      | -            | -                | -                | -         |    -0.35 | Bruninho, cerolzin, GYZER, kye, mello |
|            3 |     4045 | 2024-02-18 | BESTIA      | L   | 0.087      | -            | -                | -                | -         |    -0.14 | Bruninho, cerolzin, GYZER, kye, mello |
|            2 |     4096 | 2024-02-16 | Dusty Roots | W   | 0.073      | 0.435        | 0.006 (0.000)    | 0.299 (0.010)    | 0 (0.000) |     2.03 | Bruninho, cerolzin, GYZER, kye, mello |
|            1 |     4208 | 2024-02-12 | BESTIA      | L   | 0.048      | -            | -                | -                | -         |    -0.08 | Bruninho, cerolzin, GYZER, kye, mello |

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
