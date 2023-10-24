```java
public class WhoIAm {

  public String user = "Rodrigo Batista";

  public String title = "Software Developer";

  public String[] nextGoals = {
    "Finish Backend Specialist studies",
    "Learn NodeJS and Typescript"
  };

  public static String getCity() {
    return "Montevideo, Uruguay";
  }

  public Boolean isWorking() {
    throw new Error("Looking my first IT job opportunity");
  }

  public void printSkills() {
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
TERMINAL OUTPUT 'Main':

  Languages: [ Java, Go, JavaScript (ES6), HTML5, CSS3, SQL, Bash ]

  Frameworks: [ Spring, React ]

  Protocols:: [ REST ]

  Databases: [ MySQL, PostgreSQL, MongoDB ]

  Testing: [ JUnit, Jest, Selenium, RestAssured ]

  Cloud: [ Docker, AWS, IaC, CI/CD, Git ]

Process finished with exit code 0
```
