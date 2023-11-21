# SDL2_Battleship_game
![Game Screenshot](https://i.imgur.com/zQiezZZ.png)
A battleship game made in c++ using SDL2 for homework. I had to finish it in a hurry, so there is some spaghetti code here and there. Maybe I will clean it and remove dead code, maybe.

# Dependencies
- SDL2
- SDL_mixer
- SDL_image
- SDL_ttf


# BUILD
I compiled using:

    g++ -Isrc/Include -Lsrc/lib -g main.cpp -o main.exe -lmingw32 -lSDL2main -lSDL2 -lSDL2_ttf -lSDL2_mixer -lSDL2_image
 
 Have in mind I had a local src/ folder with the lib/ and include/ data from SDL2 and its components, as well as the .dlls in the main folder which I did not include in this repo.

# Credits
Grid, Tiles and Sprites:
- ["Naval Battle Assets Pack" by Molly "Cougarmint" Willits](https://opengameart.org/content/naval-battle-assets-pack)

Font:
- [X.Template](https://all-free-download.com/font/download/xtemplate_6919000.html)

Sound Effects:
- ["Water Explosion" by Sheyvan](https://freesound.org/people/Sheyvan/sounds/519008/)
[[licensed under the Creative Commons 0 License]](https://creativecommons.org/publicdomain/zero/1.0/)

- ["bad explosion" by deleted_user_364925](https://freesound.org/people/deleted_user_364925/sounds/47252/)
[[licensed under the Creative Commons 0 License]](https://creativecommons.org/publicdomain/zero/1.0/)

- ["Family Friendly Inspect Sound, UI, or In-Game Notification" by MATRIXXX_](https://freesound.org/people/MATRIXXX_/sounds/657948/)]
[[licensed under the Creative Commons 0 License]](https://creativecommons.org/publicdomain/zero/1.0/)

- ["Access Denied" by suntemple](https://freesound.org/people/suntemple/sounds/249300/)
[[licensed under the Creative Commons 0 License]](https://creativecommons.org/publicdomain/zero/1.0/)


- ["The Battle Between Scorpio And Orion" by MATRIXXX_ ](https://freesound.org/people/MATRIXXX_/sounds/507307/) 
[[licensed under the Creative Commons Attribution License]](https://creativecommons.org/licenses/by/4.0/)


