# Covid-19-Risk-Assessment-Application

This is a web-based application (written in Javascript) allowing patients to assess their risk in terms of their age, race/ethnicity, and medical conditions. The patient's data are retrieved from FHIR server through REST API. The app also alows patients to subscribe updates on vaccination on TextIt. Patient's data will be sent to TextIt and a new contact will be created via API. 

Files: 
1. HTML file (open on a browser)

Instruction: 
1. Log in the FHIR server (esacuser/foresaconly)
2. Enter patient's ID
3. Click 'Assess Risk'
4. A new window should pop-up showing the assessment results. 
5. A button on the bottom of the page allows user to subscribe the updates of vaccination
