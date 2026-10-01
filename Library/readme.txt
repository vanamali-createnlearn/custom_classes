Initial set up before you begin coding
1. Three different types of books named RedBook, BlueBook, GreenBook and add proximity prompts in each. 
2. Those have to be either meshes or base parts, cannot be models.
3. You can duplicate them scatter them across the map any number of times you want as long as the names are the same.
4. Take 3 different shelves for each corresponding book types.
5. It doesn't matter if they're models, parts or meshes because we'll do processing on invisible parts instead.
6. Adjacent to each shelf, add an invisible part and name it appropriately RedShelf, BlueShelf, GreenShelf
7. Add a proximity prompt in each of them.

CODE SETUP
BookScript goes inside EACH book
ShelfScript goes inside ServerScriptService

GAMEPLAY
1. Go near any book and use the prox promp to pick it up.
2. It should get attached as a tool into your backpack.
3. Select any one of the books and select the prox promp of any of the shelves.
4. If they match it gets destroyed, otherwise nothing happens - for now.
