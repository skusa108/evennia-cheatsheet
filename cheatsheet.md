## Creating and Building
### Creating an Object
- Create object with `create box` (replace box with the object you want)
  - Name object with `name box = very large box;box;wooden box`. The box will be recognized by any of the semicolon-seperated list.
  - Drop object with `drop box`
  - Describe object with `describe box = This is a large and very heavy box.`
- Set object attributes
  - Lock the object so players can't pick it up: `lock box = get:false()`. This blocks the `get` command.
    - Give a special message when someone tries to pick up the object: `set box/get_err_msg = It's way too heavy for you to lift.`

### Create a new room/location
- Dig a route to a new room: `dig myroom = door to myroom;mydoor,door to outside;out
  - This creates:
    -  a new room (myroom)
    -  a corresponding exit from your current location (door to myroom with alias mydoor)
    -  an exit from the new location back to your current location (door to outside with alias out)
- Create an new exit with `open mydoor;door = myhouse`
  - This creates an exit (mydoor, with alias door) that connects to the location myhouse.
