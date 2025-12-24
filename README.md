gradle-init-action
==================
[Build Init Plugin](https://docs.gradle.org/current/userguide/build_init_plugin.html)

```bash
gradle init \
  --type java-application \
  --dsl kotlin \
  --test-framework junit-jupiter \
  --package my.project \
  --project-name my-project  \
  --no-split-project  \
  --java-version 17
```

### TODOs
- [ ]  Append extra files to the generated project
- [ ]  Specify Gradle version
