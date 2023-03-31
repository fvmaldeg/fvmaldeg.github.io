+++
widget = "contact_form"
title = "Contacteer mij" 

# Uncomment the following line and widget will NOT be displayed
# hidden = true

# Uncomments the following line for
# standard forms.
#
# Form handler
# action = "/contact_handler.php"
# Form submit method
# method = "GET" # Default is POST

# For Netlify form
#
netlify = true

# Add a contact via email button if your email
# is configured in the config file of your website.
useEmail = true

# Form inputs
[[inputs]]
label = "Uw naam"
# Input type
type = "text"
# minimum input length
minlength = "3"
# maxlength = "25"
name = "name"
# pattern matching
pattern = "[a-zA-Z]"
placeholder = "Naam"
# The input is required to submit the form
# required = true

[[inputs]]
label = "Uw email"
type = "email"
name = "email"
# pattern = ""
placeholder = "Email"
required = true

# Textarea works same as input but doesn't support pattern matching
[[inputs]]
label = "Uw bericht"
type = "textarea"
minlength = "10"
name = "message"
placeholder = "Uw bericht..."
required = true

+++

Interesse in een workshop, lezing of gewoon meteorieten?
Stel hier de vraag!
