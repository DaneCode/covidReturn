This code creates a web page with a form that allows the user to indicate their symptoms, test result, exposure to COVID-19, and living status with regards to the virus. 
When the user submits the form by clicking the submit button, the code uses jQuery to calculate the result based on the user's inputs and displays the result on the page. 
The output is one of the following:

    "ok to return to work once symptom free"
    "Placed on 5 day quarantine & must wear a mask for 5 additional days upon return"
    "Placed off work until test results. If positive: 5 day quarantine & wear mask for 5 days after. If negative: return when symptom free"
    "ok to work pending test result. If positive: 5 day quarantine & wear mask for 5 days after. If negative: return when symptom free"
    "Placed off work until test results. If positive, follow positive test guidelines. If negative, return when symptom free"
    "ok to work, wear mask for 10 days"
    "ok to work"

This program was intentinally written within the index.html to make it a single self contained file.
