# Fountain Exponential
## Fountain Exponential introduction for Writers
Fountain Exponential is a simple markup syntax for writing, editing and sharing game stories in plain, human-readable text. Fountain Exponential allows you to work on your game stories anywhere, on any computer or tablet, using any software that edits text files.

Extending Fountain the screenplay Markdown format, Fountain Exponential files are eminently readable. When special syntax is required, it is straightforward and intuitive.

The readability makes it easy to proof read and spell check the text. Automatic spell checkers that are generally integrated in word processors, are less error prone if the dialog and action are separate form the code, data or styling.

Even when viewed as plain text, your game story feels like a screenplay, with some game specifics sprinkled on top.

Fountain Exponential supports everything a game story writer is likely to need in the creative phases of writing for a game.

Because it’s just text, Fountain Exponential is also a great format for archiving game stories without worry of file-format obsolescence or incompatibility.

The ability to convert to or from Fountain Exponential gives you the freedom to change your story writing tool, just as Fountain has done for screenplay's. This can also simplify changing game engine, so you can enjoy new features and components.


## Fountain Exponential for Developers
Fountain Exponential is the Markdown format for branching stories meant to ease game story development and provide a format for archiving stories.

### Conversion
A mayor design goal of Fountain Exponential is to create a basis other interactive fiction and gamebook story formats can be converted to and from. The Fountain format is already successfully being used as a store and intermediary between different screenplay formats. This makes it easier to switch tool or engine and makes creating new tools or engines with innovative features more attractive, because old content can be easier ported to them.

Being able to converted to and from  Fountain Exponential, does imply that can hold all the data all the other formats can hold. New engines and the format they use, will inevitably bring new features and new data to hold. With a comprehensive standard, going from one engine to then next will ensure not all is lost and only the novel features have to be added.

### Upscaling
A possible scenario that should be possible with Fountain Exponential, is scaling up a story from a linear Fountain screenplay to branching game script. 

Dialog separate from action
The key to Fountain Exponential is that it's based on Fountain and thus specifies Characters and Dialog separate from the story. This makes it a better choice for a visual medium like a game.

### Ergonomics
Fountain Exponential will extend Fountain, the Markdown variant specific for the screenplay writing domain, in such a way that the excellent readability of Fountain will remain, but add the branching and triggering aspects for games.

### Proof reading
Dysorthography and dyslexia are rampant among developers, especially if they are writing in a foreign language. Fountain Exponential makes it easier to proof read and spell check the action, description and dialog of the game.

### Supports multiple story styles
The format can be used to tell a literature style story, by only using action in scenes, making it usable for an Interactive Fiction engine. The dialog option creates  an extra dimension, that is vital for characters on screen, just like in many games.

Fountain Exponential is intended to support various game modes like text only adventure style games, illustrated gamebook style games, as well as games that host text in a 2d or 3d world. The flow of control could be done via a graphical user interface, triggers on actions, a text menu, links in the text or a parser interpreting typed text.

### Entities matching Core Knowledge
In development psychology Core Knowledge is the innate knowledge humans and other living creatures are born with. The core knowledge domains are Objects, Agents, Geography, Calculus, Social roles and Shapes/Forms. Although lots is proven about the theory, there are still parts that are controversial. Whether true or not, what is relevant for Fountain Exponential is that basing certain language elements on these domains will make it very intuitive to understand. Fountain already has done part of this by defining Characters describing agents, Props describing objects and Locations describing geography.

All entities in a game they should be able to have elements like facts, values and operations tagged to them. These elements make it possible to interact with the host of the game. The flow of the story can also be changed by these elements as well and the text itself can be changed when variables in the text are replaced.

Specific entities like Characters, Props and Locations should be extended with Groups, Collections, Shapes and other when needed. These should be able to support the human cognition modes of Object interactions, Agent actions, Social Group dynamics, location Geography, calculation operations and Shape/Form description. 

Describing Shape/Form is generally omitted by screenplay writers in favor of a more poetic an compact style of describing the location and props. Prop masters and location scouts interpret these colorful descriptions to find objects and places they feel match the intend of the description. Game makers and interpreters could also be given the same freedom, but it should also be possible to be very precise in your description and have the interpreting application synthesize the object or place or have artist draw or model your vision. This way of describing may be very similar to descriptions of archeological finds and places, as the science of archology deals with the same problem.

Centering the text around entities would allow for organization of the text similar to what is in computer science called object oriented programming. Although the main story should read as a screenplay, interaction with entities not relevant to the story should be relegated to files holding the elements and interaction specific to that entity.

## Fountain Exponential technical details
The syntax of Fountain Exponential expands uppon the Fountain syntax that can be found on https://fountain.io/syntax It also merges back in some features of Markdown CommonMark and the Markdown Extensions.

### Fountain
Fountain most important feature is the character labeled dialog, so well known in the writing forms of screenplay, stageplay, teleplay and radioplay. Some interactive fiction formats mimic the labeling, but do so by adding the character in front of the line followed by a colon and then the spoken text. Fountains way of having the characters name in the line before the dialog is easier to read, but a bit more verbose. Optionally the character can be prefixed with an @ sign for clarity. Dialog ends with an empty line, but dialog may continue if 2 spaces are put in the empty line. This is exactly like the Fountain specification, but it is important to repeat here.

Fountain has support for screenplay specific things like Act, Sequence and Scene. These are spans of time. An Act is a defined part of the story structure. A Sequence, is contained in an Act and had to do with the reals of film being switched, but is now multiple scenes. A Scene is a span of time on a specific location, possibly with sub locations. These spans of time are similar to methods or functions in a programming language, because once they get called, some action gets performed.

#### Moments
A Moment is an optional part of the Scene. A moment is still a span of time on a location, just like a Scene, only shorter. It can be chosen or skipped depending on the state of the game or the player. A Moment should be a full paragraph or dialog line. For changes in parts of text us Slices.

#### Slices
A Slice is an optional part of a text. It is part of a Scene or Moment, but displays text based on the state of the game or the player. It can start and stop anywhere in the text and is intended to embellish the text. It is similar to some functionality in Ink that made the text adapt to the choices and situation of the player in an award winning way.

#### Continuations and detours 
Links and menu choices allow the story to divert to other Scenes, Moments and Slices by user input. A continuation or detour will divert the scene without waiting for input by the user. A detour will revert back to the originating story, but a continuation will continue on with the diversion. The difference between a continuation and detour can be denoted by a minus sign - and a equal sign = respectively.

Showing the continued or detoured to text as integrated or separate from the original text, is done in a similar way as Yaml does it, by respecting the line breaks of the text or removing the line breaks, making it seem like it's one line.  The way to denote one or the other is by a greater then sign > or a vertical pipe | 


There are thus 4 types of arrows 
a -> single arrow 
a => double arrow
a -| single stump and
a =| double stump

This also implies that the game engine keeps track of the stack of Scenes, Moments and Slices, in at least a rudimentary way, so it can go back to a previous text.

#### References to other files
To focus on the main story in the main file it should be possible to relegate the non relevant Scenes, Moments and Slices to other files. Adventure games have a lot of interaction that adds color to the story, but distracts from the drama. For instance the examine action generally results in a scene where the object, person or location is described, but this Scene seldom furthers the story. This description Scene should therefore be in another file, ideally grouped with other Scenes, Moments or Slices around a specific Entity.

The references to other files could be defined in the metadata at the top of the Fountain file, but could also be included run time as special inline code imports.

### Commonmark
Commonmark is the Markdown standard all Markdown implementers agree on. Fountain is a bit strange, because it does not adhere to the Commonmark standard. The thinking being that Fountain is specific for screenplay writing and things like tables will never be in a screenplay.
Adding missing Commonmark functionality will make it easier for experienced Markdown users to pick it up.

#### Links
Adding links will enable branching stories like Gamebooks. Following links you can move from text to text, allowing you to create your own story. Links are different from continuations or detours in that links have to be clicked by the user to make the story continue and the other ones do not.

#### Lists and Images
Adding lists, images and other visual elements, will make it more expressive. A Gamebook formatted game gets a lot more lively when in story snippets are occasionally accompanied with an image or a list of items.

#### Code blocks
It's code blocks are fenced by lines with-three \`\`\` back ticks, with optionally the language after the starting triple back ticks, making the code highlight for the specified language. 

Adding code blocks and interpreting them as instructions that should be executed when the story passes that point will make it possible to interact with the other game systems.
As Markdown is highly linked with Html and CSS it is natural to assume that the code should be JavaScript. This does not need to be the case as the code can be Java, C#, Python or any other language you desire. The choice of language may be influenced by the interpreter you use. All programming languages mentioned before, use a similar style of calling functions and checking conditions. Limiting the code to those things, will make it programming language agnostic and, more importantly, be easier to read.
A difference between Code blocks and the later mentioned declarative Yaml blocks, is that Code blocks are run every time the story passes the point of the Code block and the declarative Yaml blocks are only run once as an initialization.
An example of a code block example:
~~~
### Enter the arena
```
Player.adrainalinrush();
Player.strength += 1;
Crowd.exitement = 100;
```
The player walks exited onto the sand of the arena and the crowd goes wild.

@Player
Woouha!
~~~

#### Inline code
Markdown inline \`code\` has \`back-ticks around\` it.

##### Regular Inline code
Inline code is a span of instructions that are executed when the story passes that point, but change nothing of the text. It is simply a way of signaling of working with the other game systems. 

##### Injected Values
Inline code is a span of instructions that are executed when the story passes that point, but the value the code produces is injected into the text.  In this way the text can vary based upon the situation or show the stats of the other game systems.

Inline code injecting a value in the text is made by containing the code with backticks `, but starting with an equal sign. Technically it's an expression being evaluated and converted into a string.
And example of showing different text depending on the situation:
```
### The meeting
----
gender: female
----
@Player
Greeting `= (gender == female)? "Madam" : "Sir";`
```
An example of showing stats 
```
### The brag
@Player
I got  `= 3 + 4;` in one go.
```

#### Import of files
Importing another file at run time is done by special inline code fenced with back ticks but starting with a percentage sign %. This is a mixture of T4 template and Typescript styles of adding metadata.

```
`% import * as city from "city"; `
```

Or more specific
```
`% import CityCenter as citycenter from "city"; `
```

#### Adding functionality
Adding class and a function definitions to the code is possible, but should really be done in a code behind file.

~~~
```+ 
function playertest()
{
	Player.test();
}
```
~~~

##### Conditionals
Inline code conditional are instructions that are executed when the story passes that point, but determine if the following story elements should be shown. The elements that are mainly conditioned paragraphs or choice options.
Acts, Scenes, Moment and Slices can not be in a condition, as after a link was clicked or a choice was made something should follow. This enables the static checking of the validity of links and choice options. This also implies that a conditional can not condition something outside of an Act, Scene, Moment or Slice. 

An inline code conditional in the text is made by containing the code with backticks `, but starting with an question mark.
For example, a simple conditional:
```
### The salute
@Player
`? hasSword && taunting > 50`  I'll show you the tip of my sword!

The player makes some intimidating moves.
```

A simple conditional with an else option
```
### The salute
@Player
`? hasSword && intelligence < 50`  I'll show you the tip of my sword! `:`  Dare to come an play?

The player makes some intimidating moves.
```

A conditional that check multiple conditions, but takes the first that fits, similar to coalesce in SQL  or a switch statement with a default case.
```
### The salute
@Player
`? hasSword && intelligence < 50`  
I'll show you the tip of my sword! 
`:`  
`? hasSword` 
Dare to come an play? 
`:`  
I'll have you know, I'm a master at the noble art of boxing.

The player makes some intimidating moves.
```

#### Interleaving tekst and code
Interleaving tekst and code implies that code statements span multiple blocks or inline code.
A statement started in one code block  or inline code could continue in a following code block or inline code, making text and code weave together. This is similar to a template language like Microsoft T4 Templates or tools like Jekyll, Hugo or Pandoc. The text caught in between the statements will be treated as a hard coded string value by the code and when not assigned to a value, will be assumed it was meant to return and insert it in the text.

A continuation of a statement can only done inside of an Act, Scene, Moment or Slice. Because it's bound to these bounds, it must be part of the language or at least respect these limitations. Simply cutting an pasting, like template languages do, can lead to code not working or even worse code working sometimes and not working other times.

The syntax for conditionals is deliberately closer to Markdown then to any of those templating engines.  Firstly because they must be part of the languages and secondly that combining  with template engines can still be done without integration issues.

A simple example showing the enclosed text being assigned to a variable
~~~
### Finding a catch phrase
```
player.catchphrase =
```
@Player
That's cool.
`;`


@Player
I think I got it!
It'll be:
`= player.catchphrase;`

~~~

An example showing an if/else structure also showing that multiple lines can be covered by the conditional 
~~~
### Candy heat
----
favoriteFood: peppers
----
@Challenger
I dare you to eat this Madam Janet.

```
if(favoriteFood == peppers)
{
```

@Player
Sure, I'll eat it.

The player chows down on the pepper, amazing the challenger.

```
}
else
{
```

@Challenger
Come on, do it.

@Player
No way, josé.

The challenger eats the pepper mockingly.

@Challenger
Wuss.

`}`
~~~

An example showing a switch/case structure using C# style compact code
~~~
### Candy heat
----
favoriteDessert: ice
----
@Host
Care for dessert?
@Player
`switch(favoriteDessert){`
	`case "ice":` I'd love some ice-cream.
	`case "thee":` I'll have a thee, please.
	`default:` Just a glass of water would be fine.
`}`
~~~

### Markdown Extensions
Markdown extensions are added to the Markdown language by implementers, but are not standardized. 
Using the most suitable extensions for Fountain Exponential will make it compatible with those extensions and those experienced with these extensions will understand them quicker.

Adding Markdown extensions will make it more complex, but achieve the same things as it's competitors in a far simplify way. This will make creation of the story of a game easier, as well as allow for more clarity and ease of rewriting.

#### Yaml blocks for data interaction
Yaml blocks in Markdown are fenced by triple minuses ---

Yaml blocks are generally used in Markdown as a place to store values that get replaced in the text, making the Markdown into a template. It can only be added to the front of the file, hence the name "Yaml Front Matter" used by markdown interpreters.

Tagging Yaml data to Scenes and Moments is easy, unobtrusive an flexible. The interpreting game engine can use or ignore whatever it finds. The Yaml blocks together with the code blocks makes it possible for the text to interact with the rest of the game systems. 

###### Triggers and events
Adding the ability to add Yaml to the front of a Scene will make the scene be scannable for trigger or event definitions that should be handled by the interpreter. In this way, an action in the game can trigger the scene and display the text of the scene to the user.

###### Broadcasts and messages when entering
Other declarative data interaction may also be possible, like sending a data notification, when entering a scene, to a specific component or to all that are listening on a topic. In many cases tagging the Yaml of Message containing the data of a transaction would be better suited to a Moment, like that of buying an item. 

###### Data locality
The Yaml data blocks may be extended as a writer sees fit, but the data is always related and thus local to that Scene or Moment. A similar Scene in a different act does not have that data unless a copy is specified in code.

For example:
```
### Shopkeeper scene
---
subscriptions:
  triggerSituations:
    - location:  GothamCity
      shoparea:  Downtown
      action:    Interact
    - location:  WindyCity
      shoparea:  Docks
      action:    Interact
broadcasts:
  - topic: history
    anotherSaveArrival: true
messages:
  - to: Act1
    visitedShopkeeper: true
money: 100
cokecans: 0
---
@Shopkeeper
Hello what will it be?
::: {.shopMenu}
- A can of coke
  @Player
  I'll have a can of coke.
  @Shopkeeper
  Here you go.
  `money -= 1; cokecans += 1;`
* Information =| Info acquisition moment
+ Nothing
  @Player
  Sorry, nothing for now.
:::
@Player
Thank you.

#### Info acquisition Moment
---
broadcasts:
  - topic: research
    anotherPieceOfKnowledge: true
messages:
  - to: Infentory
    changeMoney: -10
---
@Player
Know any place that sells Grand cru de Colombia?
@Shopkeeper  
I'll take your tenner and give you directions.
`addDirections();`
Ask for Pablo. Say Tony send ya.
```

#### Attribute blocks
Attributes in Markdown are started by an open accolade { and end with a closing accolade }. The opening accolade is optionaly followed by a colon :, but this is a residue of Inline Attribute Lists (ISL), that does not match well with the hash # of id and dot . of class attributes. When using Markdig or Kramdown they translate to attributes on an element in HTML.

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
This text has data tagged to it {commandId=tag}
```
- An empty attribute block {} or {::} can be used to separate an element from the rest of the text. For example:
```
The {}readability{.emphasis} focused way.
or
Ths {::}programming{animation=woosh display=blink hover=haha} focused way.
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
  @Player
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

## Acknowledgements
I would like to acknowledge the foundational work that Fountain Exponential builds upon.

### Fountain
Whiteout the foundational work on Fountain by John August, Nima Yousefi and Stu Maschwitz, Fountain Exponential would not be possible. 
Please check out Fountain the markup syntax for writing, editing and sharing screenplays in plain human-readable text on 
https://fountain.io/

The Fountain syntax
https://fountain.io/syntax

The software that uses Fountain
https://fountain.io/apps 
The long list of software using the Fountain syntax on the Fountain Apps page stands testament to it's success and confirms that there is a need for interoperability in writing tools.

## Markdown
Whiteout the foundational work on Markdown by John Gruber and "the internet's own boy" Aaron Swartz.
Mark Grubers site Daring Fireball hosts the original Markdown project from 17 Dec 2004
https://daringfireball.net/projects/markdown/

The Markdown: Basics  
https://daringfireball.net/projects/markdown/basics

The Markdown: Syntax  
https://daringfireball.net/projects/markdown/syntax

## CommonMark
The CommonMark initiative trying to create a standard, unambiguous syntax specification for Markdown, along with a suite of comprehensive tests to validate Markdown implementations against this specification. 
https://commonmark.org/

## Markdown extensions
There are many Markdown Extensions to be found. For Fountain Exponential the ones that inspired the syntax for Yaml Front Matter, Attributes and Containers where essential for creating a coherent whole. The ones that come to mind are Markdig, Kramdoc, Pandoc, Jykill, Hugo, Markdown-r, VuePress.
