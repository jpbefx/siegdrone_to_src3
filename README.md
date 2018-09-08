A project with the AR Drone 2.0 Elite, ps_drone and pydrone programs in Python

You will need to install the pip 'pygame' and have a PlayStation 4 DS controller.

Plug in battery -> Wait for all clear -> Connect to ARDrone network -> Connect PS4 Controller -> Run "python siegdrone.py"

    siegdrone.py writtten by Greg Siegfried
    Sources used were:
         ps_drone.py
         (w)+(c) J. Philipp de Graaff, www.playsheep.de, drone@playsheep.de, 2012-2015
         Project homepage: www.playsheep.de/drone and 
             https://sourceforge.net/projects/ps-drone/

         ps4constroller.py
         (w)+(c) Jacob Laney MIT 2016
         Project homepage: https://github.com/JacobLaney/py-drone

    This project tries to use the pygames as input and feedback for the user.
    The current button configuration is:
    Pad:
    Down/Up = -/+ Animation Options             Triangle = Doggy Nod
    Left/Right = -/+ Led Options       Square = Doggy Hop    Circle = Doggy Wag
                                                eXe = Takeoff/Land

    Shoulder:    L1 = LED PATTERN        R1 = ANIMATE! PATTERN

    SPECIAL:    
    Share:    Set Megneto Trim (Must be in flight!)
    Option:    Set Drone Soft Reset (Must be on ground!)
    *** PLAYSTATION BUTTON = ENDS THE RUNNING STATE TO EXIT THE PROGRAM!
                            ***    BE ON THE GROUND WHEN PRESSED!

    The axis for the PS4 controller are:
        W/Forward = Left-Stick Up    S/Backward = Left-Stick Down
        A/SideLeft = Left-Stick Left  D/SideRight = Left-Stick Right
       
        Raise Drone = Right-Stick Up    Lower Done = Right-Stick Down
        Turn Left = Right-Stick Left    Turn Right = Right-Stick Right
#
###
#####
 END
