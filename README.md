# Electronic Voting Machine (EVM) Project

## Microprocessors & Interfacing (CS F241)

### Problem Statement

Design a microprocessor Voting Machine which has provision for 8 candidates. It should keep the count of total votes polled and the count of votes polled for each candidate. Before being put in use, it should check if all memory locations allotted to candidates, and the total count are empty. If not, it should clear these as well as the display. There are two keypads, one for the polling officials and one for the voter. The Polling Officers Keypad also comes with a 16 character LCD Display. To put the voter keypad in use, it needs to be enabled by 8 polling agents and the Presiding officer. If anyone is missing it should not be enabled. This enabling is done using the polling officers’ keypad. The polling officer’s keypad has keys 0-9, backspace, enter, Poll count, Lock, Unlock, DisplayCount. Each polling agent and Presiding officer have a unique 5-digit numeric code. The system when turned on displays officer 1 on LCD. The polling officer then enters his numeric code. If correct then the display is updated to officer 2 and so on and finally the Presiding officer enters his code. Each person is allowed 2 retries if there is a failure the voting is blocked.

The name of the candidate followed by a button followed by LED. Voter will press the button against the candidate's name — the LED will glow for 2 seconds. After 10 hours (7 a.m. to 5 p.m.) it should stop taking input from voters. There has to be a provision that the Presiding officer by pressing the Lock key followed by a 5-digit code can lock voting in between and then can restart it by pressing the Unlock key followed by a separate 5-digit code. For retrieving the count of each candidate the Presiding Officer presses the Poll Count key followed by a 5-digit code. The Presiding officer then enters the Candidates Number followed by Display Count Key — The count for the candidate is displayed. This is done for all candidates.

## Files Description

[Report.pdf](https://github.com/Brox7/Electronic_voting_Machine-EVM-/blob/main/Report.pdf) - Contains the project Report which highlights the project specification,justifications,assumptions,memory addressing and flowcharts explaining the flow of the process.

[Chart.pdf](https://github.com/Brox7/Electronic_voting_Machine-EVM-/blob/main/Chart.pdf) - Contains how the actual EVM design will look like with all the microprocessors and interfaces.
