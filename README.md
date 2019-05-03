# gocd-json-config-example

Example GoCD configuration repository with json configuration.

## Server configuration

In order to import this configuration in your Go server.
1. Install json.config.plugin
2. Add this to your cruise-config.xml configuration:
```xml
<config-repos>
   <config-repo pluginId="json.config.plugin" id="gocd-json-config-example">
     <git url="https://github.com/tomzo/gocd-json-config-example.git" />
   </config-repo>
</config-repos>
```
