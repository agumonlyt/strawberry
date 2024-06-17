# strawberry

- i really want to try out an open sourced project, built by community. so let's give it a try. see how far we can go. 
- let's create a whole new bot. 

# plan:
- i want to make code simple. 
- let's code a pure point-based rotation properly like auto-maple. 
- minimum codes. 
- let's just use interception for now. 
- not planning to compile with nuitka? worrying about same signature problem. 
- the first thing we need is to build a new gdi_capture.dll. 
- performance is the key, speed is the key. i want the new gdi_capture to be able to capture frame at max=0.001999 second per frame. any higher than that is failure. 
- try not to open a handle to maplestory game client. anti-cheat scan for all processes. 
- my idea is i will create another tool, that can drag maplestory window to top left corner of your desktop screen, and so the new gdi_capture no need to create a handle to maplestory, instead it will screenshot from (0,0) to (800,600) instead. 
- more .. add-ons later. 

- the last step should be to rename all variables and functions so that every bot has different signature. 


# watermelon
- i will create another codebase purely for custom rotation named 'watermelon'. 


# starfruit
- i will create another codebase purely for script recording named 'starfruit'. 