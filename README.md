
# 🫧 Stack Overflow Rust Tag Data Analysis Demo

![CourseInfo](https://img.shields.io/badge/sustech--cs209-23sp%3Aproject--demo-brightgreen)![License](https://img.shields.io/github/license/hezean/chatting)

This is a simple Stack Overflow `rust` tag data analysis demo, based on the SpringBoot web framework.

## Demo Introduction

This repository is just a very simple demo, I am sure you need more content and more beautiful views to get a good grade.

The data used in the demo is based on Stack Overflow `rust` tags, so it cannot be directly applied to your final project (although the sample charts may be modified and used).

This demo is a SpringBoot project with Maven as the package manager. The project uses SpringBoot version 2.7.10 (not recommended to use SpringBoot 3), and the default JDK version is 17. In addition, the thymeleaf template engine ([see the documentation for more details](https://www.thymeleaf.org/)) is imported for page rendering. The frontend and backend of this demo are not separated (you can create a separate front-end and back-end project), and the frontend uses HTML, CSS, and Javascript (you can use Vue, React, or other front-end frameworks). The echarts framework for generating wordcloud and piechart is imported via CDN ([see the documentation for more details](https://echarts.apache.org/en/index.html)).

## How to Run the Demo

If you want to use this demo as the beginning of your final project, Click the [use template](https://github.com/SnowCharmQ/2023-Spring-Java2-Project-Demo/generate) to create a fork of this template - to avoid potential plagiarism disputes, **please be sure that your repository is made _private_ before the deadline**. But I recommend you start from **create a new project** (it will help you get more familiar with SpringBoot).

You need to then clone your repository into your local machine. You can then open the whole folder as a project in your IDE - it will recognize the SpringBoot Application structure and automatically configure the project.

![](https://i.imgur.com/qCKayU0.png)

#### IDEA

Once you enter your project, if your IDEA is "smart" enough, it will configure your project automatically. After indexing, you can simply run the main function in **src->main->java->cse->java2->project->Application.java**. If your IDEA is not "smart" enough, you can follow the tutorial in [Assignment 2](https://github.com/hezean/chatting), then you can run the application.

If you see the result below, congratulations!:tada:

![](https://i.imgur.com/1FWvFof.png)

#### Terminal

Now, the first thing you need to do is to install your local Maven project.

```
mvn install
```

After executing the command, you can simply run the application in your terminal.

```
mvn spring-boot:run
```

If you see the result below, congratulations!:tada:

![](https://i.imgur.com/4sBwTsD.png)

If you get an error like below, it means your 9090 port is already in use, you can change the port in **src->main->resources->application.properties**.

![](https://i.imgur.com/zMg1v57.png)

If you get other errors, fill free to ask us for help :)

## How to See the Result

You can visit localhost:9090 or localhost:9090/demo (based on your port number) to see the demo result.

![](https://i.imgur.com/PQLvjaS.png)

The demo is so simple, and we look forward to your creative ideas :)

## More Information

If there's anything ambiguous about the document or the instruction above, feel free to [open an issue](https://github.com/SnowCharmQ/2023-Spring-Java2-Project-Demo/issues/new) and ask. Your question may also help others to better understand this assignment 🔥

## License

This project is licensed under the MIT License - see the LICENSE file for details.
