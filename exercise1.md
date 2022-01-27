When writing code in kotlin, we often use IDEs such as IntelliJ IDEA, Eclipse and Android Studio which have integrated lint tools. There is also a tool called ktlint which can format our codes when using code editors.

JUnit is the first testing framework that comes to my mind. Others are Spek and KotlinTest. 

Gradle is the most commonly used build tool in Kotlin. It provides a Kotlin DSL which is used by default when generating a Kotlin project, so this is the recommended choice. Another choice is Maven.

CircleCI, TeamCity and Travis CI are tools for continuous integration besides Jenkins and GitHub Actions.

Cloud-based CI tools are an easier choice compared to self-hosted tools because they have configured hardware and default configurations so you can use them out of the box. When we know a little about CI or we just want it works, cloud-based CI is a wise choice with simplicity and stability.

Self-hosted tools have more flexibility, especially for some large projects. Full control of the system and faster processing are the strengths of self-hosted CI tools.

So when deciding on using which CI tool, we need to confirm whether it can meet our needs mentioned above.