# EMPIR project 17IND12 ***Met4FoF*** coding conventions
These coding conventions apply to all code and software written for the project
and will constantly be extended as the project evolves and more code is written.  

## Design

1.  All lines in code files should not exeed 80 characters.

1.  Names for modules, classes, methods and functions should be speaking and
    explicitly represent the content.

1.  The use of global variables should be avoided where possible.

1.  There should be no *TODO*-statements in production code.

1.  There should be no out commented code in production code.

1.  *CI/CD* should be implemented, if applicable.

## Documentation

1.  All documentation should be provided in English.

1.  A first overview of what the code in a repository does should be provided
    inside a `README.md`.

1.  All parts of the public interface of modules, classes, methods and functions
    should provide detailed information in their headers about inputs, outputs
    and what is done.

1.  A module/class header should at least provide information about authors,
    available functions and module-/class-parameters.

1.  Function und method headers should provide information about authors, what
    and how it is done and in- and output parameters.

1.  For in- and output parameters that are vectors or matrices, information on
    the dimensions should be provided.

1.  Presentation of inputs and outputs should be consistent throughout one
    repository.

1.  A function body should include a reasonable amount of commenting to provide
    a broad idea of what is happening at different points within the function.

1.  If there are references to external sources in documenting comments, those
    should be consistently spread all over the project.

1.  It is highly recommended that version number and release date be included in
    every release.
