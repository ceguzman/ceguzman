<h1> Hi, I'm Carlos Guzman!  <img src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif" width="50"> </h1>

<img src="https://media.giphy.com/media/QTfX9Ejfra3ZmNxh6B/giphy.gif" width="230" align="right">

<p>
  <em> 
    <strong>Future Software Enginner </strong><img src="https://media.giphy.com/media/Me15eWDZ5AAeKH7TUm/giphy.gif" width="40">
  </br>
   <strong>Java Junior Developer </strong><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="40"> 
  </em>
  </br>  
</p>

<h3>About me</h3>
<p>I consider myself a person with a good performance in programming with a desire to learn, a good attitude for team and individual work, creative, responsible, honest, punctual and disciplined.

My strong programming language is JAVA with the following technologies JPA, Hibernate and Spring Boot (Framework). On the other hand, in the area of databases I use the MySQL and PostgreSQL engines.</p>

- <img src="https://media.giphy.com/media/XEDIHHp3i8bVoEdxd7/giphy.gif"> I am learning Angular 

```java
package carlos.me;

import java.time.LocalDate;
import java.time.Period;
import java.time.format.DateTimeFormatter;
import java.util.ArrayList;
import java.util.List;

public class Me {
    private String name;
    private int age;
    private String currentProfession;
    private List<String> languages = new ArrayList<String>();

    public Me() {
        this.age = getAge();
        this.name = "Carlos Guzman";
        this.currentProfession = "Java Junior Developer";
        this.languages.add("Java");
    }

    public int getAge() {
        DateTimeFormatter fmt = DateTimeFormatter.ofPattern("dd/MM/yyyy");
        LocalDate dateToday = LocalDate.now();
        LocalDate birthdate = dateToday.parse("02/05/2001", fmt);
        Period age = Period.between(birthdate, dateToday);
        return age.getYears();
    }

    public List<String> getLanguages() {
        return languages;
    }


    @Override
    public String toString() {
        return "Me{" +
                "name is ='" + name + '\'' +
                ",my age is =" + age +
                ", currentProfession is ='" + currentProfession + '\'' +
                ",My languages are =" + languages +
                '}';
    }
}
```

```java
package carlos.me;

public class App {
    public static void main(String[] args) {
        Me carlos = new Me();
        carlos.getLanguages().add("Html");
        carlos.getLanguages().add("Css");
        carlos.getLanguages().add("TypeScript");
    }
    /**
     * Me{name is ='Carlos Guzman',my age is =19, 
     * currentProfession is ='Java Junior Developer',
     * My languages are =[Java, Html, Css, TypeScript]}
     */
}    
```

[![Twitter: carlose96008362](https://img.shields.io/twitter/follow/carlose96008362?style=social)](https://twitter.com/carlose96008362)
[![Linkedin: carlose96008362](https://img.shields.io/badge/-carlos-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/carlos-esteban-guzman-baquero-012606199/)](https://www.linkedin.com/in/carlos-esteban-guzman-baquero-012606199/)
[![GitHub carlose96008362](https://img.shields.io/github/followers/ceguzman?label=follow&style=social)](https://github.com/ceguzman)

# My Skills

## Main programming language

[![Generic badge](https://img.shields.io/badge/Java-✓-brightgreen.svg?style=flat&logo=java&labelColor=black)](https://sdkman.io/)

## Other languages
[![Generic badge](https://img.shields.io/badge/HTML5-✓-brightgreen.svg?style=flat&logo=html5&labelColor=black)](https://developer.mozilla.org/es/docs/Web/HTML)
[![Generic badge](https://img.shields.io/badge/CSS-✓-brightgreen.svg?style=flat&logo=css3&labelColor=orange)](https://developer.mozilla.org/es/docs/Web/CSS)
[![Generic badge](https://img.shields.io/badge/JavaScript-✓-brightgreen.svg?style=flat&logo=javascript&labelColor=black)](https://javascript.info/)
[![Generic badge](https://img.shields.io/badge/TypeScript-✓-brightgreen.svg?style=flat&logo=typescript&labelColor=blue)](https://www.typescriptlang.org/docs/home.html)

### :minidisc: Database technologies & Structured Query Language
[![Generic badge](https://img.shields.io/badge/MySQL-✓-brightgreen.svg?style=flat&labelColor=black&logo=mysql)](https://www.mysql.com/)
[![Generic badge](https://img.shields.io/badge/Postgres-✓-brightgreen.svg?style=flat&labelColor=blue&logo=postgresql)](https://www.postgresql.org/)

### :pushpin: Other tools

[![Generic badge](https://img.shields.io/badge/GIT-✓-brightgreen.svg?style=flat&logo=git&labelColor=blue)](https://git-scm.com/)
[![Generic badge](https://img.shields.io/badge/Gitkraken-✓-brightgreen.svg?style=flat&logo=gitkraken&labelColor=black)](https://www.gitkraken.com/)
[![Generic badge](https://img.shields.io/badge/AWS-✓-brightgreen.svg?style=flat&logo=amazon-aws&labelColor=black)](https://aws.amazon.com/es/)
[![Generic badge](https://img.shields.io/badge/Windows-✓-brightgreen.svg?style=flat&logo=windows&labelColor=blue)](https://www.microsoft.com/es-co/windows)
[![Generic badge](https://img.shields.io/badge/Bash-✓-brightgreen.svg?style=flat&logo=gnu-bash&labelColor=black)](https://www.gnu.org/software/bash/manual/bash.html)
[![Generic badge](https://img.shields.io/badge/Eclipse-✓-brightgreen.svg?style=flat&logo=eclipse&labelColor=black)](https://www.eclipse.org/)
[![Generic badge](https://img.shields.io/badge/Vscode-✓-brightgreen.svg?style=flat&logo=visual-studio-code&labelColor=blue)](https://code.visualstudio.com/)
[![Generic badge](https://img.shields.io/badge/NetBeans-✓-brightgreen.svg?style=flat&logo=apache-netbeans-ide&labelColor=black)](https://netbeans.org/)
[![Generic badge](https://img.shields.io/badge/IntelliJ-✓-brightgreen.svg?style=flat&logo=intellij-idea&labelColor=red)](https://www.jetbrains.com/es-es/idea/)
[![Generic badge](https://img.shields.io/badge/WebStorm-✓-brightgreen.svg?style=flat&logo=webstorm&labelColor=orange)](https://www.jetbrains.com/es-es/webstorm/)

<p align = "center">
<img src="https://github-readme-stats-git-master.zephirorb.vercel.app/api?username=ceguzman&show_icons=true&theme=dracula&count_private=true&hide_title=false&hide=stars&line_height=29"/>

<img src="https://github-readme-stats-git-master.zephirorb.vercel.app/api/top-langs/?username=ceguzman&layout=compact&theme=dracula&card_width=250&hide=PureBasic,Ruby,TSQL,Papyrus,PLpgSQL&hide_title=false"/>
</p>
  


