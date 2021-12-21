## greet + show_phones
* greet
  - utter_how_can_I_help
* buy_phone_laptop{"category":"phone"}
  - utter_ask_ram
* give_information{"ram":"8 GB RAM"}
  - utter_ask_camera
* give_information{"camera":"40 megapixel"}
  - utter_ask_battery
* give_information{"battery":"2000 mah"}
  - action_search

## greet + ask_leave_policy
* greet
  - utter_how_can_I_help
* what_is_leave_policy
  - utter_leave_policy

## greet + ask_leave_policy
* greet
  - utter_how_can_I_help
* what_is_leave_policy
  - utter_ask_ram

## greet + show_latest_news
* greet
  - utter_how_can_I_help
* latest_news_phones_laptops{"category":"phone"}
  - action_show_latest_news
