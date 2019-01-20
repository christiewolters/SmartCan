# SmartCan
H.A.R.D. Hack submission

# Inspiration
Look outside at UC San Diego. There are smart trashcans everywhere. These are incredibly helpful to people as they can tell if a trash can is full or not before opening the can and getting a strong whiff of someone's tuna leftovers for no reason. Similarly, janitors love these trashcans as they can quickly tell which trash cans need to be emptied. However, these trash cans are expensive. Our goal was to provide a low cost solution to turn any trash can into a smart trash can to save the world from unnecessary bad smells.

# What it does
Our device monitors how full a trash can is and indicates when the trash needs to be changed.

# How we built it
We used an ultrasonic range finder to detect how full the trash can is, processed the information on an Arduino Nano, and displayed it on an LCD display using an I2C LCD library.

# Challenges we ran into
Understanding how to use the LCD library took quite a bit of time and we needed to create additional processing to provide useful information.

# Accomplishments that we're proud of
We are proud that we created a finished product and learned a bunch! We are particularly proud of getting the ultrasonic range finder to work.

# What we learned
We learned a lot about how to use an Arduino, sensors, and libraries.

#What's next for Smart Can
Turning it into an GPS device! Our goal for Smart Can is to create a network of smart trashcans that can all post their location when they're full. We can then process this information to create the shortest route for janitors to change public trashcans.

# Built With
arduino
