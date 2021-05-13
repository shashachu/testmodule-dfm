# Test Module DFM Bug

Sample project demonstrating a bug with test modules and dynamic feature modules

Repro:
```
./gradlew :app:testmodule:assembleDebug
```

Output:
```
* What went wrong:
Execution failed for task ':app:testmodule:processDebugManifest'.
> Failed to calculate the value of task ':app:testmodule:processDebugManifest' property 'testedApplicationId'.
   > Collection has more than one element.
```