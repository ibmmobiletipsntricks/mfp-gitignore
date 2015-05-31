mfp-gitignore
=============

This is an unofficial repository providing an initial/template `.gitignore`
file for an [IBM MobileFirst Platform
Foundation](http://www-03.ibm.com/software/products/en/mobilefirstfoundation)
Project. There is **no** official IBM support for these artifacts. 
We are attempting to follow the same principles as GitHub's own
[gitignore project](https://github.com/github/gitignore). We will gladly
accept any pull request with corrections or clarifications (especially
explanatory comments).

Usage
-----

1. Include the contents of the appropriate `<VERSION>.gitignore` file in your `.gitignore` file, located at the root of your MFP project.
1. MFP requires some directories to be present, but Git does not check in empty directories.  `.gitkeep` files ensure these directories are present when developers clone the Git repository.  `.gitkeep` files should be created in the following directories:
  1. `server/java`
  2. `adapters/ADAPTER_NAME/lib` (for all **Java** adapters)

*Note*: Prior to version 6.3, IBM MobileFirst Platform Foundation was known as
[IBM Worklight
Foundation](http://www-03.ibm.com/software/products/en/worklight-foundation),
so there are equivalent `.gitignore` files here for versions 6.1 and 6.2. This
repository was formerly known as `worklight-gitignore`.
