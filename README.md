```
Backend development && Data engineering && system architecture
```

```scala

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
