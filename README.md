# cdto

A npm package to make navigating to projects in the command line easier

## Commands

```shell
-a: add
--name: name of project
--path: path of project
```

## Example

Basic use case adds the current directory to the proect name

```shell
cdto -a projectname
```

Allows user to specify a project and its path.

```shell
cdto -a --name=projectname --name=*pathtoproject*
```

Removes a project.

```shell
cdto -r projectname
```

## TODO

1) Add Windows & Linux Options
2) Add Command to Edit Project Paths
3) Add Options to Change Terminal Location

## Knwon Issues

* Sometimes new terminal windows cannot read the sqlite databse
    * Researching more efficient ways to store projects
* Sometimes name is null
* Windows does not end previous process until new window is closed or original window is closed
