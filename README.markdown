Samples of this code, particularly the annotated files below were completed as part of a Rails mentoring project. I assisted another developer with a complex nested form involving several models and a jQuery/Helper solution to complete the project.

This code demonstrates a strong understanding of the internals of ActiveRecord models and associations, as well as proper use of the View to manage multiple dynamically generated objects.

app/views/contracts/edit.html.haml
app/views/contracts/_codeline_fields/html.haml (Note that this file includes the key line for dynamically building the code object and associated attributes)
app/views/contracts/_code_fields.html.haml
app/controllers/contracts_controller.rb
app/models/codeline.rb
app/assets/javascripts/contracts.js.coffee
