# Level-Result-Screen

## Feature

Display the result of the level to the user

## Acceptance Criteria

### Scenario: User has lost against computer

  Given the game is in progress

  When the ball has hit user's side wall

  Then "Level lost" message is shown on the screen

### Scenario: When the computer lost against user

  Given the game is in progress

  When the ball has hit computer's side wall

  Then "Level cleared" message is shown on the screen