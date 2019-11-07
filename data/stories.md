## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
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



## snack response positive

* snack_ask
  - utter_snack
* snack_affirm
  - utter_enjoy_snack
* polite
  - utter_goodbye


## snack response positive

* snack_ask
  - utter_snack
* snack_affirm
  - utter_enjoy_snack
* not_polite
  - utter_goodbye


## snack response negative

* snack_ask
  - utter_snack
* snack_deny
  - utter_have_good_day
* polite
  - utter_goodbye



## snack response negative

* snack_ask
  - utter_snack
* snack_deny
  - utter_have_good_day
* not_polite
  - utter_goodbye







