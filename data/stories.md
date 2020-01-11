## happy path
* greet
  - utter_greet
  - utter_howareyou
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
  - utter_howareyou
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
  - utter_howareyou
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## strange user
* affirm
  - utter_happy
* affirm
  - utter_unclear

## fallback
- utter_unclear