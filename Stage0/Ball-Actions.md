# Ball-Actions

## Feature

Controls the movement of the ball

## Acceptance Criteria

### Scenario: Determine initial movement of the ball

  Given the game has begun

  When the 3 seconds timer is finished

  Then ball starts moving in a random direction

### Scenario: When the ball hits a border (top/bottom) or hits a bar 

  Given the game is in progress

  When the ball hit an object

  Then move the ball in the direction detrmine dby angle of collision


### Scenario: When user looses

  Given the game is in progress

  When ball touches user's side wall

  Then level-result screen is displayed

### Scenario: When computer looses

  Given the game is in progress

  When ball touches computer's side wall

  Then level-result screen is displayed