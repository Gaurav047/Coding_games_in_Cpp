# Coding_games_in_Cpp

* Ensure that you have the SFML/graphics library installed, if not follow this [link](https://www.sfml-dev.org/tutorials/2.5/start-linux.php)

### To Compile and Run any of the games follow the following steps

* Go to the directory where the main.cpp file of the game is present
* Open Terminal
* Now create the object file using the following lines of code:

```
g++ -std=c++11 -c main.cpp
```

* Compile the object files created in the above steps using the following lines of code:

```
g++ main.o -o sfml-app -lsfml-graphics -lsfml-window -lsfml-system
```

* Run the app:

```
./sfml-app
```
