**Coding Languages:** <a href="https://www.java.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/></a>, <a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" alt="python" width="40" height="40"/></a>, <a href="https://www.scala-lang.org/" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/3/39/Scala-full-color.svg" alt="scala" width="40" height="40"/></a>, <a href="https://nodejs.org/en" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg" alt="nodejs" width="40" height="40"/></a>

**Cloud & Tools:** <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/></a>, <a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/></a>, <a href="https://cloud.google.com/" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Google_Cloud_logo.svg" alt="gcp" width="40" height="40"/></a>, <a href="https://kafka.apache.org/" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/0/0a/Apache_kafka-icon.svg" alt="kafka" width="40" height="40"/></a>, <a href="https://spark.apache.org/" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/f/f3/Apache_Spark_logo.svg" alt="spark" width="40" height="40"/></a>

**CI/CD:** <a href="https://www.jenkins.io" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/></a>


```scala
/** Heya this is Yen, I code backend for problem solving */

sealed trait Skill {
  def description: String
}

case class BackendDevelopment(name: String) extends Skill {
  def description: String = s"$name involves building backend services with JVM and Python."
}

case class DataEngineering(name: String) extends Skill {
  def description: String = s"$name focuses on big data, streaming, and data platform development."
}

case class SystemArchitecture(name: String) extends Skill {
  def description: String = s"$name includes system design and product ownership."
}

object SkillApp extends App {
  val skills: List[Skill] = List(
    BackendDevelopment("Backend Development"),
    DataEngineering("Data Engineering"),
    SystemArchitecture("System Architecture")
  )

  skills.foreach(s => println(s.description))
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
