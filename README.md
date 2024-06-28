# Odin Recipes

This project is part of The Odin Project curriculum and aims to provide a basic understanding of HTML structure and the creation of a simple web page with various recipes.

## Iteration 1: Initial Structure

1. Create a directory named `odin-recipes`.
2. Create an `index.html` file within the `odin-recipes` directory.
3. Fill `index.html` with the usual boilerplate HTML and add an `h1` heading with the text "Odin Recipes" to the body.

## Iteration 2: Recipe Page

1. Create a new directory within the `odin-recipes` directory and name it `recipes`.
2. Create a new HTML file within the `recipes` directory and name it after the recipe it will contain, for example, `lasagna.html`. You can use the name of your favorite dish or find a recipe on Allrecipes for inspiration.
3. For now, just include an `h1` heading with the recipe's name as its content.
4. Back in the `index.html` file, add a link to the recipe page you just created. Example: Under the `<h1>Odin Recipes</h1>` heading, write out the link like so: `<a href="recipes/lasagna.html">Lasagna</a>`.

## Iteration 3: Recipe Page Content

Your new recipe page should have the following content:

1. An image of the finished dish under the `h1` heading that you added earlier. You can find images of the dish on Google or Allrecipes.
2. Under the image, add an appropriately sized "Description" heading followed by a paragraph or two describing the recipe.
3. Under the description, add an "Ingredients" heading followed by an unordered list of the ingredients needed for the recipe.
4. Finally, under the ingredients list, add a "Steps" heading followed by an ordered list of the steps needed for making the dish.

## Iteration 4: Add More Recipes

1. Add two more recipes with identical page structures to the recipe page you’ve already created.
2. Don’t forget to link to the new recipes on the index page. Also, consider putting all the links in an unordered list so they aren’t all on one line. Example:

   ```html
   <ul>
     <li><a href="recipes/lasagna.html">Lasagna</a></li>
     <li><a href="recipes/spaghetti.html">Spaghetti</a></li>
     <li><a href="recipes/tacos.html">Tacos</a></li>
   </ul>
