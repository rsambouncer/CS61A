# CS61A

All of this code comes from CS61A staff, none is mine. I like cheese.

# Ants Updated GUI

Download `gui.py` and `gui.html` into your ants folder, as well as `app.js` into the assets folder. Then, you need to change the following line of code in your `ants.py` file:
In Insect.reduce_armor, change `self.death_callback()` to `Insect.death_callback(self)`. 

Now, running `python3 gui.py` should bring up the working GUI in `http://localhost:8000/gui.html`. If it does, congrats! You can now play Ants vs. Some Bees. 
