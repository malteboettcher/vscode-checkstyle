# Checkstyle extension for Visual Studio Code

## Prerequisites

* Please make sure Java is in system ```PATH```

## Options
```
{
    "checkstyle.jarPath": "[file path to the checkstyle jar file]",
    "checkstyle.configPath": "[file path to the checkstyle rule config file]"
}
```

* ```checkstyle.jarPath``` - Path to the checkstyle jar file. By default, the extension will use [checkstyle-8.4-all.jar](https://sourceforge.net/projects/checkstyle/files/checkstyle/8.4/)
* ```checkstyle.configPath``` - Path to the checkstyle rule config file. By deefault, the extension will use [google_checks.xml](https://github.com/checkstyle/checkstyle/blob/master/src/main/resources/google_checks.xml)

## License
[MIT](LICENSE.md)