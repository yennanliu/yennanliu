Coding: <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/></a> <a href="https://www.python.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.scala-lang.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/3/39/Scala-full-color.svg" alt="python" width="40" height="40"/> </a> <a href="https://nodejs.org/en" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg" alt="python" width="40" height="40"/> </a>

Others: <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a>  <a href="https://www.gcp.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="gcp" width="40" height="40"/> </a>  <a href="https://cloud.google.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Google_Cloud_logo.svg" alt="docker" width="40" height="40"/> </a> <a href="https://kafka.apache.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/0a/Apache_kafka-icon.svg" alt="aws" width="40" height="40"/> </a>   <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/f/f3/Apache_Spark_logo.svg" alt="aws" width="40" height="40"/> </a>  <a href="https://spark.apache.org/" target="_blank" rel="noreferrer">

CI/CD: <a href="https://www.jenkins.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/> </a>


```java
/** Heya this is Yen, I code backend for problem solving */

import io.reactivex.rxjava3.core.Observable;

public class MyStack {

    interface Skill {}

    static class BackendDevelopment implements Skill {
        String name;
        BackendDevelopment(String name) { this.name = name; }
    }

    static class DataEngineering implements Skill {
        String name;
        DataEngineering(String name) { this.name = name; }
    }

    static class SystemArchitecture implements Skill {
        String name;
        SystemArchitecture(String name) { this.name = name; }
    }

    public static Observable<String> run(Skill skill) {
        return Observable.create(emitter -> {
            if (skill instanceof BackendDevelopment) {
                emitter.onNext("build backend services with JVM, Python");
            } else if (skill instanceof DataEngineering) {
                emitter.onNext("big data, streaming, data platform development");
            } else if (skill instanceof SystemArchitecture) {
                emitter.onNext("system design, product ownership");
            } else {
                emitter.onNext("other awesome works");
            }
            emitter.onComplete();
        });
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
