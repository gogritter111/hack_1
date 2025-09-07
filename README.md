# hack_1
py+maria
goal is to create a system to aide pilots to stop plane crashes and avoid tragedies
#story board
Pilot is flying a plane A to B, 
failure is recognized, pilot enter probable cause for failure -> create input field with possible options -> frontend
as system is searching through database for possible options, weather must be taken into account with realtime data -> API
once weather is taken into account through API database will accept new weather parameter -> logic+API+db
extra logic like runway length + plane size must be taken into consideration, create extra parameters(based on factual research) -> logic+db
once calculations are done by machine, result should be displayed with appropriate rankings -> logic+db+frontend

Questions to ask ourselves...
1. What plane are we even flying -> model name, route -> frontend+logic+db
2. for failure recognition, logic should be thorough -> what failure?, how will parameters be affected(runway length, plane size) ?->logic
3. how to integrate weather into the frontend since backend is obvious ? -> what values are we displaying wrt weather ? -> logic+API
4. how is ranking done ? what are we trying to teach our machine to do ? are we prioritizing time or safety ? -> logic+db+frontend

    
