# apollo-code-test
A code test based on Project Apollo

# Scenario
You have chosen, or been chosen, to create a prototype for Project Apollo. Apollo is a dynamic campaign app, that simulates the air war in WWII for players in of the Il-2: Great Battles flight simulator. Your task is to build a proof of concept for "Career Mode" which will assing missions to simulated pilots, based on the state of the campaign for a given day.

In this prototype, you must build a system that allows the user to upload a file, parse that file to persist campaign state, and then generate mission for new pilots. The user can create as many pilots as they wish. Pilots have a first and a last name. Each one is assigned one mission randomly when they are created. For this prototype a mission consists of an airfield, an objective type and an airplane.

Airfields, airplanes and available enemy objectives are described by the JSON file uploaded by the user.
