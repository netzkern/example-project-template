# Projekt butler{ .Project.Name }

[Here](https://golang.org/pkg/text/template/) you can find an overview about all template features. We use a unique delimiter to avoid collsion with existing template engines.

## Delimiter

```
butler{ .Project.Name }
```
<b>Default variables</b>
<br>
butler{ .Project.Name }
<br>
butler{ .Project.Description }
<br>
Date: butler{ .Date }
<br>
Year: butler{ .Year }
<br>
<b>Custom variables</b>
<br>
Company: butler{ .Vars.company }
<br>
Email: butler{ .Vars.email }
<br>
<b>Helper functions</b>
<br>
butler{ toCamelCase .Project.Name }
<br>
butler{ toPascalCase "foo-bar" }
<br>
butler{ toSnakeCase "foo-bar" }
<br>
<a href="mailto:butler{ .Vars.email }">Contact</a>
