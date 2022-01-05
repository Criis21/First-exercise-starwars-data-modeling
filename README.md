<p align="center">
	<img
		width="300"
		alt="4Geeks Academy"
		src="https://github.com/4GeeksAcademy/About-4Geeks-Academy/blob/master/site/static/background_art.jpg?raw=true">
</p>


<h1 align="center">Welcome to 4Geeks Academy</h1>


<h3 align="center">&lt;StarWars blog database&gt;</h3>

## Content

1. Language
2. Project instructions
3. Instalation


## 👩‍💻Language
<p>This project contains:</p>

<ol>
    <li>SQL</li>
    <li>SQLALCHEMY</li>
    <li>UML</li>
    <li>DATA-MODELING</li>
</ol>

## 📝Proyect instructions 
We are going to be creating the Entity Relationship Diagram for your StarWars Blog Database, a very similar diagram to this one:

![Starwars Diagram](https://github.com/breatheco-de/exercise-starwars-data-modeling/blob/master/assets/example.png?raw=true)

The project is using the SQLAlchemy Python library to generate the database.

- Your project must have a table `User` that will represent your blog users.
- Your blog users will be able to login and save their favorite planets and characters.
- The database should store the user favorites.
- The database should store characters and planets.
- What other tables do you think a blog like this might have?
- What properties should go inside the user? or inside the Character or Favorite table?
- What are the relationships between those tables?
- Please add at least 4 models with all of its properties.
- Generate the diagram.png file at the end by running `$ python3 models.py` on the console.



## 💻 Instalation

1. Get inside the environment `$ pipenv shell`

2. Install all dependencies `$ pipenv install`

3. Generate de diagram as many times as you need `$ python src/models.py`

4. Open the file `diagram.png` to check out your UML diagram!


Your Job is to update the `src/models.py` file with the code needed to replicate the Starwars data model.



