

# Issues
1. FAILURE: Build failed with an exception.
```
* What went wrong:
Could not open settings generic class cache for settings file '/Users/rick/src/bitrise-android-demo-app/settings.gradle' (/Users/rick/.gradle/caches/7.6.2/scripts/ixp9hrbpzfmr5h8lc00jczsq).
> BUG! exception in phase 'semantic analysis' in source unit '_BuildScript_' Unsupported class file major version 67
```
Resolved: 
```
/usr/libexec/java_home -V
export JAVA_HOME=$(/usr/libexec/java_home -v 17)
```

2. commit push