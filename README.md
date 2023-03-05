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

This could be divided in the following levels
1. The basic story, without diversions making it equal to a movie script.
2. An alternating story, that keeps to main flow of the story, but takes small detours.
3. A responding story, that adapts the main flow of the story after a detour.
4. A branching story, that deviates from the main story and does not come back to it, having multiple endings.
5. An open ended story, that has no main story flow and no ending, providing responses to player choices based on basic story content, on previous choices or novel content.

A side story, is a detour of the main story. It can change the main story, making it respond or return to the main story without making a change to it, providing only backdrop. A vignette is a very small side story providing only backdrop. An open ended story is made up of multiple side stories and vignettes, where the main story is the player being in the game world without end.

### Dialog separate from action
The key to Fountain Exponential is that it's based on Fountain and thus specifies Characters and Dialog separate from the story. This makes it a better choice for a visual medium like a game, where the location and action is shown instead of described.

### Ergonomics
Fountain Exponential will extend Fountain, the Markdown variant specific for the screenplay writing domain, in such a way that the excellent readability of Fountain will remain, but add the branching and triggering aspects for games.

In order to handle text in the most ergonomic way text is the primary thing in the language and conditions and variable handling secondary. Meaning that conditions are dotted among the text and code relegated to demarcated blocks and spans. This is the opposite to general programming languages that demarcate the text in string spans and blocks and makes the code primary.

Making the text primary is also done with HTML, as it can have code attributed in the elements of the structure. A HTML document is meant to be viewed as a static whole and has little sense of time. Some parts like CSS declarations such as highlight or screen size and evens like mouseover can be used to define what happens at a certain time, but that is going from one stable situation to another. Screenplay's and game are dynamic and Fountain Exponential has fundamental structures like  Scenes and Acts, that similar to functions in a programming language describe what happens at a certain time.

### Proof reading
Dysorthography and dyslexia are rampant among developers, especially if they are writing in a foreign language. Fountain Exponential makes it easier to proof read and spell check the action, description and dialog of the game.

### Supports multiple story forms
The format can be used to tell a literature story form, by only using action in scenes, making it usable for an Interactive Fiction engine. The dialog option creates an extra dimension, that is vital for characters that are shown on screen, just like in many games.

Fountain Exponential is intended to support various game modes like text only adventure games, illustrated gamebook type games, as well as games that host text in a 2d or 3d world. It is agnostic about the flow of control in the game, be it via a graphical user interface, triggers on actions, a text menu, links in the text or a parser interpreting typed text. Use what suits your game and engine best.

### Organize the text in multiple files
An average film script is around 110 pages, but the text for a game can be much more, because of the freedom to choice how the story branches and the actions you can do in the game. Luckily text is relatively cheap to create, but managing a mountain of text, gets harder and harder, the bigger it grows. Organizing the text in separate but related files can make that mountain manageable, similar to the code for an application.

#### A file per alternative story
A regular movie script can be seen as a basic game without any choices. On top of that, alternative choices can be added to make the game more immersive, but not change the main flow the story. The responses to those alternatives could be placed in separate files based on some categorization creating for instance a sexy or an aggressive story file next to the main file.
The sexy or aggressive story could be read as a regular story and choices would only make you jump between one of the stories.

Consider a movie about a detective inquiring about a lost robot. The basic story has the detective ask inquisitive question, but the game could add aggressive or sexy alternatives. The responses to those questions differs from the main story, but the detective will follow along the same path trying to find the lost robot. The aggressive file would hold the aggressive story line and the sexy file the sexy story. The player making a choice in the story would jump from one story line to the other. A responding story could have the scenes trigger on some variable for aggression or sexiness. Proofreading for the sexy or aggressive detective would be simplified, because the story in the file would be complete.

#### A file per entity
Entities like characters, props and locations can have a life of there own in a game. In a movie these are all subject to the story, but in a game they can have much more depth because there is more time to develop them. The parts of the story do detract from the main story and therefore it would be better to separate them from it. The would be referenced in the main story as a detour, but have little impact on it. 

### Entities matching Core Knowledge
In their core entities are special types of variables. In any play one could identify the characters, props and locations as well as certain roles a character play like protagonist or antagonist. All these entities can have elements like facts, values and operations tagged to them. These elements make it possible to interact with the host of the game. The flow of the story can also be changed by these elements as well and the text itself can be changed when variables in the text are replaced.

In development psychology Core Knowledge is the innate knowledge humans and other living creatures are born with. The core knowledge domains are Objects, Agents, Geography, Calculus, Social roles and Shapes/Forms. Although lots is proven about the theory, there are still parts that are controversial. Whether true or not, what is relevant for Fountain Exponential is that basing certain language elements on these domains will make it very intuitive to understand. Fountain already has done part of this by defining Characters describing agents, Props describing objects and Locations describing geography.

Specific entities like Characters, Props and Locations should be extended with Groups, Collections, Shapes and other when needed. These should be able to support the human cognition modes of Object interactions, Agent actions, Social Group dynamics, location Geography, calculation operations and Shape/Form description.

Describing Shape/Form is generally omitted by screenplay writers in favor of a more poetic an compact style of describing the location and props. Prop masters and location scouts interpret these colorful descriptions to find objects and places they feel match the intend of the description. Game makers and interpreters could also be given the same freedom, but it should also be possible to be very precise in your description and have the interpreting application synthesize the object or place or have artist draw or model your vision. This way of describing may be very similar to descriptions of archeological finds and places, as the science of archology deals with the same problem.

Centering the text around entities would allow for organization of the text similar to what is in computer science called object oriented programming. Although the main story should read as a screenplay, interaction with entities not relevant to the story should be relegated to files holding the elements and interaction specific to that entity. The interactive fiction engine Inform 6 implements the story around entities and Inform 7 puts a logic engine on top of that. However having only entities is a simulation of a world, but that makes telling a story difficult, so Fountain Exponential will have a hybrid approach, starting with the story and having embellishments by entities.

The programming architecture that is supports the idea of roles is that of Data, Context and Interaction (DCI). It supports the tagging of roles by separating interaction from data and context. It defines a business model similar to a domain in Domain Driven Design (DDD), but makes it anemic, in that it only has functionality for it's consistency, but not interaction. The interaction functionality is contained in roles that are put on the entities in the anemic model. The context is the service or main function that creates the entities and makes them interact with each other.

### Character persona described with the OCEAN model
Having a character list in a screenplay is seen as unprofessional as the characters should be memorable, but it's common for a movie to have a cast list at the end. In a large novel with a very large cast of characters, more common in children's books and speculative fiction, a character list at the beginning or end may can be helpful to the reader. In theatre a Dramatis Personae contains a list of the main characters in a play with the actors in the second column. When writing any kind of larger story having a list to track the characters is common, but it's part of the notes of the creator and not of the product. Having such a list either as a mental model or a real list helps with writing, rewriting, adapting the story to notes and proof reading. It would therefor make sense to incorporate a character list into the Fountain Exponential format in a similar way as notes and comments, that are useful when writing the screenplay, but not shown in the product.

Describing the persona of a character can be done in many ways. The mayor ones seem to be Mayer-Briggs Type inventory (MBTI) based on Jungian archetypes, Enneagram based on spirituality, Gallup Cliffort StrengthsFinder based on behavior in the work place and the OCEAN model based on scientific research of personality descriptions. Although Jungian archetypes are important for creative work and spirituality is important for creatives and strengths are important for hero's in a story, a screenplay is about describing characters and the OCEAN model is based on that. Going from a personality description to dialog and action is difficult with any system, but using the closes related one makes it as easy as possible.

The psychological trait theory, also known as the Big Five, five-factor model or OCEAN model is a scientific model based on the factor analysis, a statistical technique, of verbal descriptors of human behavior in personality survey data. It reveals semantic associations: some words used to describe aspects of personality are often applied to the same person. For example, someone described as conscientious is more likely to be described as "always prepared" rather than "messy". These associations suggest five broad dimensions used in common language to describe the human personality and psyche.
The theory identifies five factors:

* openness to experience (inventive/curious vs. consistent/cautious)
* conscientiousness (efficient/organized vs. extravagant/careless)
* extraversion (outgoing/energetic vs. solitary/reserved)
* agreeableness (friendly/compassionate vs. challenging/callous)
* neuroticism (sensitive/nervous vs. resilient/confident)

The five factors are abbreviated in the acronyms OCEAN or CANOE. Beneath each proposed global factor, there are a number of correlated and more specific primary factors. For example, extraversion is typically associated with qualities such as gregariousness, assertiveness, excitement-seeking, warmth, activity, and positive emotions.

#### Aspects of OCEAN factors
Each of the Big Five personality traits contains two separate, but correlated, aspects reflecting a level of personality below the broad domains but above the many facet scales that are also part of the Big Five. The aspects are labeled as follows:

* Neuroticism
  + Volatility 
  + Withdrawal
* Extraversion
  + Enthusiasm 
  + Assertiveness
* Openness to Experience
  + Intellect
  + Openness
* Conscientiousness
  + Industriousness 
  + Orderliness
* Agreeableness
  + Compassion 
  + Politeness

People who do not exhibit a clear predisposition to a single factor in each dimension above are considered adaptable, moderate and reasonable, yet they can also be perceived as unprincipled, inscrutable and calculating.

Studies indicate that the Big Five traits are not nearly as powerful in predicting and explaining actual behavior as are the more numerous facets or primary traits.

In contrast with Costa and McCrae's admittedly arbitrary decisions for the NEO PI-R facet scales, studies guided by the Lexical Hypothesis root facets in the personality language of laypeople. This approach is meant to test, and possibly enhance, the content validity of the measures used. Using the Five Factor Model, Gerard Saucier and Fritz Ostendorf explored each domain's facet structure through lexical studies. Using English and German participants and materials, they found a total of 18 facets, or "subcomponents," of the Big Five. These are:

* Extraversion
  + Sociability 
  + Unrestraint
  + Assertiveness
  + Activity-Adventurousness
* Openness to Experience
  + Intellect
  + Imagination-Creativity
  + Perceptiveness
* Conscientiousness
  + Orderliness 
  + Decisiveness-Consistency
  + Reliability
  + Industriousness
* Agreeableness
  + Warmth-Affection 
  + Gentleness
  + Generosity
  + Modesty-Humility
* Neuroticism
  + Irritability 
  + Insecurity
  + Emotionality

The lexical hypothesis is generally defined by two postulates. The first states that those personality characteristics that are important to a group of people will eventually become a part of that group's language. The second follows from the first, stating that more important personality characteristics are more likely to be encoded into language as a single word. The lexical hypothesis is a major foundation of the Big Five personality traits and has been used to study the structure of personality traits in a number of cultural and linguistic settings. Because it is linguistics based it would be a good match for a language that deals with describing personality.

## Fountain Exponential Vision
The vision for Fountain Exponential is to make proofreading of a game story as easy as reading a screenplay, while seeing pieces of the context of the story in special block that are easy to ignore, but may give hints to where in the game the text will fit. Having the text be split up in scenes and moments instead of less informative id's, having function calls in the text that have names that describe their intention, Yaml data block that convey data that is meaningful for the story, as well as attributes that alters the display of the elements of the text in predictable ways, will give the reader the context they need to see it the story enfolds properly and the freedom to be creative with the story. The responsibility of a readable story lies with the writer and these blocks of code and data can be done in a badly readable way, just as paragraphs can be written in a badly readable way. We thrust the writer with these tools, as the story should dictate the implementation, although the implementation can have an effect on the story, the writer should take these notes and adapt the story to them, so the story stays true to it's ideas and keeps it's internal consistency in tact.

Being able to convert Fountain Exponential to other formats, decouples the written text from the data used in game. This will make it possible for developers to use a format that is optimized for their game while, not making any demands on the format the writers use. The writers can also embellish the story to their liking without having to worry that the implementation will suffer.

Another part of the vision of Fountain Exponential is to make the story of a game a separate reusable asset similar to an image or a sound file. The story should not be locked up in the code or be specific for an engine. It should be possible to create a remake of the story in a different game engine, without having to rewrite the text of the story.

## Fountain Exponential Principles
Fountain Exponential tries to uphold the following principles:
1. A Fountain screenplay should be usable as a basis for a Fountain Exponential game story, by adding extra scenes for the branching story, ways to branch the story, like choices and links and embellish the story with technical details to interact with the rest of the game.
2. The story should be readable. Technical details, although important to developers, but matter little to writers, should detract as little as possible from the story. Therefor it is preferred to group code or data in a block or span, instead of sprinkling them through the text, as the reader can easier skip blocks and spans, if those are not relevant. 
3. The game engine should make little demand on the story and it's difficulties should be solved in the conversion process to an optimized format for the game.
4. The game story is an asset just as separate or integrated with the game, as other assets like images and sounds.
5. The game story should be transferable between game engines.
6. The game story should be able to hold the specific enhancements of an engine, without making the text less readable. Extending blocks and spans only has impacts on the length of text to skip, if those are not relevant for the reader.

## Fountain Exponential technical details
The syntax of Fountain Exponential expands upon the Fountain syntax that can be found on https://fountain.io/syntax It also merges back in some features of Markdown CommonMark and the Markdown Extensions.

### Fountain Syntax

Fountain Exponential offers complete support of the Fountain syntax. For a complete overview of the Fountain syntax, go to [http://fountain.io/syntax](http://fountain.io/syntax).

Title Page 
The Title Page holds metadata by Key Value pairs that are separated by `:` 
*Each key can have multiple values by placing them on newlines that are indented 3+ spaces or by a tab*

Fountain Element | Example
--------------|---------------
Title: | `Title:` **Title**
Credit: | `Credit:` **Written by**
Author: | `Author:` **Author Name(s)**
Source: | `Source:` **Story by...**
Draft date: | `Draft date:` **Date**
Contact: | `Contact:` **Contact Info**

After dropping to enters the Title Page is followed by the sceenplay elements

Fountain Element | Example
--------------|---------------
Sections | One `#` or more at the start of the line
"Act" Section | `#` at start of the line defines a **Act** section
"Sequence" Section | `##` at start of the line defines a **Sequence** section
"Scene" Section | `###` at start of the line defines a **Scene** section
Scene Headings | `.` at start of the line forces a Scene Heading. Using `INT.`, `EXT.`, `EST.`, `INT./EXT.`, `INT/EXT`, `I/E` at start of line interprets it also as a Scene Heading
Scene Numbers | `#`**Scene Number**`#` at the END of the Scene Heading
Action | `!` at start of the line forces Action or have a paragraph of text with an empty line before and after it 
Character | `@` at start of the line forces Character even for characters with lowercase letter or an all uppercase line with empty line before and no empty line after
Character Extensions | `(`**O.S., V.O., CONT'D**`)` at the END of the Character line 
Parenthetical | Lines of `(`**Parenthetical Text**`)` that are beneath Character or Dialogue lines
Dialogue | Lines of text that are beneath Character or Parenthetical lines
Dual Dialogue | `^` at the END of the SECOND Character line 
Lyrics | `~` at the start of the line
Transitions | `>` at start of the line forces a Transition or use `FADE IN:`, `FADE OUT.`, `FADE TO BLACK.`, alternatively an all uppercase line that ends with: `TO:`

Comments in the screenplay
Fountain Element | Example or Definition | Explanation
--------------|---------------|---------------
Synopses | Start line with: `=` | invisible text intended as writing aid for metadata
Notes | `[[`**Note Text**`]]` | invisible text intended for external stakeholders
Boneyard | `/*`**Boneyard Text**`*/` | invisible text intended for writer

Styling of screenplay text
Fountain Element | Example or Definition | Explanation
--------------|---------------|---------------
Centered Text | `>`**Centered Text**`<` | -
Page Breaks | `===` | Line that only contains three or more consecutive equal signs: 
Line Breaks | \r\n | Lines can be broken up by using carriage returns
Italics | `*`*Italic Text*`*` |-
Bold | `**`**Bold Text**`**` |-
Bold Italics | `***`***Bold Italic Text***`***` | -
Underline | `_`**Underline Text**`_` | Differs from markdown by not being strikethrough
\* | `\*` | Special characters can be escaped by prefixing them with a \ 


Fountain example:

```
Title:
    Title 1
    Title 2
Credit: Written by
Author: Author name
Source: Story by...
Draft date: 12/10/2014
Contact:
    Contact Info
    Address Line 1
    Address Line 2

# Act 1

= The introduction of Character

EXT. HOUSE - DAY

Some action text.

CHARACTER
(parenthetical)
Dialogue.

CUT TO:

.Scene Heading
```

### Fountain Syntax extensions by Fountain Exponential
Fountain Exponential Element | Example
--------------|---------------
"Moment" Section | `####` at the start of the line defines a **Moment** section
"Slice" Section | `#####` at the start of the line defines a **Slice** section
"divert separate" | `->`  single arrow 
"detour separate" | `=>` double arrow
"divert integrated" | `-\|` single stump
"detour integrated" | `=\|` double stump
"Searched Label" | `#~` after a diver or detour defines a **Searched Label** going to a section while ignoring the section level
Continue | \|\| at the start of a line defines the continue from this section to next section. Equal to a divert seperate and the label of the next section.
Image | Include an image for storyboarding 
Link | A link can be used for outside reference or anchors within the text
List | Visible list of elements, interpreted as a menu when contained in a Container.
Container | A block denoting an area with special rules.
Menu | A list wrapped in a Container
Conditionals | the if else statement controlling flow of the text, integrated into the text.
Arrangement | a generator that yields a text from a list every time when called 
Code span | Code integrated as part of the text, triggered at display time of the text.
Code block | A block of multiple lines of code, triggered when the structure element like a scene is used.
JSON Attribute span | Descriptive attributes in JSON format put on integrated parts of the text similar to CSS
JSON Attribute block | Descriptive attributes in JSON format put on elements similar to CSS
TOML block | Data, about game engine behavior like conditionals and triggers, in TOML format specific to the structure coming before it, but setting up the interaction with the game.
YAML block | Data, about in game behavior like visuals, in YAML format specific to the Entity of the game coming before it, triggered when the structure element like a scene is used. 


### Fountain
Fountain most important feature is the character labeled dialog, so well known in the writing forms of screenplay, stageplay, teleplay and radioplay. Some interactive fiction formats mimic the labeling, but do so by adding the character in front of the line followed by a colon and then the spoken text. Fountains way of having the characters name in the line before the dialog is easier to read, but a bit more verbose. Optionally the character can be prefixed with an @ sign for clarity. Dialog ends with an empty line, but dialog may continue if 2 spaces are put in the empty line. This is exactly like the Fountain specification, but it is important to repeat here.

Fountain has support for screenplay specific things like Act, Sequence and Scene. These are spans of time. An Act is a defined part of the story structure. A Sequence, is contained in an Act and had to do with the reals of film being switched, but is now multiple scenes. A Scene is a span of time on a specific location, possibly with sub locations. These spans of time are similar to methods or functions in a programming language, because once they get called, some action gets performed.

#### Moments
A Moment is an optional part of the Scene. A moment is still a span of time on a location, just like a Scene, only shorter. It can be chosen or skipped depending on the state of the game or the player. A Moment should be a full paragraph or dialog line. For changes in parts of text us Slices.

#### Slices
A Slice is an optional part of a text. It is part of a Scene or Moment, but displays text based on the state of the game or the player. It can start and stop anywhere in the text and is intended to embellish the text. It is similar to some functionality in Ink that made the text adapt to the choices and situation of the player in an award winning way.

#### Automatic diverts via Deviations and Detours 
Links and menu choices allow the story to divert to other Scenes, Moments and Slices by user input. A continuation or detour will divert the scene without waiting for input by the user. A detour will revert back to the originating story, but a deviation will continue on with the diversion. The difference between a deviation and detour can be denoted by a minus sign - and a equal sign = respectively.

Showing the deviated or detoured to text as integrated or separate from the original text, is done in a similar way as Yaml does it, by respecting the line breaks of the text or removing the line breaks, making it seem like it's one line.  The way to denote one or the other is by a greater then sign > or a vertical pipe | 


There are thus 4 types of arrows 
a -> single arrow 
a => double arrow
a -| single stump and
a =| double stump

This also implies that the game engine keeps track of the stack of Scenes, Moments and Slices, in at least a rudimentary way, so it can go back to a previous text.

In Fountain the synopses are single lines prefixed by an equals sign =. They can be located anywhere within the screenplay. This can conflict with the double arrow or double stump. To fix this add an exclamation point ! In front of it to make it action text. Alternatively using a double arrow or double stump in a container block would logically be a divert instead of a synopsis, but Fountain writing software does not know about these block.
```
# ACT I

= Set up the characters and the story.

EXT. BRICK'S PATIO - DAY

= This scene sets up Brick & Steel's new life as retirees. Warm sun, cold beer, and absolutely nothing to do.

A gorgeous day.  The sun is shining.  But BRICK BRADDOCK, retired police detective, is sitting quietly, contemplating -- something.

!=> Some Detour

:::
* Some choice
=> To elsewhere
* Some other choice
=| Something else, but integrating here.
:::
```

#### References to other files
To focus on the main story in the main file it should be possible to relegate the non relevant Scenes, Moments and Slices to other files. Adventure games have a lot of interaction that adds color to the story, but distracts from the drama. For instance the examine action generally results in a scene where the object, person or location is described, but this Scene seldom furthers the story. This description Scene should therefore be in another file, ideally grouped with other Scenes, Moments or Slices around a specific Entity.

The references to other files could be defined in the metadata at the top of the Fountain file, but could also be included run time as special inline code imports.

#### Dramatis Personae or Character list
A stageplay generally has a Dramatis Personae because every actors plays multiple roles. For a screenplay a Character list is considered bad form, because there shouldn't be so many characters that a list is needed to keep track of them. The characters should be memorable enough to be in the screenplay, although a tiny reminder in the action text can be helpful. 
The Character list should be created from the Characters used in the script. A list of possible Characters could be added to the metadata to make it possible to select the character in the editor. Be able to view where a character is used in the text and to jump to that part of the text is helpful, but is mostly a thing of the editor not the format.

### Commonmark
Commonmark is the Markdown standard all Markdown implementers agree on. Fountain is a bit strange, because it does not adhere to the Commonmark standard. The thinking being that Fountain is specific for screenplay writing and things like tables will never be in a normal screenplay. Adding missing Commonmark functionality will make it easier for experienced Markdown users to pick it up.

#### Links for interactive Diverts
Adding links will enable branching stories like Gamebooks. Following links you can move from text to text, allowing you to create your own story. Links are different from deviations or detours in that links have to be clicked by the user to make the story continue and the other ones do not.

#### Lists and Images
Adding lists, images and other visual elements, will make it more expressive. A Gamebook formatted game gets a lot more lively when in story snippets are occasionally accompanied with an image or a list of items.

#### Internal and Integrated Code
In order to have a branching story Fountain Exponential must have some flow of control. This is the essential difference between a markup language like Markdown and a programming language like those in the C family like C++, C#, Java, JavaScript, Python, etc.
Unfortunately code containers like spans and blocks encapsulating  an integrated C style language are rather verbose, especially when used in simple conditions and menu structures. Fountain Exponential's core focus on readability of the text is at odds with this verbosity. An internal language that can evaluate expressions is simply more concise, then a integrated language. Having the option of integrating another language with code containers can still be useful for special integrations with the hosting game or as an escape when the regular things do not work out or if the writer is more comfortable with the integrated language then the internal one. 
The internal language of Fountain Exponential must not only be concise, but also be clearly distinguishable from the regular text. Mainly this would improve readability of the text and mitigate the possibility of error, but it would also make the implementation easier, as the compiler can also distinguish things more easily.
The integrated language functions as an extension of the internal language. It can be any C style language as it is exported to an external interpreter or made to compile on the fly. The directives that come out of the integrated code are either Boolean values for conditionals or simple values to be integrated into the text like string, integer, floating point or a list. The language of integrated code can be set with the specific code block, but would normally be set for all the code containers in the metadata of the file.

#### Code blocks
It's code blocks are fenced by lines with-three \`\`\` back ticks, with optionally the language after the starting triple back ticks, making the code highlight for the specified language. 

Fountain Exponential can be seen as an inverted programming language, as the text is dotted with code instead of code dotted with text. In order to handle text in the most ergonomic way text, the dialog, action and descriptions, come first, flow of control, the choices and conditions, second and code, handling things like triggers and variable manipulation,  third.
Modern programming languages like C# or Python have string interpolation to integrate help adapt the text to the code and something similar happens with Fountain Exponential in that code is integrated in the text means, like menu choices and conditions.

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

#### Inline code span
Markdown inline \`code\` has \`back-ticks around\` it.

##### Regular Inline code
Inline code is a span of instructions that are executed when the story passes that point, but change nothing of the text. It is simply a way of signaling or working with the other game systems. 
```
### Arriving in town
@Player
What a lovely little town. `townGoesOnFullAlert();` Everything is as I expect it to be.
```
Alternatively calling code behind without showing the returned result can be done by using a & sign. Markdown color codeing will not work for this.
Using the & in the middle of a sentence can be done for a value or function, as the end of the expression can then be determined.
Having the & at the start makes the whole line being interpreted as instructions.
```
### Arriving in town
@Player
What a lovely little town. &townGoesOnFullAlert() I think we can make it smaller.
&player.drawnSword = player.hasSword && player.goodSwordArm 
```

##### Injected Values
Injected values are span of instructions that are executed when the story passes that point, but the value the code produces is injected into the text.  In this way the text can vary based upon the situation or show the stats of the other game systems.

Inline code injecting a value in the text is made by containing the code with backticks `, but starting with an equal = sign. Technically it's an expression being evaluated and converted into a string.
And example of showing different text depending on the situation:
```
### The meeting
----
gender: female
----
@Player
Greetings `= (gender == female)? "Madam" : "Sir";`
```
An example of showing stats 
```
### The brag
@Player
I got  `= 3 + 4;` in one go.
```
Alternatively calling code behind and injecting the return value can be done by using a $ sign. Using the $ can only be done for a value or function, as for an expression the end can not be determined.
```
### The meeting
----
name: "Lady Vagabond" 
----
@Player
Greetings $name
```
An example of calling a function 
~~~
```+ 
function amountRetrieved()
{
	return 3 + 4;
}
```
### The brag
@Player
I got  $amountRetrieved() in one go.
~~~

##### Integrated Common Code Language (ICCL)
The Integrated Common Code Language (ICCL) is the programming integrated with Fountain Exponential. It is intended as a bare bones implementation to control the story. Fountain Exponential code blocks can be used with multiple language like C/C++, C#, Java and Javascript, because it's primary consern is the text in the game. However an integrated language is needed when writing in an engine independent way.

###### Overriding ICCL
The ICCL can be overriden by blocks in a specific language by setting the override attribute to the id of the block with the specific language code.
The default language of Fountain Exponential is ICCL, but can be set in the front matter of the page to the specific language you want. For instance when setting the default language to C# code blocks are assumed to contain C#, so block that contain ICCL must then be attributes as ICCL.

##### Selection Trigger Values
Selection trigger values are a part of the text given to the other game systems when the story passes that point. It functions as an ID a way of signaling or working with the other game systems. This is the most natural way of signaling the other game systems, as natural text can be used as an identifying text. The identifying text could be used in multiple places serving like a function call.

A selection trigger value is created by prepending the text that functions as the ID with an % sign.
```
### Arriving in town
@Player
What a lovely little town. %Smiling face% Everything is as it should be. 
```
When the % is not ended with another % the rest of the line is assumed to belong to the ID.
```
### Arriving in town
@Player
What a lovely little town. Everything is as I expect it to be. %Smiling face
```
When the % is followed by a = the id is also put in the text. This allows for a more natural flow of the text.
```
### Arriving in town
@Player
One snap of my fingers and %=Snap% it's gone.
```

Alternatively a selection may be done and an attribute setting may be triggered similar to selecting HTML elements with CSS
```
### The curse takes effect
Alle the male villagers turned into zombies.
% .villager.male % { species=zombie }
```

#### Section parameters
A section can function as a method in a programming language. It can be made more generic if the text in the section can refer to parameters given to the section from outside the section.
The parameters that can be given to a section can be defined in between parentheses in the definition of the section.
```
#Act 1
You approach the man.

=> Meet the infamous(@blackKnight)

=> Where the fight takes place ( "Ardania" ) 

@blackKnight
Forget it, I'm out off here!

### Meet the infamous ( @person ) 
@Player
So we meet at last $person.name

### Where the fight takes place ( landname ) 
@Player
The lands of $landname will be witness to our joust.
```

#### Group sections into an Entity
A group or prototype is similar to a object, class or namespace in that it defines sections inside of it.
It can be one of the following:
Group type | Description
--------------|---------------
Object | An Object is something that exists outside of the game like part of the game engine. 
Entity | An Enity is something that exist inside of the game world similar to an object.

Subgroups of Objects and Entities can be removed or altered seperate from the them.
Group type | Description
--------------|---------------
Attribute | An attributed property of an Entity like it's color, smell or status.
Action | An action is something that can be performed on the Entity.
Interaction | An interactivety is something that can be performed by the Entity on another Entity.
Activety | An activety of the Entity that can be started and stopped to perform an Action periodicaly. 
Interactivety | An interactivety of the action that can be started and stopped to perform an Interaction periodicaley.

Having specific derivatives of Entity can make them have them the correct default representation and behavior in the game.
Specific derevatives bases on Cinematograpy and Core Knowledge are defined as:
Group type | Description
--------------|---------------
Game | The Object that represent the game itself.
Agent | An Entity with Agency in the game.
Player | A Agent that represents a Player in the game.
Character | A Character represents an Agent that matters to the story of the game. 
Supernumerary | A Character represents an Agent that matters little to the story of the game.
Animal | An Animal is an Agent that generaly functions as a backdrop in the game.
Location | A Location represents a Geographical Entity like a Room, Castle or Forest. Possibly having Attributes like Scenery, Terrain, Decor, Fictures, Ornaments etc.
Prop | A Prop represents an Physical Entity like an Item that matters to the story of the game.
Costume | A Costume represents an Physical Entity is worn by a Character or Supernumerary. It could also be implemented as an Attribute.
Furniture | A Furniture represents an Physical Entity that generaly functions as a backdrop in the game.
Plant | A Plant represents an Physical Entity that generaly functions as a backdrop in the game.
Fictitious | A Fictitious Entity represents an immaterial or artificial Entity like a Company, Nation or Team. Hierachies end relations are described with Fictitious Entities.

```
#Act 1
You approach the soldier.

=> &Soldier.Salut

&Soldier = create Character(Soldier) {
### Salut
The soldiers arm moves to his head and he stands at attention.

@Soldier
Sir!

}

```
##### Create a local copy of a Group
A Group of functionality can be made into a separate Entity, meaning that it's data will be split from the definition or original and go it's separate way. This can be done by Create(), Copy() or Clone().

When Create() is used the original definition is used to create a separate fresh unchanged Entity.
When Copy() is used the current state of the Entity is used to create a shallow copy of the Entity. Any other Entity the copied Entity refers to is not copied and is thus not a separate Entity.
When Clone() is used the current state of the Entity is used to create a deep copy of the Entity. Any other Entity the copied Entity refers to is also copied into a separate Entity. Game elements outside of the game world like the render engine are not subject to the deep copy.

The Create, Copy and Clone can be defined as sections, but can also be left up to the default implementation. 

#### Tables for quarriable data 
Frameworks that hold boilerplate response that are not part of the story but add to the believability of the game, for instance NPC in a city, should be able to be created and used in Fountain Exponential. 
The table definitions of Markdown can be reused here, in a similar fashion as the list is reused for the menu structure.
```
### Greet the NPC
::: {id=greetingsTable}

ID|Salutation|Response
--------------|---------------|---------------
upperClass|Greetings, sir| Greetings to you too
lowerClass|Hi! | Hello
Friend|=> Greet a friend | => A friend responds to a greeting

::: 

#### Greet a friend
@Player
Hi, how are you?
You look great.

#### A friend responds to a greeting
@NPC
I'm fine thanks.
Nice of you to notice.
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
Adding management of code elements like constant, variable, class and function definitions to the code is possible, but should really be done in a code behind file.

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

#### Interleaving text and code
Interleaving text and code implies that code statements span multiple blocks or inline code.
A statement started in one code block  or inline code could continue in a following code block or inline code, making text and code weave together. This is similar to a template language like Microsoft T4 Templates or tools like Jekyll, Hugo or Pandoc. The text caught in between the statements will be treated as a hard coded string value by the code. It is extracted from the text into the code, but when it is not assigned to a value, it will be assumed it was meant to return and insert it in the text.

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

#### Data and Code blocks
Fountain Exponential reuses a number of Front Matter blocks, like TOML, YAML and JSON to instruct or send data to the game engine. The same could be achieved with Code blocks, by setting properties and calling functions. Code blocks can differ in implementation language and data block can be parsed by multiple implementations and retain their meaning. All Data and Code blocks can be cut from the text and fed into their specific parsers. As these are common data format with parsers available in many languages this should not be an issue for implementors.

Having data blocks designated for specific purposes makes the intention of the text also clearer to the reader. While learning multiple format is harder then using just one format, it does match Fountain Exponential intention to optimize for readability.

#### TOML blocks for setting up interaction
Yaml blocks in Markdown are fenced by triple plusses +++

TOML blocks are generally used for setting up interaction with the engine like conditional triggers. Also adapting the story to the game engine by replacing parts of the story, like a scene that makes you choose where to go next, with walking around in a world, is done with TOML. As the game should be testable as a text adventure with choices, the TOML data sets up the dirty changes that are needed to have a different type of engine handle the story.

The TOML syntax is similar to that of INI files used in configuration of applications. It is therefor a natural fit for these technical configurations.

##### Special data keys
The user can put whatever is needed in the TOML block, but some keys are special in that they are useful to have.

###### The isStart key
The Boolean isStart key of a scene can be used to identify with what scene to start. Default the first scene in the file is the start of the story, similar to a screenplay starts at the first scene. For testing purposes a later scene can be set to be the starting scene by adding the isStart: true key to it. In the case of multiple scenes tagged with isStart: true the last one becomes the starting scene. The last one wins behavior is preferable when testing further and further down the story. It is also possible to tag a scene isStart: false, which is redundant under normal circumstances, but can be beneficial when switching between scenes when testing.

###### Conditional triggers
Adding the ability to add TOML to the front of a Scene will make the scene be scannable for conditional trigger definitions that should be handled by the interpreter. In this way, an action in the game can trigger the scene and display the text of the scene to the user.

Triggers is a name often used in 2d and 3d gaming, events is a name often used in business oriented software, in the interactive fiction community these are often called quality based narrative or storylets for short. All describe an action performed when some situation arises, but in 2d and 3d games this is often a location the player enters, in business oriented software this is often a button press and in quality based narrative this is often the value of a quality reaching a threshold value. A storylet is a piece of story with the description of the qualities under witch it triggers. The storylet was created by Failbetter for their game Fallen Londen and has been adopted by the interactive fiction community as a shorthand for quality based narrative.

Activating a scene by a trigger is actually a superset of activating a scene by following a links or making a choice in a menu. A trigger can be equivalent to those options by having the description of the trigger holding the data for a clicked link or a choice made and immediately activate when that situation arrives. The trigger could be expanded with other prerequisites, making it probably activate later in the story when that extra prerequisite is met or have multiple scenes where one is picket for a specific case. 
Following a link or making a choice in a menu seems much more easy to understand for humans then having some scene somewhere with a trigger on it, making it pop up in the story. This could however be used to move less relevant links and choices from the main story file to include files, so they don't detract from the main story. This would also make those include files more self contained and possibly be reusable in another story.


#### YAML blocks for triggered data interaction
Yaml blocks in Markdown are fenced by triple minuses ---

Yaml blocks are generally used for sending a package of data to the game engine when the Fountian Exponential structure like a scene is activated. This is similar to sending events in an event driven application. YAML emits triggers while TOML configures reception of triggers.

Yaml blocks in Markdown are used a place to store values that get replaced in the text, making the Markdown into a template. It can only be added to the front of the file, hence the name "Yaml Front Matter" used by markdown interpreters.

Tagging Yaml data to Scenes and Moments is easy, unobtrusive an flexible. The interpreting game engine can use or ignore whatever it finds. The Yaml blocks together with the code blocks makes it possible for the text to interact with the rest of the game systems. 

###### Broadcasts and messages when entering
YAML is used for declarative data interaction, like sending a data notification, when entering a scene, to a specific component or to all that are listening on a topic. In many cases tagging the Yaml of Message containing the data of a transaction would be better suited to a Moment, like that of buying an item. 

###### Data reception
The data in Yaml data blocks standard overrides the global data of the game. 

For example:
```
### Shopkeeper scene
+++
subscriptions:
  triggerSituations:
    - location:  GothamCity
      shoparea:  Downtown
      action:    Interact
    - location:  WindyCity
      shoparea:  Docks
      action:    Interact
+++
---
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
::: {style=shopMenu}
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

#### JSON Attribute blocks
Attributes in Fountain Exponential are similar to the attributes in HTML. They are JSON nodes in the Game Object Model (GOM) that is being hosted by the Engine Object Model (EOM). The EOM is not specified and can be implemented in multiple ways. The GOM is standardized and holds the elements of the text as wel as Entities in the game world. 

Attributes can alter the text, but also an Entity in the game. Therefore the attributes should not collide in meaning. For instance setting the color of the text should be done by {}sometext{style="text-color:blue"} while styling for instance the GUN in the game would be done by GUN{style="weapon-color:blue"}

Attributes in Markdown are started by an open accolade { and end with a closing accolade }. The opening accolade is optionaly followed by a colon :, but this is a residue of Inline Attribute Lists (ISL), that does not match well with the hash # of id and dot . of class attributes. When using Markdig or Kramdown they translate to attributes on an element in HTML.

Attributes are attached to the element that commes just before it:
- The previous inline element if the previous element is not a literal
- The previous block if the current block is a paragraph and the attributes is the only inline present in the paragraph
- Or the current block
- On a separated part of the text

They can be of 4 kinds:
- An id element, starting by # that will be used to set the id property of the HTML element
```
This text is identified { id=theTextId}
```
- A class element, starting by . that will be appended to the CSS class property of the HTML element
```
This text has class { class=haughty}
This text has has multiple influences { class="jazz highlight"}
```
- A style attribute with name:value pairs similar to inline CSS describing the element or entity
```
This text is displayed in blue {style="color:blue;font-size:9pt"}
```
- The style attribute can also change the display of locations, characters or props
```
EXT. BRICK'S PATIO - DAY 
{style="scenery:cloudy;decor:overgrown"}

@Brick
{style="pose:holdingBinoculars;expression:grim"}
It doesn't look good.

!Brick takes his {} GUN {type="revolver" style="look:worn;" onAction="blam"} and waves it around.
```

- An empty attribute block {} or {::} can be used to separate an element from the rest of the text. For example:
```
The {}readability{class=emphasis} focused way.
or
Ths {::}programming{style="animation:blink;hover:haha"} focused way.
```

Adding attribute blocks that describe how an element should be displayed makes it possible to style the text differently depending on the situation or add extra data for the interpreting game. For example, a command line text parser could used data attributed to choices to determine where the flow of the game should go.

An example of a game that uses attributes extensively, mainly to express emotion in it's text is "Night in the Woods" by Secret Lab, unfortunately their game engine Yarn Spinner adds these attributes in a clunky way making the text less readable. Fountain Exponential hopes to make attributes on text easier to read, although they may be harder to write.

#### Container blocks for interactive Diverts via menu's
Markdown containers are fenced by triple colons ::: optionally followed by and attribute block. When using Markdig, markdown-it or VuePress they translate to a div in HTML.

Adding container blocks will make it possible change meaning of a part of the text, while still maintaining the readability of Markdown. In a Markdown editor that does not know Fountain Exponential the container does not create problems with syntax highlighting etc.

Specifically lists in Markdown can, when encapsulated in a container, be interpreted as menu structures in the game. The list items becoming the options one must choose from. An example of a game that uses menu's extensively is "80 day's" by Inkle. Unfortunately their game engine Ink, does menu's in a way that is easy to write but hard to read, making it very powerful for programmers, but horrible for proofreaders. Fountain Exponential hopes to make it's menu's easier to read, although they may be harder to write. 

A menu Item can be  consumable designated with a star* or persistent designated with a plus+.  A consumable menu item can be used once, after witch it wont show up in the menu anymore. A persistent menu item is always available in the menu, whether it is used before or not. 

A continuation designated with a minus- is a persistent menu item that escapes the menu. Technically it is the same as the persistent menu item, but logically it is used as the option that makes no choice and just continues with the story. It could also be called the exit, oops or "not now" option. Having a separate menu symbol for continuation simplifies the checking of the menu structures, by proof reading as well as with linting generating warnings.

Generally the menu is ordered by consumable options, then persistent options and lastly the continuation. The consumable options are first because they are special and more interesting then the regular persistent options. The continuation is last because generally the player arrived at the menu wanting to interact with it and the last thing to do is leave.


And example of a simple menu structure, where the optional display class is added:
```
::: {style=navigationMenu}
Where to go next?
- Visit the shops. -> Shopping scene
* Visit the mayor. -> A talk with the Mayor
+ Leave town. -> On the road again 
:::
```
Menu structures can be hierachical, but as a rule menu's should not be deeper then 3 layers.
And example of a hierarchical and thus more complex menu structure, although the indenting does help:
```
::: {style=conversationMenu}
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

#### Game Entity Attribute Model (GEAM)
The Game Entity Attribute Model (GEAM) is the standard set of attributes the entities in Fountain Exponential, like Characters, Props and Locations should have. These attributes can set properties of the text displayed, but also change the display of the Entities in the game.

The GEAM is inspired by the Document Object Model (DOM) of HTML enabling designers to style webpages independantly of the browser implementation. An "Object models" has to related but different meanings (as mentioned by Jason Gregory):
* Properties/architecture of a particular object-oriented programming language (e.g. C++, Java, Python, …) used to manage code.
* Collection of objects/classes with which programs can be built or problems can be solved in scripting the state of elements and their display.

The term “game object model” really refers to two distinct object models:
* Tool-time, defining the content of the game world and their properties, including their behavior.
* Run-time, optimized for speed, visuals and gameplay and therfore less dynamic as tools.

Fountain Exponential, just like the screenplay format it is based on, is a tool used to implement a solution. A screenplay is used for shooting a film and Fountain Exponential is intended to be used to create a game with. GEAM is therefor aimed at tool time dynamics and generalization instead of optimized for running in a game or supporting features of a specific game engine.

GEAM tries to support the Core Knowledge model by implementing the attributes of Entities that designers and developers will expect.


## Implementation

### Writing a compiler
The compiler could be writen like the Go compiler explained in "Lexical Scanning in Go - Rob Pike"

### Compiling to an Intermediate Language Format
It should be possible to compile Fountain Exponential to an intermediate data format. Interactive Fiction writers would feel their work is more protected. It's also more effictient to run in a browser or game engine.

### Intermediate Language Format definition
The Intermediate Language Format could be in XML, JSON, YAML or a proprietery format. 
A proprietery format has the adventage that it can be very compact and performant, but speed is generaly not an issue and it's difficult to have multipole implementation for such a forma, because they must all be made by the holder of the format.
Generic formats like XML, YAML and JSON are prefered, because it's easy to get them running on any platform.
XML has the adventage that it's readable and it's possible to fix errors by hand, but it's too verbose.
YAML has the advantage that it's compact and easy to read when it's small, but when it gets big it gets difficult to read and error prone.
JSON has the advantage that it's compact and supported in the brower. It's may be difficult to read especialy compressed, but that is actually an advantage.
JSON seems like the prefered choise for an Intermediate Language Format.

This would be similar to Interactive Fiction Mark Up Language (IFML), although that is writen in XML and is going nowhere.

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

### Markdown
Whiteout the foundational work on Markdown by John Gruber and "the internet's own boy" Aaron Swartz.
Mark Grubers site Daring Fireball hosts the original Markdown project from 17 Dec 2004
https://daringfireball.net/projects/markdown/

The Markdown: Basics  
https://daringfireball.net/projects/markdown/basics

The Markdown: Syntax  
https://daringfireball.net/projects/markdown/syntax

### CommonMark
The CommonMark initiative trying to create a standard, unambiguous syntax specification for Markdown, along with a suite of comprehensive tests to validate Markdown implementations against this specification. 
https://commonmark.org/

### Markdown extensions
There are many Markdown Extensions to be found. For Fountain Exponential the ones that inspired the syntax for Yaml Front Matter, Attributes and Containers where essential for creating a coherent whole. The ones that come to mind are GitHub flavored Markdown, Markdig, Kramdoc, Pandoc, Jekyll, Hugo, Markdown-r, VuePress.

### Hugo Front Matter Formats
Hugo supports four formats for front matter, TOML, YAML, JSON and ORG. This illustrates the multiple ways Markdown can be interspeced by data.
https://gohugo.io/content-management/front-matter/

### Interactive Fiction Mark Up Language (IFML)
https://sourceforge.net/projects/ifml/

http://ifml.sourceforge.net/#:~:text=Interactive%20Fiction%20Markup%20Language%20%28IFML%29%20is%20an%20XML,scenes%2C%20dialogs%2C%20monologs%20and%20create%20characters%20and%20props.

https://github.com/IFML2/ifml2

### Go Compiler
Lexical Scanning in Go - Rob Pike
https://www.youtube.com/watch?v=HxaD_trXwRE&list=PL3NQHgGj2vtsJkK6ZyTzogNUTqe4nFSWd

### Specflow Gherkin
The Gherking language is used to describe test cases in Specflow in a BDD style. The Given, Then, When syntax is quite limited, but the idea of using sentences as ID's on another language is quite powerfull. The Trigger Values follow the same concept.

### Core Knowledge
The work of mainly Elizabeth Spelke that human and other living beings have innate mental abilities is inspiration for having a story format that supports that.

Lecture in Science: From Core Concepts to New Systems of Knowledge by Dr. Elizabeth Spelke
https://www.youtube.com/watch?v=Ojz-kgOEij8

### Data, Context and Interaction (DCI)
The work of Trygve Reenskau and James O. Coplien is an inspiration as it takes Object Oriented one step further. By doing so it better matches what happens in the real world or in an imaginary world as in a game or on stage. The idea of entities performing a role in DCI, matches with agents, objects or geography performing a role in core knowledge and characters, props and locations performing a role in a story.

### Deep Nesting
The rule to not nest the menu's deeper then 3 layers commes from the programming rule to not nest if statements deeper then 3 layers. Excessive indentation, or "nesting," has been pilloried in computing literature for decades and is still one of the chief culprits in confusing code. Studies by Noam Chomsky and Gerald Weinberg suggest that few people can understand more than three levels of nested ifs (Yourdon 1986a), and many researchers recommend avoiding nesting to more than three or four levels (Myers 1976, Marca 1981, and Ledgard and Tauer 1987a). 

### Game object models
Jason Gregory presentation starts with a high level explanation of the obejct models used in game development, then dives into the different implementations. As  Fountain Exponential is intended as a standard decoupled from the implementation those are less relevant, but provide an insight in what an implementation might do.

GAME OBJECT MODELS and Scripting Jason Gregory Naughty Dog, Inc.
https://www.gameenginebook.com/resources/GEA2_GameObjectSystems.pdf

Game object models - Game Engine Architecture
https://www.slideshare.net/ShawnPresser/game-object-models-game-engine-architecture
