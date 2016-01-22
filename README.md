# gocd-json-config-example
Example Go configuration repository with json configuration

## Server configuration

In order to import this configuration in your Go server.
1. Install json.config.plugin
2. Add this to your cruise-config.xml configuration:
```xml
<config-repos>
   <config-repo plugin="json.config.plugin">
     <git url="https://github.com/tomzo/gocd-json-config-example.git" />
   </config-repo>
</config-repos>
```

## Notes

This is suited to run on development server. The `dev` environment declares `up42` as pipeline members.
If you don't have `up42` pipeline defined in cruise-config.xml then add one.
