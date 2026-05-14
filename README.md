<img width="1402" height="1122" alt="starseekexample" src="https://github.com/user-attachments/assets/7cac6ea0-8a51-4530-80a3-80362a4ca290" />


a terminal app to pull dynamic projections of the stars above you for night time.






StarSeek is a terminal-based night sky viewer written in Python. It uses real star data from the Hipparcos catalogue to calculate which stars are currently visible above the horizon based on your location, then renders them as an animated ASCII map that refreshes in real time. Stars are displayed with different symbols based on their brightness, giving you a rough sense of what the sky actually looks like from where you are. Built with Skyfield for astronomy calculations and NumPy for the math behind the projections.


How to install, first download the starseek python file, then make sure you have PIP installed on your selected system, then install the latest Starfield Pandas library to ensure the command works


# Installing starfield library
pip3 install starfield pandas (Either Pip3 or Pip (it depends on your system)


# Creating alias
alias starseek='python3 ~/YOUR PATH/starseek.py'

# Running command
starseek
