# Bar-Actions

## Feature

Allows the user to control their bar

## Acceptance Criteria

### Scenario: When the game has begun, bar actions are enabled

  Given the game has begun

  When clicks up arrow/down arrow

  Then move the bar up/down by 5% of screen size based on user input.

### Scenario: When the user drags down the bar when the bar is already at the bottom of the screen

  Given the game is in progress and user bar is at the bottom of the screen

  When user drags down the bar

  Then do nothing


### Scenario: When the user drags up the bar when the bar is already at the top of the screen

  Given the game is in progress and user bar is at the top of the screen

  When user drags up the bar

  Then do nothing

### Scenario: When the user drags the bar in a random direction other than up/down

  Given the game is in progress

  When user drags the bar sideways

  Then do nothing