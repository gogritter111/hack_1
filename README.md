# hack_1
py+maria
goal is to create a system to aide pilots to stop plane crashes and avoid tragedies\
\
Story Board

1. Pilot is flying a plane A to B, 
2. failure is recognized, pilot enters probable cause for failure
3. ATC receives message  -> create input field with possible options -> frontend
4. as system is searching through database for possible options, weather must be taken into account with realtime data -> API
5. once weather is taken into account through API database will accept new weather parameter -> logic+API+db
6. extra logic like runway length + plane size must be taken into consideration, create extra parameters(based on factual research) -> logic+db
7. once calculations are done by machine, result should be displayed with appropriate rankings -> logic+db+frontend

Questions to ask ourselves...
1. What plane are we even flying -> model name, route -> frontend+logic+db
2. for failure recognition, logic should be thorough -> what failure?, how will parameters be affected(runway length, plane size) ?->logic
3. how to integrate weather into the frontend since backend is obvious ? -> what values are we displaying wrt weather ? -> logic+API
4. how is ranking done ? what are we trying to teach our machine to do ? are we prioritizing time or safety ? -> logic+db+frontend

    
