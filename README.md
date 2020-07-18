# Fountain Exponential
## Fountain Exponential introduction for Writers
Fountain Exponential is a simple markup syntax for writing, editing and sharing game stories in plain, human-readable text. Fountain Exponential allows you to work on your game stories anywhere, on any computer or tablet, using any software that edits text files.

Extending Fountain the screenplay Markdown format, Fountain Exponential files are eminently readable. When special syntax is required, it is straightforward and intuitive.

Even when viewed as plain text, your game story feels like a screenplay playing in a game.

Fountain Exponential supports everything a game story writer is likely to need in the creative phases of writing for a game.

Because it’s just text, Fountain Exponential is also a great format for archiving game stories without worry of file-format obsolescence or incompatibility.

The ability to convert to or from Fountain Exponential gives you the freedom to change your story writing tool, just as Fountain has done for screenplay's. This can also simplify changing game engine, so you can enjoy new features and components.


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
The format can be used to tell a literature style story, by only using action in scenes, making it usable for an Interactive Fiction engine. The dialog option creates  an extra dimension, that is vital for characters on screen, just like in many games.

Fountain Exponential is intended to support various game modes like text only adventure style games, illustrated gamebook style games, as well as games that host text in a 2d or 3d world. The flow of control could be done via a graphical user interface, triggers on actions, a text menu, links in the text or a parser interpreting typed text.

### Entities matching Core Knowledge
In development psychology Core Knowledge is the innate knowledge humans and other living creatures are born with. The core knowledge domains are Objects, Agents, Geography, Calculus, Social roles and Shapes/Forms. Although lots is proven about the theory, there are still parts that are controversial. Whether true or not, what is relevant for Fountain Exponential is that basing certain language elements on these domains will make it very intuitive to understand. Fountain already has done part of this by defining Characters describing agents, Props describing objects and Locations describing geography.

All entities in a game they should be able to have elements like facts, values and operations tagged to them. These elements make it possible to interact with the host of the game. The flow of the story can also be changed by these elements as well and the text itself can be changed when variables in the text are replaced.

Specific entities like Characters, Props and Locations should be extended with Groups, Collections, Shapes and other when needed. These should be able to support the human cognition modes of Object interactions, Agent actions, Social Group dynamics, location Geography, calculation operations and Shape/Form description. 

Describing Shape/Form is generally omitted by screenplay writers in favor of a more poetic an compact style of describing the location and props. Prop masters and location scouts interpret these colorful descriptions to find objects and places they feel match the intend of the description. Game makers and interpreters could also be given the same freedom, but it should also be possible to be very precise in your description and have the interpreting application synthesize the object or place or have artist draw or model your vision. This way of describing may be very similar to descriptions of archeological finds and places, as the science of archology deals with the same problem.

Centering the text around entities would allow for organization of the text similar to what is in computer science called object oriented programming. Although the main story should read as a screenplay, interaction with entities not relevant to the story should be relegated to files holding the elements and interaction specific to that entity.

## Fountain Exponential technical similarities
### Fountain
Fountain has support for screenplay specific things like Act, Sequence and Scene. These are spans of time. An Act is a defined part of the story structure. A Sequence, is contained in an Act and had to do with the reals of film being switched, but is now multiple scenes. A Scene is a span of time on a specific location, possibly with sub locations. These spans of time are similar to methods or functions in a programming language, because once they get called, some action gets performed.

#### Moments
A Moment is an optional part of the Scene. A moment is still a span of time on a location, just like a Scene, only shorter. It can be chosen or skipped depending on the state of the game or the player. A Moment should be a full paragraph or dialog line. For changes in parts of text us Slices.

#### Slices
A Slice is an optional part of a text. It is part of a Scene or Moment, but displays text based on the state of the game or the player. It can start and stop anywhere in the text and is intended to embellish the text. It is similar to some functionality in Ink that made the text adapt to the choices and situation of the player in an award winning way.

#### Links and References to Scenes, Moments and Slices
Links and References allow the story to divert to other Scenes, Moments and Slices, but a Link will continue there while a Reference will revert back to the originating story. Also showing the diverted to text with or without line breaks, therefor integrating it in the original text or making it separate from it. The difference between link and reference can be denoted by - and =. The difference between integrating or separating the diverted to text can be denoted by > and | similar to Yaml. There thus be 4 types of arrows ->, =>, -|, =|. This also implies that the game engine keeps track of the stack of Scenes, Moments and Slices, so it can go back to a previous one.

#### References to other files
To focus on the main story in the main file it should be possible to relegate the non relevant Scenes, Moments and Slices to other files. Adventure games have a lot of interaction that, but adds color to story but distracts from the drama. For instance the examine action generally results in a scene where the object, person or location is described, but this Scene seldom furthers the story. This description Scene should therefore be in another file, ideally grouped with other Scenes, Moments or Slices around a specific Entity. 

### Commonmark
Commonmark is the Markdown standard all Markdown implementers agree on. Fountain is a bit strange, because it does not adhere to the Commonmark standard. The thinking being that Fountain is specific for screenplay writing and things like tables will never be in a screenplay.
Adding missing Commonmark functionality will make it easier for experienced Markdown users to pick it up.

#### Links
Adding links will enable branching stories like Gamebooks. Following links you can move from text to text, allowing you to create your own story.

#### Lists and Images
Adding lists, images and other visual elements, will make it more expressive. A Gamebook formatted game gets a lot more lively when in story snippets are occasionally accompanied with an image or a list of items.

#### Code blocks and inline code
Markdown inline \`code\` has \`back-ticks around\` it. It's code blocks are fenced by lines with-three \`\`\` back ticks, with optionally the language after the starting triple back ticks, making the code highlight for the specified language. 

Adding code blocks and inline code, interpreting them as instructions that should be executed when the story passes that point will make it possible to interact with the other game systems. The difference between Code blocks and the later mentioned declarative Yaml blocks, is that Code blocks are run every time the story passes the point of the Code block and the declarative Yaml blocks are only run once as an initialization.

### Markdown Extensions
Markdown extensions are added to the Markdown language by implementers, but are not standardized. 
Using the most suitable extensions for Fountain Exponential will make it compatible with those extensions and those experienced with these extensions will understand them quicker.

Adding Markdown extensions will make it more complex, but achieve the same things as it's competitors in a far simplify way. This will make creation of the story of a game easier, as well as allow for more clarity and ease of rewriting.

#### Yaml blocks for data interaction
Yaml blocks are generally used in Markdown as a place to store values that get replaced in the text, making the Markdown into a template. It can only be added to the front of the file, hence the name "Yaml Front Matter" used by markdown interpreters.

Adding the ability to add Yaml to the front of a scene will make it possible to have trigger or event definitions for a scene. Other declarative data interaction may also be possible. The Yaml data blocks may be extended as a writer sees fit and an interpreting game engine can use or ignore whatever it finds. The Yaml blocks together with the code blocks makes it possible for the text to interact with the game systems.

#### Attribute blocks
Attributes in Markdown generally are started by open accolade { and end with the closing accolade }.  When using Markdig  or Kramdown they translate to attributes on an element in HTML.

Attributes can be attached to:
- The previous inline element if the previous element is not a literal
- The next block if the current block is a paragraph and the attributes is the only inline present in the paragraph
- Or the current block
- On a separated part of the text

They can be of 4 kinds:
- An id element, starting by # that will be used to set the id property of the HTML element
```
This text is identified {#theTextId}
```
- A class element, starting by . that will be appended to the CSS class property of the HTML element
```
This text has class {.haughty}
```
- A name=value or name="value" that will be appended as an attribute of the HTML element
```
This text has data tagged to it {: command=tag}
```
- An empty attribute block {::} can be used to separate an element from the rest of the text. For example:
```
This {::}text{:.special} is special
```

Adding attribute blocks that describe how an element should be displayed makes it possible to style the text differently depending on the situation or add extra data for the interpreting game. For example, a command line text parser could used data attributed to choices to determine where the flow of the game should go.

An example of a game that uses attributes extensively, mainly to express emotion in it's text is "Night in the Woods" by Secret Lab, unfortunately their game engine Yarn Spinner adds these attributes in a clunky way making the text less readable. Fountain Exponential hopes to make attributes on text easier to read, although they may be harder to write.

#### Container blocks
Markdown containers are fenced by triple colons ::: optionally followed by and attribute block. When using Markdig, markdown-it or VuePress they translate to a div in HTML.

Adding container blocks will make it possible change meaning of a part of the text, while still maintaining the readability of Markdown. In a Markdown editor that does not know Fountain Exponential the container does not create problems with syntax highlighting etc.

Specifically lists in Markdown can, when encapsulated in a container, be interpreted as menu structures in the game. The list items becoming the options one must choose from. An example of a game that uses menu's extensively is "80 day's" by Inkle. Unfortunately their game engine Ink, does menu's in a way that is easy to write but hard to read, making it very powerfull for programmers, but horrible for proofreaders. Fountain Exponential hopes to make it's menu's easier to read, although they may be harder to write. 

And example of a simple menu structure, where the optional display class is added:
```
::: {.navigationMenu}
Where to go next?
- Visit the shops. -> Shopping scene
* Visit the mayor. -> A talk with the Mayor
+ Leave town. -> On the road again 
:::
```
And example of a hierarchical and thus more complex menu structure, although the indenting does help:
```
::: {.conversationMenu}
What shall we talk about?
- Talk about shopping?
  @Avatar
  How is shopping going?.
  @Conversationnist
  It's fine.
  :::
  Your response?
  - Great!
    @Avatar
    Great to see you enjoy yourself.
  + Ok.
    @Avatar
    Nice to see you up and about.
  :::
+ Stay silent. -> Stare at each other
:::
```

