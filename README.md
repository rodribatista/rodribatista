```java
public class WhoIAm {

  String user = "Rodrigo Batista";
  String education = "Software Developer - Backend Specialist";

  static String getCity() {
    return "Montevideo, Uruguay";
  }

  static Boolean isWorking() {
    throw new Error("Looking my first IT job opportunity");
  }

  void printSkills() {
    skills.forEach(System.out::println);
  }

}

public class Main {

  public static void main(String[] args) {

    WhoIAm myself = new WhoIAm();

    myself.printSkills();

  }

}
```

```bash
OUTPUT 'Main':

  Lenguajes: [ Java, Go, JavaScript (ES6), HTML5, CSS3, SQL, Bash ]

  Frameworks: [ Spring, React ]

  Protocolos: [ REST ]

  Bases de datos: [ MySQL, PostgreSQL, MongoDB ]

  Testing: [ JUnit, Jest, Selenium, RestAssured ]

  Cloud: [ Docker, AWS, IaC, CI/CD, Git ]

Process finished with exit code 0
```
