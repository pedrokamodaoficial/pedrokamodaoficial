<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F89820,100:5382A1&height=180&section=header&text=Pedro%20Kamoda&fontSize=45&fontColor=ffffff&animation=fadeIn&fontAlignY=35"/>
<img src="https://readme-typing-svg.demolab.com/?lines=Java+Developer;Always+Learning;Python+%7C+C%23+%7C+JavaScript&font=Fira%20Code&center=true&width=500&height=45&color=F89820&vCenter=true"/>
</div>

## About me

Backend **Java** Developer with experience in **Spring** (Boot/Framework), **Docker**, and both **SQL** and **NoSQL** databases.
Currently studying **Computer Engineering**, applying my studies to building **REST API** projects that combine theory with real-world development practice.

[![LinkedIn](https://img.shields.io/badge/-PedroKamoda-blue?style=flat-square&logo=LinkedIn&logoColor=white)](https://www.linkedin.com/in/opedrokamoda/)
[![GitHub followers](https://img.shields.io/github/followers/pedrokamodaoficial?label=follow&style=social)](https://github.com/pedrokamodaoficial)

public class Developer {

    private String name = "Pedro Kamoda";
    private String role = "Backend Java Developer";
    private String degree = "Computer Engineering Student";

    private String[] skills = {
        "Java", "Spring Boot", "Spring MVC", "Spring Data",
        "Docker", "PostgreSQL", "MySQL",
    };

    private String currentFocus = "Building REST APIs";

    public String[] getGoals() {
        return new String[] {
            "Hexagonal CRUD in Java",
            "E-Players technic graduation project"
            "Good knowledge in Python, JavaScript and C#"
            "Always studying something new!"
        };
    }

    public static void main(String[] args) {
        Developer me = new Developer();
        System.out.println(me.name + " is coding...");
    }
}
