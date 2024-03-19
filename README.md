# Use Java Package
This is a example trying to pull the Maven artifact published to public repository of GitHub packages. This is not working as GitHub currently
does not support downloading packages from a public repository without authentication. 

Interestingly packages https://github.com/cdivitotawela/example-java-package can be downloaded without any authentication via the browser but 
fails when it is configured via pom.xml or settings.xml files. All the references points to that it is not possible to download Maven artifacts
in GitHub packages without authentication.
