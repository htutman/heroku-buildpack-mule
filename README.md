Heroku buildpack for Mule 4
=========

The buildpack expects Mule jar files to be presented inside `build/` directory of the project. All jar files are copied into the `apps/` directory inside Mule's home before the Mule server is started.
