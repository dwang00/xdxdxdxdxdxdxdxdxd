# Final by David Wang pd 10
Features  
light  
  -Add a light to the symbol table  
  -When calculating diffuse and specular: loop through all the lights  
  -mdl command: light name x y z r g b, creates light named name at point (x,y,z) using color (r,g,b)  
mesh  
  -Use an external .obj file for polygons  
  -mdl command: mesh :file, creates image using .obj file with name file  
set  
  -Assign a value to a knob  
  -mdl command: set knobname value, gives a value to knobname within symbol table  
saveknobs
  -Save current knob values to a list  
  -mdl command: save_knobs list, saves value of knob into a list with name list  
tween  
  -Produce an animation by going between two knob lists  
  -mdl command: tween start_frame end_frame knoblist0 knoblist1, generates frames from start_frame to end_frame with knoblist0 as start and knoblist1 as end  
save_coordinate_system  
  -Save a copy of the top of the stack to the symbol table  
  -mdl command: save_coordinate_system name, saves to symbol table with the name as name
