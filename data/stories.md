## happy path
* greet
  - find_facility_types
* inform{"facility_type":"xubh-q36u"}
  - facility_form
  - form{"name":"facility_form"}
  - form{"name":null}
* inform{"facility_id":4245}
  - find_healthcare_address
  - utter_address
* thanks
  - utter_goodbye 

## happy_multi_path_location
* greet
  - find_facility_types
* inform{"facility_type": "xubh-q36u"}
  - facility_form
  - form{"name":"facility_form"}
  - form{"name":null}
* inform{"facility_id": "747604"}
  - find_healthcare_address
  - utter_address 
* search_provider{"facility_type": "xubh-q36u"}
  - facility_form
  - form{"name":"facility_form"}
  - form{"name":null}
* inform{"facility_id": 4245}
  - find_healthcare_address
  - utter_address

## happy_path2
* search_provider{"location": "Austin", "facility_type": "xubh-q36u"}
  - facility_form
  - form{"name":"facility_form"}
  - form{"name":null}
* inform{"facility_id": "450871"}
  - find_healthcare_address
  - utter_address
* thanks
  - utter_goodbye

## sad path 1
* affirm
  - utter_happy

## sad path 2
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot