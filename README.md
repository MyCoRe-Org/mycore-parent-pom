# MyCoRe Parent POM

The MyCoRe Parent POM provides a shared Maven configuration for all MyCoRe modules.
It defines common plugin setups, dependency and plugin versions, and project metadata (licenses, mailing lists, CI settings) to keep builds consistent across the ecosystem.
By centralizing these settings, it reduces duplication and simplifies maintenance for all MyCoRe projects.

## How to use it

In your module’s pom.xml, declare this parent:
```xml
<parent>
<groupId>org.mycore</groupId>
<artifactId>mycore-parent</artifactId>
<version>[version number]</version>
</parent>
```
## Which version do I need

| MyCoRe Version | Parent Version | Comment                                                       |
|----------------|----------------|---------------------------------------------------------------|
| main           | 58-SNAPSHOT    | https://github.com/MyCoRe-Org/mycore/blob/main/pom.xml        |
| 2025.06        | 58-SNAPSHOT    | https://github.com/MyCoRe-Org/mycore/blob/2025.06.x/pom.xml   |
| 2024.06        | 57             | https://github.com/MyCoRe-Org/mycore/blob/2024.06.x/pom.xml   |
| 2023.06        | 57             | https://github.com/MyCoRe-Org/mycore/blob/2023.06.x/pom.xml   |
| 2022.06        | 51             | https://github.com/MyCoRe-Org/mycore/blob/2022.06.x/pom.xml   |
| 2021.06        | 48             | https://github.com/MyCoRe-Org/mycore/blob/2021.06.x/pom.xml   |
| 2020.06        | 45             | https://github.com/MyCoRe-Org/mycore/blob/2020.06.x/pom.xml   |
| 2019.06        | 42             | https://github.com/MyCoRe-Org/mycore/blob/2019.06.x/pom.xml   |
| 2018.06        | 38             | https://github.com/MyCoRe-Org/mycore/blob/2018.06.0.x/pom.xml |
