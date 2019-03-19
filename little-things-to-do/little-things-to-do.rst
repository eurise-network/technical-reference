Little things to do to improve the quality of your software
===========================================================

The following list proposes small habit changes you/your team can easily implement into your day-to-day work.
Sticking to just one of these suggestions will increase your software's quality at once without being too time-consuming.
Approximate time costs are stated in brackets after each suggestion.

Please note that this list is far from being complete and it is ever developing since technologies change a lot.
We're looking forward to your PR to extend this list or discuss its recommendations.


#. Functions and variables

    - Give your functions and variables a descriptive name, e.g. "currentYear" instead of "y". [0.5min]
    - One function should be responsible for doing one thing. If it does more than this, split it. [max. 10min]
    - Clean as you go: In case you notice something worth changing and it takes less than 2 minutes to fix it, do it at once. [max. 2 min]


#. Error handling

    - Write custom error codes with a descriptive error messages for your modules. [ca. 3min per error code]


#. Documentation

    - Dedicate on 1h per week to writing/updating your documentation. [1h]
    - Organize a weekly doc sprint (approx. 1h) with your colleagues. [1h]


#. Usability

    - Engage in hallway usability testing: Once a week let a colleague test some part of your User Interface for 5 minutes. (You'll get the best results if s/he doesn't know what you are working on.) [7min + Xmin for solving the problems you have found]
    - When choosing a color scheme for a GUI, turn your screen to gray scale and check if the contrast is sufficient. [max. 5min]
    - Use relative font sizes in CSS instead of absolute ones. [0.5min]


#. Making developing in teams less painful

    - Commit early. Commit often.
    - Think about adopting a branching model like git flow.
