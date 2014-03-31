# `{cmd} [name] [description] [options]`

Creates a new project. Will write the project to a folder called
  `name` in the current working directory.

Example:

`{cmd} new-project 'new description of project'`

Options:
    --template=[str]        Which template to use
    --directory=[str]       Which directory templates live in.
    --name=[str]            Set name of project
    --description=[str]     Set description of project

 - `--template` defaults to `uber`
 - `--directory` defaults to `uber-ngen/templates` folder


## `{cmd} --help`

Prints this message