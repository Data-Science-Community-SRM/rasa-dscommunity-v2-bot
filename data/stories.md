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

## about_community_morning
* greeting_morning
- utter_greeting_morning
* bot_ask_community
- utter_bot_ask_community
* bot_tech
- utter_bot_tech
* bot_projects
- utter_bot_projects
* bot_sponsor
- utter_bot_sponsor
* bot_blogs
- utter_bot_blogs
* bot_about_club
- utter_bot_about_club
* bot_recruitments
- utter_bot_recruitments

## about_community_evening
* greeting_evening
- utter_greeting_evening
* bot_ask_community
- utter_bot_ask_community
* bot_tech
- utter_bot_tech
* bot_projects
- utter_bot_projects
* bot_sponsor
- utter_bot_sponsor
* bot_blogs
- utter_bot_blogs
* bot_about_club
- utter_bot_about_club
* bot_recruitments
- utter_bot_recruitments

## about_community_informal
* informal_greeting
- utter_informal_greeting
* bot_ask_community
- utter_bot_ask_community
* bot_tech
- utter_bot_tech
* bot_projects
- utter_bot_projects
* bot_sponsor
- utter_bot_sponsor
* bot_blogs
- utter_bot_blogs
* bot_about_club
- utter_bot_about_club
* bot_recruitments
- utter_bot_recruitments

## recruitments_perks_unhappy_path
* informal_greeting
- utter_informal_greeting
* bot_ask_community
- utter_bot_ask_community
* bot_about_club
- utter_bot_about_club
* bot_recruitments
- utter_bot_recruitments
* bot_issues
- utter_bot_issues

## recruitments_perks_happy_path
* informal_greeting
- utter_informal_greeting
* bot_ask_community
- utter_bot_ask_community
* bot_about_club
- utter_bot_about_club
* bot_recruitments
- utter_bot_recruitments
* goodbye_bot
- utter_goodbye_bot

## blogs_projects
* informal_greeting
- utter_informal_greeting
* bot_tech
- utter_bot_tech
* bot_projects
- utter_bot_projects
* bot_blogs
- utter_bot_blogs
* goodbye_bot
- utter_informal_bot

## domain_tech_projects
* informal_greeting
- utter_informal_greeting
* bot_ask_community
- utter_bot_community
* bot_tech
- utter_bot_tech
* bot_projects
- utter_bot_projects

