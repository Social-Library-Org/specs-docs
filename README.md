# Social Library specs docs

All specifications and general documentation around Social Library.

## General context

Social Library aim is to help to manage a personal library of physical medias.

1. Project should always be fully open source.
2. Personal data should always be kept safe.
3. An association to support the project may be created if needed.
4. The development workflow is totally open. It means that anyone can contribute, the management is open, documentation, translation, code, etc.
5. The project's structure may allow anybody to host the service himself.

## Definitions

Only medias can be managed in Social Library.

**Media:** every physical object which complies to CreativeWork definition from schema.org [https://schema.org/CreativeWork](https://schema.org/CreativeWork)

## Aspects

Three aspects have been defined until now. Those aspects will be integrated into the software following the order below. It allows to manage progressively the application's complexity and to still have already some value at the beginning.

### Personal aspect

The personal aspect of Social library should let the user manage all his medias
whatever the type.

Using the service should help to know what the user has:
  - the user will than be able to know what to buy and avoid to have duplicates
  - the user can be at somebody's home and lend what he doesn't have

User data should always allow to be exported and imported.

### Sharing aspect

The shared aspect of Social Library should help people to interact
between each other and to lend things.

Using the service should:
  - help users to find things that may not be found otherwise
  - help users to exchange things for free
  - help users to have an archive to whom things have been lent

### Database aspect

The database aspect of Social Library should help to create a database of all
medias according to the definition of Media in **Definitions**.

This database should be freely accessible through an API.

