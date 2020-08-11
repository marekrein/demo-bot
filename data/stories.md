## küsimus vpn kohta

* kysi_vpn_kohta
  - utter_kysi_vpn_kohta

## küsimus struktuur kohta

* kysi_ng_struktuuri_kohta
  - utter_kysi_ng_struktuuri_kohta

## küsimus parkimise kohta

* kysi_parkimise_kohta
  - utter_kysi_parkimise_kohta

## küsimus kuluaruande kohta

* kysi_kuluaruande_infot
  - utter_kysi_kuluaruande_infot

## greet

* greet
	- utter_greet

## küsimus põhipuhkuse kohta

* kysi_puhkuste_kohta{"puhkuse_tyyp":"põhipuhkus"}
    - slot{"puhkuse_tyyp":"põhipuhkus"}
    - utter_kysi_põhipuhkuse_infot

## goodbye

* goodbye
  - utter_goodbye

## küsimus puhkuse kohta

* kysi_puhkuste_kohta
  - utter_kysi_puhkuste_kohta

## õppepuhkuse hea lõpp

* kysi_puhkuste_kohta{"puhkuse_tyyp":"õppepuhkus"}
    - slot{"puhkuse_tyyp":"õppepuhkus"}
    - utter_kysi_õppepuhkuse_infot

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

## thanks

* thanks
	- utter_thanks

## küsimus põhipuhkuse kohta VOL 2

* kysi_puhkuste_kohta{"puhkuse_tyyp":"põhipuhkus"}
    - slot{"puhkuse_tyyp":"põhipuhkus"}
    - utter_kysi_põhipuhkuse_infot

## Kus näen haiguslehte
* kysi_haiguslehte
	- utter_kysi_haiguslehte

## Are you bot

* bot_challenge
  - utter_imabot
