Here are the versions of various packages:

Flask==1.0.2
Flask-Cors==3.0.4
Flask-Mail==0.9.1
future==0.16.0
rasa-core-sdk==0.12.1
rasa-nlu==0.12.3
tensorboard==1.8.0
tensorflow==1.8.0
zomatopy==1.0.10

To run the bot:

Run nlu_model.py followed by dialogue_management.py and then start typing your questions.
When prompted, please provide your email ID and the search results will be emailed to you.

Please note:

1) While entering location, please start with "in". Examples - "In Bangalore", "Mexican food in Mumbai"
2) For selecting cuisine, please start with "I'll prefer". Example - "I'll prefer Chinese"
3) Please select only one of the price ranges - < 300, between 300 and 700 or > 700. Fractions,decimal numbers may not yield correct results. Numbers outside these
   3 ranges are considered invalid input by the bot.

