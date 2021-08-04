# Skeleton of a mono-repo

This is a collection of applications in the same repository.

## Do you have multiple applications that need to access the same database?

Code and schema need to move in lockstep. Change the schema in one place, and all other applications need to update their code.

By putting the applications in the same repository, it is very easy to keep changes in one place.

Changes to the front end & changes to the backend can be made on the same branch, merged at the same time & deployed simultaneously.

Nginx can be used as a reverse proxy, - multiple applications will appear externally no different to a single application.
