# Palette Picker Submission Form

[Project Spec](http://frontend.turing.io/projects/palette-picker.html)

# Basics

#### Link to the GitHub Repository for the Project
[palette-picker](https://github.com/AdamMescher/palette-picker)

#### Link to the Deployed Application
[heroku](https://palette-picker-adam-mescher.herokuapp.com/)

#### Link to your annotated server file
[annotated server file](https://github.com/AdamMescher/palette-picker/blob/am-commented-server-file/server.js)

## Completion

#### Were you able to complete the base functionality?

Yes, I was able to complete the base functionality. 

If not, explain what is missing and why.

#### Which extensions, if any, did you complete?

I did not complete any extensions. 

# Code Quality

#### Link to a specific block of your code on GitHub that you are proud of
[happy code](https://github.com/AdamMescher/palette-picker/blob/master/server.js#L99-L111)

* Why were you proud of this piece of code?

Does not allow a user to post a palette if the name of that palette already exists. The query is more efficient because it uses `.first()` to find the first instance rather than checking all palettes before ending.

#### Link to a specific block of your code on GitHub that you feel not great about
[sad code](https://github.com/AdamMescher/palette-picker/blob/master/public/js/scripts.js#L28-L47)

* Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

Despite the server not accepting the HTTP POST request if the palette title already exists within the database, the client side still posts the card because the promise resolves. 

#### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

[test suite]()

#### Link to Design Inspiration

* Show us what you used as design inspiration (another color picker site, a dribbble UI element, a user flow, etc.) and explain what you stole from it

- [Inspiration for palette card design](https://dribbble.com/shots/3340684-Color-Palette-Component)
- [Inspiration for color aperture design](https://dribbble.com/shots/891640-Colour-Palettes)

#### Please feel free to ask any other questions or make any other statements below!

Anything else you wanna say!

I found creating the UI and animations to be a very fun exercise. I'm really happy with how the aperture and the arrow button spins. 

-----


# Instructor Feedback (Instructor Name)

## Specification Adherence

**x points**: (50 possible points)

## User Interface

**x points**: (20 possible points)

## Testing

**x points**: (20 possible points)

## Commented Server File

**x points**: (10 possible points)

## JavaScript Style

**x points**: (30 possible points)

## Workflow

**x points**: (20 possible points)


### To get a 3 on this project, you need to score 110 points or higher
### To get a 4 on this project, you need to score 130 points or higher

# Final Score: x / 150

