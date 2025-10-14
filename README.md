### Hi there 👋


```kotlin
data class MyProfile(
     val pronouns: String = "he|him",
     val askMeAbout = listOf(
       "Kotlin", "Compose",
       "Swift", "Typescript"
     ),
     val currentlyLearning: List<String> = listOf(
        "Compose Multiplatform", "React Native", "Data Science", "Swift"
     ),
     val toLearn = {
       "KMM" to "Fun"
     }
     (0..end).reduce { acc, new ->
        study(new)
        coding(new)
        sumUp(acc) + haveFun(new)
     }
)
```

