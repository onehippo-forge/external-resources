
# External Resource Project

The External Resource Project is an API that enables a developer to manage external resources in Hippo CMS, notably
It currently supports MediaMosa platform integration.

# Documentation 

Documentation is available at [bloomreach-forge.github.io/external-resources](https://bloomreach-forge.github.io/external-resources)

The documentation is generated by this command from the master branch:

 > mvn clean site:site -Pgithub.pages 
 
The output is in the ```/docs``` directory; push it and GitHub Pages will serve the site automatically. 

For rendering documentation on non-master branches, use the normal site command so the output will be in the ```/target``` 
and therefore ignored by Git.

 > mvn clean site:site

# Mediamosa API Javadoc

The separate Mediamosa API Javadoc is generated by this command from the mediamosa-api module:

 > mvn -Psite

The output is in the ```/mediamosa-api/docs/apidocs``` directory.
