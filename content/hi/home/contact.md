+++
widget = "contact_form"
title = "संपर्क करें" 

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
label = "आपका नाम"
# Input type
type = "text"
# minimum input length
minlength = "3"
# maxlength = "25"
name = "name"
# pattern matching
pattern = "[a-zA-Z]"
placeholder = "नाम"
# The input is required to submit the form
# required = true

[[inputs]]
label = "आपका ई-मेल"
type = "email"
name = "email"
# pattern = ""
placeholder = "ई-मेल"
required = true

# Textarea works same as input but doesn't support pattern matching
[[inputs]]
label = "आपका संदेश (न्यूनतम 10 वर्ण)"
type = "textarea"
minlength = "10"
name = "message"
placeholder = "लिखें..."
required = true

+++

यदि आप कोई प्रतिक्रिया देना चाहते हैं, या आपके पास कोई सवाल है, तो यहाँ वर्णन कीजिए। 
