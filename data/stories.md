## health check
* health_check_start
  - health_check_form
  - form{"name": "health_check_form"}
  - form{"name": null}
  
## hello world
* hello_world
  - utter_greet
  - action_hello_world

## i am user
* i_am_user{"username":"fred"}
  - slot{"username": "fred"}
  - utter_i_am_user

## add numbers
* maths_add_numbers
  - action_maths_add_numbers
  - slot{"result": "3"}
  
## subtract numbers
* maths_subtract_numbers
  - action_maths_subtract_numbers
  - slot{"result": "3"}

## multiply numbers
* maths_multiply_numbers
  - action_maths_multiply_numbers
  - slot{"result": "3"}
  
## divide numbers
* maths_divide_numbers
  - action_maths_divide_numbers
  - slot{"result": "3"}

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
  - action_end
  
## say goodbye
* goodbye
  - utter_goodbye
  - action_end

## bot challenge
* bot_challenge
  - utter_iamabot
 

## interactive_story_1
* mood_unhappy
    - utter_cheer_up
    - utter_did_that_help
* affirm
    - utter_happy

## interactive_story_2
    - utter_greet
* mood_unhappy
    - utter_cheer_up
    - utter_did_that_help
* deny
    - utter_goodbye

## interactive_story_3
    - utter_greet
* mood_great
    - utter_happy

## interactive_story_1
* maths_divide_numbers{"number": "2"}
    - action_maths_divide_numbers
    - slot{"result": "2.5"}

## interactive_story_1
* maths_add_numbers{"number": 4}
    - action_maths_add_numbers
    - slot{"result": "8"}
* maths_add_numbers{"number": "7.2"}
    - action_maths_add_numbers
    - slot{"result": "8"}
    
    
    
