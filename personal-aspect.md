# Personal Aspect

Describes personal aspect requirements. 

## Media {#personal-aspect-media}

A user should be able to create and edit a media and reference its details.

A media can only be a child of CreativeWork according to schema.org and which is physical:
  - Book: [https:\/\/schema.org\/Book](https://schema.org/Book)
  - Game: [https:\/\/schema.org\/Game](https://schema.org/Game)
  - Movie: [https:\/\/schema.org\/Movie](https://schema.org/Movie)
  - MusicPlaylist: [https:\/\/schema.org\/MusicPlaylist](https://schema.org/MusicPlaylist)
  - TVSeries: [https:\/\/schema.org\/TVSeries](https://schema.org/TVSeries)

Following fields are mandatory when creating and editing a media:
  - Title: [https:\/\/schema.org\/name](https://schema.org/name)
  - Author: [https:\/\/schema.org\/author](https://schema.org/author)
  - Barcode: [https:\/\/schema.org\/Barcode](https://schema.org/Barcode)


### Media title

The title of a media is a text according to schema.org https:\/\/schema.org\/name


### Media author


The author of a media is a Person according to schema.org https:\/\/schema.org\/Person

Following fields are mandatory:
  - Name: [https:\/\/schema.org\/name](https://schema.org/name)
  - Family Name: [https:\/\/schema.org\/familyName](https://schema.org/familyName)


### Media barcode


Each physical media has a barcode which has to be referenced on the media.
The user can scan it with a smartphone or enter it manually.
  - The text barcode is stored as caption of [https:\/\/schema.org\/Barcode](https://schema.org/Barcode)
  - The image is stored after automatic generation in [https:\/\/schema.org\/Barcode](https://schema.org/Barcode)


## Library


A user should be able to add and remove a media from his library.

A media can be added directly by the user by creating it as described in [personal aspect's media ](#personal-aspect-media)or being added from the Social Library database aggregated from all users.

If the media is not yet available in the database, data can be fetched from a third party database or website like Amazon to autocomplete some parts of the required fields after the user has at least given the title or the identifier \(ISBN for books\).



