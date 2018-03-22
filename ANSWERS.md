# Q0: Why is this error being thrown?
The error was thrown because the pokemon model was not defined 
# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *
The random pokemons are appearing because of the seed file, which produces seeds that are used by the random function. The
common factor between the pokemons are that they do not have trainers assigned to them yet.
# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
This line creates a button that creates a patch that calls the Capture method in the Pokemon controller, while inputting the pokemons's
id as a parameter 
# Question 3: What would you name your own Pokemon?
Kunal
# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?
We passed in the Trainer controller, and inputted the pokemon's trainer's id as the parameter 
# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.
Serves to catch the error thrown and outputs an Error page
# Give us feedback on the project and decal below!

# Extra credit: Link your Heroku deployed app
