# Items

## Item tags
Every item can have arbitrarily many tags. Tags are used for:
  * classification of items, increasing searchability etc.
  * adding properties to items (see Item Properties).
  * adding offered links to items (see Item Links).

## Item Properties
Items have properties based on their tags. A property is simply a key-value-pair.
The key comes from a tag, the value is user input.

## Item Links
An item can offer links to other items based on its tags.
An item can be linked to other items based on the links they offer.

# Special tags

## The "basic"-Tag
Every item has the "basic" tag. The basic tag defines the following properties:
  * name, e.g. Glamdring
  * game-term, e.g. Sword of Orc-Shredding +17
  * description, e.g. a sword that is balanced toward the tip, holds a ruby in its hilt and is full of engravings
  * weight, e.g. 7 Stein
  * market-value, e.g. 711 gold

## The "container"-Tag
A container holds collection of items, e.g. a character's backpack, wallet, crate, cellar, ... .
Containers can be put inside containers to form a hierarchy.
By adding the "container"-tag to an item, it offers the link "contained-in".

## "type-*"-tags
If the name of a tag starts with "type-", it is considered to describe a type of item, such as "weapon", "armor", ...
An item can have arbitrarily many types.
If two items share a type, they are considered to have some similarity.
Use dashes to describe type-hierarchies: If the tag is "type-weapon-sword", then "sword" is considered to be a subtype of "weapon".
