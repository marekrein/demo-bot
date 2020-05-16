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

## küsimus vpn kohta
* kysi_vpn_kohta
	- utter_kysi_vpn_kohta

## küsimus struktuur kohta
* kysi_ng_struktuuri_kohta
	- utter_kysi_ng_struktuuri_kohta

## küsimus parkimise kohta
* kysi_parkimise_kohta
	- utter_kysi_parkimise_kohta
