## Functions
* Passing flags into a function screams that the function is doing more than one thing 
* The less arugments the better because they are a different level of abstraction to the function and requires additional context 
* Command/mutation or query a function should either do something or answer something but not both `checkPasswordAndInitSession` should be two functions `checkPassword` and `initSession` better yet you scope these functions to a certain context `user.checkPassword` and `user.initSession`
* `functions` are the verbs `classes` are the nouns
* Think of systems as stories to be told rather than programs to be written
