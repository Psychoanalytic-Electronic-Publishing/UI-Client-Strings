# UI Client Strings

This repository holds all the string files for the app and the base Admin string files.  Parts of the admin files, those with formatting, should probably not be edited here since they may not load properly.  That mainly concerns the top boxes in admin.

See issues for more notes concerning specific loads here.

## Top Level files

Current set of files in English.  There are two files, one for the ADMIN settings (read by the APP in the database) and another for direct use by the client APP (needs to be in pep/dist/translatons folder during compilation)

## For Translation

Files sent for translation.  

## Translated

Translated Files.  Prefix Labeled as "ADMIN" and "APP" to indicate where they are applied.  ADMIN files are loaded into the SQL database table opascentral.api_client_configs, and APP files are loaded directly to the APP in the pep/dist/translatons folder.

The APP files need the prefix "APP." removed from them before placing in the pep/dist/translatons folder

## Early Drafts (Deprecated)

Temporary language drafts (deprecated)

