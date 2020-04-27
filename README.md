# Creating an Office Scheduler with Amazon Lex and Twilio

1. Navigate to the Lex console
![Twilio dashboard](images/lex_console.png)<br>

1. Hit Create to create a new Lex bot
![Twilio dashboard](images/lex_create.png)<br>

1. You will then want to create a custom Lex bot with the following settings.
![Twilio dashboard](images/bot_settings.png)<br>

1. Click "Create Intent", this will give your bot a motive.
![Twilio dashboard](images/create_intent.png)<br>

1. Give your intent a name.
![Twilio dashboard](images/intent_name.png)<br>

1. Input some phrases that will trigger this intent, eg.
![Twilio dashboard](images/sample_utterances.png)<br>



1. Note that "time" and "date" slots are part of amazons default slot types. These are the only 2 slot types we are using today.
![Twilio dashboard](images/slots.png)<br>

1. You can now create your slots. Check the "required" check box for each slot. Use the following diagram as a guide.
![Twilio dashboard](images/all_slots.png)<br>
The "time" slot was created with the slot type AMAZON.TIME, same with "date" slot. We will look at creating custom slot types in another session such as the other 2 you can see "doctor" and "mobile_number"

1. Put in a "one shot" utterance. This will enable users who are familiar with your bot to fill all "slots" in one utterance. You will see the slots, or minimum amount of info to fill the intent are "date" and "time".
![Twilio dashboard](images/one_shot2.png)<br>

1. At this stage we can test the bots interactions. Hit "Build" and see if there are any errors that need correcting. <br>
If the build is successful, test the conversation of your bot.
![Twilio dashboard](images/test_bot.png)<br>

1. You can now create a confirm prompt, which confirms with the user the details of the appointment are right. <br>
![Twilio dashboard](images/confirm_prompt.png)<br>

1. Add a fulfillment prompt to confirm the users booking has been made. <br>
![Twilio dashboard](images/fullfulment.png)<br>

hit Save Intent, re-Build your chat bot and re-test its conversation functionality as before. <br>
![Twilio dashboard](images/save_intent.png)<br>

You are Done!
