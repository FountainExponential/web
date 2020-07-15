# Fountain Exponential
## Fountain Exponential introduction for Writers
Fountain Exponential is a simple markup syntax for writing, editing and sharing game stories in plain, human-readable text. Fountain Exponential allows you to work on your game stories anywhere, on any computer or tablet, using any software that edits text files.

Extending Fountain the screenplay Markdown format, Fountain Exponential files are eminently readable. When special syntax is required, it is straightforward and intuitive.

Even when viewed as plain text, your game story feels like a screenplay playing in a game.

Fountain Exponential supports everything a game story writer is likely to need in the creative phases of writing for a game.

Because it’s just text, Fountain Exponential is also a great format for archiving game stories without worry of file-format obsolescence or incompatibility.



## Fountain Exponential for Developers
Fountain Exponential is the Markdown format for branching stories meant to ease game story development and provide a format for archiving stories.

### Conversion
A mayor design goal of Fountain Exponential is to create a basis other interactive fiction and gamebook story formats can be converted to and from, similar to Fountain being used as a store and intermediary between different screenplay formats.

### Upscaling
A possible scenario that should be possible with Fountain Exponential, is scaling up a story from a linear Fountain screenplay to branching game script. 

Dialog separate from action
The key to Fountain Exponential is that it's based on Fountain and thus specifies Characters and Dialog separate from the story. This makes it a better choice for a visual medium like a game.

### Ergonomics
Fountain Exponential will extend Fountain, the Markdown variant specific for the screenplay writing domain, in such a way that the excellent readability of Fountain will remain, but add the branching and triggering aspects for games.

### Supports multiple story styles
The engine can be used to tell a literature style story, by only using action in scenes and thus Fountain Exponential is an Interactive Fiction engine. The dialog option make it have an extra dimension, that is vital for characters on screen.

Various game modes should be supported by Fountain Exponential like text only adventure style games, illustrated gamebook style games, as well as games that host text in a 2d or 3d world.

### Entities matching Core Knowledge
In development psychology Core Knowledge is the innate knowledge humans and other living creatures are born with. The core knowledge domains are Objects, Agents, Geography, Calculus, Social roles and Shapes/Forms. Although lots is proven about the theory, there are still parts that are controversial. Whether true or not, what is relevant for Fountain Exponential is that basing certain language elements on these domains will make it very intuitive to understand. Fountain already has done part of this by defining Characters describing agents, Props describing objects and Locations describing geography.

All entities in a game they should be able to have elements like facts, values and operations tagged to them. These elements make it possible to interact with the host of the game. The flow of the story can also be changed by these elements as well and the text itself can be changed when variables in the text are replaced.

Specific entities like Characters, Props and Locations should be extended with Groups, Collections, Shapes and other when needed. These should be able to support the human cognition modes of Object interactions, Agent actions, Social Group dynamics, location Geography, calculation operations and Shape/Form description. 

Describing Shape/Form is generally omitted by screenplay writers in favor of a more poetic an compact style of describing the location and props. Prop masters and location scouts interpret these colorful descriptions to find objects and places they feel match the intend of the description. Game makers and interpreters could also be given the same freedom, but it should also be possible to be very precise in your description and have the interpreting application synthesize the object or place or have artist draw or model your vision. This way of describing may be very similar to descriptions of archeological finds and places, as the science of archology deals with the same problem.

Centering the text around entities would allow for organization of the text similar to what is in computer science called object oriented programming. Although the main story should read as a screenplay, interaction with entities not relefant to the story should be relegated to files holding the elements and interaction specific to that entity.

## Fountain Exponential technical similarities
### Commonmark
Commonmark is the Markdown standard all Markdown implementers agree on. Fountain is a bit strange, because it does not adhere to the Commonmark standard. The thinking being that Fountain is specific for screenplay writing and things like tables will never be in a screenplay.
Adding missing Commonmark functionality will make it easier for experienced Markdown users to pick it up.

#### Links
Adding links will enable branching stories like Gamebooks. Following links you can move from text to text, allowing you to create your own story.

#### Lists and Images
Adding lists, images and other visual elements, will make it more expressive. A Gamebook formatted game gets a lot more lively when in story snippets are occasionally accompanied with an image or a list of items.

#### Code blocks
Code blocks in markdown are special areas in the text that should be highlighted differently for clarity. Code blocks can be denoted with a specific language tag to highlight it in a specific way and are thus usable for multiple programming languages.

Adding code blocks and interpreting them as instructions that should be executed when the story passes that point will make it possible to make the story interact with the other game systems. The difference between Code blocks and the later mentioned declarative Yaml blocks, is that Code blocks are run every time the story passes the point of the Code block and the declarative Yaml blocks are only run once as an initialization.

### Markdown Extensions
Markdown extensions are added to the Markdown language by implementers, but are not standardized. 
Using the most suitable extensions for Fountain Exponential will make it compatible with those extensions and those experienced with these extensions will understand them quicker.

Adding Markdown extensions will make it more complex, but achieve the same things as it's competitors in a far simplify way. This will make creation of the story of a game easier, as well as allow for more clarity and ease of rewriting.

#### Container blocks
Containers in Markdown generally translate to a *div* in HTML.

Adding container blocks will make it possible to have menu structures in the game. A list inside a container will be interpreted as a menu the user must choose an option from. An example of a game that uses menu's extensively is "80 day's" by Inkle, unfortunatly their game engine Ink does menu's in a way that is easy to write but hard to read. Fountain Exponential hopes to make it's menu's easier to read, although they may be harder to write.

#### Attributes blocks
Attributes in Markdown generally translate to attributes on an element in HTML or CSS.

Adding attribute blocks that describe how an element should be displayed makes it possible to add emotion to the text. An example of a game that uses attributes extensively in it's text is "Night in the Woods" by Secret Lab, unfortunately their game engine Yarn Spinner adds these attributes in a clunky way making the text less readable. Fountain Exponential hopes to make attributes on text easier to read, although they may be harder to write.

#### Yaml blocks for data interaction
Yaml blocks are generally used in Markdown as a place to store values that get replaced in the text, making the Markdown into a template. It can only be added to the front of the file, hence the name "Yaml Front Matter" used by markdown interpreters.

Adding the ability to add Yaml to the front of a scene will make it possible to have trigger or event definitions for a scene. Other declarative data interaction may also be possible. The Yaml data blocks may be extended as a writer sees fit and an interpreting game engine can use or ignore whatever it finds. The Yaml blocks together with the code blocks makes it possible for the text to interact with the game systems.
