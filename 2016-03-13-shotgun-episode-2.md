# Shotgun Episode One

In this episode we continue work on the CardPlayer React component, adding element children tests to make sure everything we want is there without tying ourselves too tightly to the exact implementation inside each child. This technique allows us to test that the vital pieces are there without making the tests so fragile that any little change will break them and require you to refactor the tests.

Here are some things you'll learn about:

* Unit testing React components
* A fun JSX quirk I accidentally (re)discovered.

## Commit Log

[Flesh out the CardPlayer element](https://github.com/jshomes/course-player/tree/16a426cef25302f970c34fe83d94dd45038fdfbb)

* Add presence tests for all major UI pieces
* Disable continue button if isCompleted is false

## Links

* [Course Player](https://github.com/jshomes/course-player)
