# Omeka and Research Collections

## What is Omeka

Omeka is a content management system and web-publishing system that allows users to organise and share a research collection.
It was particularly designed to help small galleries and museums to share their collections, so it handles images really well.
Omeka is a [Swahili](http://swahili_english.enacademic.com/11461/omeka) word meaning to display goods or wares, and that's what you're doing, when you make items public.

When you create your Omeka site, you should be aware if you're using Omeka's own hosting via [Omeka.net](omeka.net) or whether your institution is hosting its own instance.
If you create a free account at Omeka.net, you'll have less storage and access to fewer customisation options than if you download
Omeka from [Omeka.org](omeka.org) and host it yourself. This workshop will assume that you're using an Omeka.net account.

## Why Omeka?
Lots of researchers, particularly in the Humanities and Social Science (HASS) start organising their research collections in a 
spreadsheet like Excel or in tables in a Word document. Sometimes these will do the job for you, but if you have a large collection,
images, long text descriptions, or want to be able to relate items in multiple ways, these options quickly become problematic. 

**Omeka might be right for you if...**
* You want to organise and display a collection of items (these can be physical objects but can also be places, people, or events)
* You want to manage a lot of information about those items
* You have a lot of text in your fields
* You want to be able to relate your items to each other

**Omeka might not be your best option if...**
* You want a website with text and a few pictures. There are blogging platforms that will probably do this job for you better.
* You want to be able to do complex, custom queries. If you want a lot of sophistication in your queries, you might need a more powerful database.

## Components in Omeka
You'll need to understand the following terms to organise your collection in Omeka effectively.

**Item** This is the basic component of Omeka. Items may be objects, people or places. Items are described by *metadata* (more on this below) 
Omeka also lets you add a *type*, such as object, still image, person, or event to items. You can create your own item types to suit your needs.
You can attach files, such as images or recordings, to items. Note you can attach multiple files to one item record.

**Collection** Items within Omeka can be grouped into collections. Each item may belong to only one collection.

**Tags** You can use tags to draw connections between items. Tags are useful ways to relate items in different collections or to let you search for characteristics that don't form part of your metadata structure. It can be useful to think of tags as keywords that describe items.

**Exhibits** You can build *exhibits* of items and link them together with narrative or descriptive text for sharing.
You can select a small number of items from your repository (potentially from different collections) and organise them into an exhibit.
Visitors to your exhibit can click on an item and access its full record. Exhibits are made up of items that are grouped into pages (often with linking or explanatory text). Pages are then grouped into sections.

### Exercise
In small groups, discuss with your neighbours whether you think each of the following would be an *item*, a *metadata field* a *collection* or a *tag* within Omeka.

There are multiple options, depending on how you want to use your Omeka. 

* The person the Roman Emperor Augustus
* A picture of a statue of Augustus
* A picture of an incription commemorating Augustus' victory at the Battle of Actium in 31 BCE
* The text of the inscription commemorating Augustus' victory at Actium
* The event 'The Battle of Actium', in which Augustus defeated Cleopatra
* The year 31 BCE
* A poem by the Roman poet Horace commemorating Augustus' victory at Actium and the suicide of the Egyptian Queen Cleopatra
* A picture of a coin from Judea depicting Cleopatra
<div align="center"> 
![Image of Augustus](https://upload.wikimedia.org/wikipedia/commons/thumb/e/eb/Statue-Augustus.jpg/320px-Statue-Augustus.jpg) ![Coin of Cleopatra](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1e/Cleopatra_VII_tetradrachm_Ascalon_mint.jpg/250px-Cleopatra_VII_tetradrachm_Ascalon_mint.jpg)</div>

Suggestions: A political historian, principally interested in events, might make Augustus and Cleopatra items (people) and attach the pictures of the statue and coin to these items as files.
The inscription and poem could also be items, with the image and transcription attached as files. Key terms from the text could be added into the metadata.
'Actium' may be a tag that links Augustus, Cleopatra, the inscription and the poem. Actium might also be an item in its own right (event) and the year 31 BCE would form part of its metadata.

Alternatively, an art historian may be more interested in the physical artefacts, and make the statue, the incription, and the coin items, with the image files attached.
They could be placed respectively into collections 'Augustus' for the statue and inscription and 'Cleopatra' for the coin.
The text of the inscription might form part of the item's metadata, as might '31 BCE' and 'Actium'.    

These are only two suggestions and, as you can see, there are a lot of possibilities and no single right anwser!
# Organising your data

As you've seen from the exercise, there are a lot of possible ways to structure your collection. The way in which you organise it will be influenced by the questions you want to ask. We're spending a bit of time on this before we get into Omeka itself because it's important. Getting into a project and finding that your data is structured incorrectly is really frustrating.

## Metadata

Metadata can be described as 'data about data'. For instance, it's all the information about a book that goes into a lbrary record, such as the author's name and the date and place of publication, that will help you to identify it. Omeka uses **Dublin Core Metadata**, which means that it uses a particular set of agreed terms to describe items in a collection. Using standardised metadata is useful as it will make it easier to cross-reference your collection with other collections or migrate your collection to a different platform.

There are 15 fields in Dublin Core Metadata. They are:
* Title
* Date
* Subject
* Description
* Creator
* Source
* Publisher
* Contributor
* Rights
* Relation
* Language
* Type
* Format
* Identifier
* Coverage

There's an explanation of the information each of these fields is intended to contain on the [Dublin Core](http://dublincore.org/documents/dces) website. You might not find all of them useful, depending on your collection. Within Omeka, **Types** have additional metadata - for instance *Person* has fields for dates of birth and death and occupation.

<div align="center"> 
<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/7/71/8106_-_Roma_-_Ara_Pacis_-_Ottavia_Minore_-_Foto_Giovanni_Dall%27Orto_-_30-Mar-2008.jpg/308px-8106_-_Roma_-_Ara_Pacis_-_Ottavia_Minore_-_Foto_Giovanni_Dall%27Orto_-_30-Mar-2008.jpg" alt="Octavia"/></div>
<div align="center">Is this Octavia, a portrait of Octavia, or a photo of a portrait of Octavia? Which you choose will depend on your research questions. </div>

### Exercise - Bag of Thingies
Take the items in the collection that the trainer has given you. In small groups think about how you would sort them. What sort of metadata will you apply? How will you group them into collections? What tags will you use? It's really important to think about how you will organise your data before you start building your Omeka.
Possible metadata includes:
* Colour
* Size
* Material
* Texture

<div align="center"> 
<img src="https://farm5.staticflickr.com/4018/4676855235_8a03dba15d.jpg" alt="Craft Supplies"/></div>

**Note** Omeka will let you create multiple entries in each metadata field. This means that you could have two dates for an artefact - when it was created and when it was excavated. Just be sure that you're consistent about which dates you use and how you order them.
