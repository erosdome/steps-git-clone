# Bitrise

## Git-clone

Clones a specified git repository to the desired local path

This Step is part of the [Open StepLib](http://www.steplib.com/), you can find its StepLib page [here](http://www.steplib.com/step/git-clone)

# Inputs
See step.yml


# How-Tos
- how to convert a file into Base64 on OSX: http://superuser.com/a/120815


# Best Practices
- add a new "bot" user to the repository you want to clone
-- and use this "bot" user's SSH key (or username&password, but SSH is preferred), _don't_ use your own, especially don't use your own username&password!
