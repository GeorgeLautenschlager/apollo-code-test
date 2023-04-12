# apollo-code-test
A code test based on Project Apollo

# Scenario
You have chosen, or been chosen, to create a prototype for Project Apollo. Apollo is a dynamic campaign that simulates the air war in WWII for players of the Il-2: Great Battles flight simulator. Your task is to build a proof of concept for "Career Mode" which will assign missions to simulated pilots, based on the state of the campaign for a given day.

In this prototype, you must build a system that allows the user to upload a file, parse that file to persist campaign state, and then generate missions for new pilots. The user can create, view and delete as many pilots as they wish. Pilots have a first and a last name. Each one is assigned one mission randomly when they are created. For this prototype a mission consists of an airfield, an objective type and an airplane. Airfields, airplanes and available enemy objectives are described by the JSON file uploaded by the user.

# Objective Types
Close Air Support
Ground Strike
Strategic Bombing
Battlefield Air Interdiction
Fighter Sweep


For example, after uploading and processing the provided example file `campaign_state.json`, a newly created pilot might be assigned a mission as follows:

Close Air Support, P-51, Munchen Munitions depot

# Architecture
Feel free to use whatever frameworks or libraries you are comfortable with. The prototype must run in a browser. You are not expected to build an extensive UI, but some attention to usability and aesthetics is a bonus.
