## Creating and Building
### Creating an Object
- Create object with `create box` (replace box with the object you want)
  - Name object with `name box = very large box;box;wooden box`. The box will be recognized by any of the semicolon-seperated list.
  - Drop object with `drop box`
  - Describe object with `describe box = This is a large and very heavy box.`
- Set object attributes
  - Lock the object so players can't pick it up: `lock box = get:false()`. This blocks the `get` command.
    - Give a special message when someone tries to pick up the object: `set box/get_err_msg = It's way too heavy for you to lift.`
