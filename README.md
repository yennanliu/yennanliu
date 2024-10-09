Coding: <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/></a> <a href="https://www.python.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.scala-lang.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/3/39/Scala-full-color.svg" alt="python" width="40" height="40"/> </a> <a href="https://nodejs.org/en" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg" alt="python" width="40" height="40"/> </a>

Others: <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a>  <a href="https://www.gcp.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="gcp" width="40" height="40"/> </a>  <a href="https://cloud.google.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Google_Cloud_logo.svg" alt="docker" width="40" height="40"/> </a> <a href="https://kafka.apache.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/0a/Apache_kafka-icon.svg" alt="aws" width="40" height="40"/> </a>   <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/f/f3/Apache_Spark_logo.svg" alt="aws" width="40" height="40"/> </a>  <a href="https://spark.apache.org/" target="_blank" rel="noreferrer">

CI/CD: <a href="https://www.jenkins.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/> </a>


```scala
/** Heya this is Yen, I code backend for problem solving */

object SkillApp extends App {

  // Define a function to describe the skill
  def describeSkill(skill: Skill): String = skill match {
    case BackendDevelopment(name) => s"$name involves building backend services with JVM and Python."
    case DataEngineering(name)    => s"$name focuses on big data, streaming, and data platform development."
    case SystemArchitecture(name) => s"$name includes system design and product ownership."
    case _                        => "Other awesome skills!"
  }

  // Using the case classes
  val backendDev = BackendDevelopment("Backend Development")
  val dataEng = DataEngineering("Data Engineering")
  val sysArch = SystemArchitecture("System Architecture")
}
```

<!--
**yennanliu/yennanliu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
