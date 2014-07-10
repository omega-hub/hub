hub
===

Repository for the index of modules in omega-hub.

To add your own module, add it to the `CMakeLists.txt` file.

The format for module entries is

`module_def(<module name> <git repository url> <description>)`
- `module name` is a unique module name. The module will be downloaded into a directory with this name.
- `git repository url` the url of the git repository containing the module.
- `description` a string containing a short module description.
