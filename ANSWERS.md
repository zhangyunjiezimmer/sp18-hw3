## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
  The value for the text field of course name is empty by default, which is set to nil is nothing is inputed. 

2. Go to `localhost:3000/teachers` in your browser; why does this not work?
  No route matches [GET] "/teachers"


3. What type of request did your browser just perform?
  GET

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
  http://localhost:3000/teachers


5. Why does `localhost:3000/teachers` work now?
  Because we have a source to provide the information for this GET request.
