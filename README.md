# nosql-challenge

Used the Xpert Learning Asistant to:
    - Confirm that my syntax for the 5 topr restaurantes next to Penang Flavours was correct:
        - Adding and substracting the degree_search and making it the '$gte' and the '$lte'
    - Find the syntax to check that the coordinates and rating value are now numbers in pymongo
        - Used a for loop technique with a limit of 5 with if statement of: if isinstance(var, (int, float))
    - Find the syntax to extract the latitude integer of establishments.find_one({"BusinessName": "Penang Flavours"}, {'geocode.latitude':1}) 


