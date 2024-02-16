Coding: <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/></a> <a href="https://python.com" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" alt="python" width="40" height="40"/> </a> <a href="https://scala.com" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/3/39/Scala-full-color.svg" alt="python" width="40" height="40"/> </a> <a href="https://nodejs.com" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg" alt="python" width="40" height="40"/> </a>

Others: <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a>  <a href="https://www.gcp.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="gcp" width="40" height="40"/> </a>  <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Google_Cloud_logo.svg" alt="docker" width="40" height="40"/> </a> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/0a/Apache_kafka-icon.svg" alt="aws" width="40" height="40"/> </a>   <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/f/f3/Apache_Spark_logo.svg" alt="aws" width="40" height="40"/> </a>  <a href="https://www.gcp.com/" target="_blank" rel="noreferrer">

CI/CD: <a href="https://www.jenkins.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/> </a>


```scala

/** Hellooo this is Yen, I build platforms for solving problems */

object myStack extends App {

  sealed trait Skill

  case class BackendDevelopment(name: String) extends Skill

  case class DataEngineering(name: String) extends Skill
  
  case class SystemArchitecture(name: String) extends Skill

  def run(name: Skill): String = name match {
  
    case BackendDevelopment(name) => "build backend services with JVM, Python"
    
    case DataEngineering(name) => "big data, streaming, data platform development"
    
    case SystemArchitecture(name) => "system design, product ownership"
    
    case _ => "other awesome works"
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
