# Commit messages.
Hello there, 

For the person reading this, you are about dive deep into the mind of a literal lunatic.<br>
Have fun.

## Structure
My commit messages are structured in a universally applicable and consistant manner.<br>
The commits start with a commit **Verb** followed by a commit **Description**.<br>
<br>
Multiple commit structures can be chained together in a commit message delimited with an `,`.<br>
**NOWHERE in the commit can an emoji be used.**

#### Verb
A **Verb** is 1 word describing what action took place during the commit.<br>
You can see all the verbs I use in the **Verb table** down below.

| Verb       | Description   |
| ---------- | ------------- |
| Added      | A file or files have been added to the repository     |
| Removed    | A file or files have been removed from the repository |
| Fixed      | A file or files have been changed to squash a bug     |
| Updated    | A file or files have been changed for a new feature   |
| Refactored | A file or files have been changed to clean up code    |
| Changed    | A file or files who does not affect the codebase itself have been changed           |
| Merged     | Multiple files have been merged together into as smaller amount of files            |
| Installed  | This is purely for the installation (addition) of packages, libraries or frameworks |

#### Description
A **Description** is a small message to elaborate on the commit.<br>
The **Description** usually only consists only of a filename (without file extension) but can be a **Description** message.<br> 
In case of a **Description** message I advice myself and anyone reading this not to make the **Description** longer than 10 words.

## Examples

| Message                             | Description |
| ----------------------------------- | ----------- |
| Added middleware                    | Added a middleware.js file to the repository              |
| Added util/moo, Changed README      | Added a util/moo.js file and changed the README.md        |
| Fixed util/moo, Refactored util/moo | Squashed a bug in util/moo.js and Refactored it           |
| Merged util/moo and util/cow        | Merged the util/moo and util/cow file together            |
| Installed jQuery                    | Added the jQuery library (either via npm or a script tag) |

## Edge cases
In the case of a weird event down below are some edge cases in the commit structure listed.<br>

1. A version release, in this case I am allowed to use an emoji to be soy and celebrate all my gremlin work.
2. A commit action does not fit into any existing **Verb**, in this case I should add the **Verb** to the list or add an `!` infront of the **Verb** to indicate a weird commit.
