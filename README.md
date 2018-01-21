# Projekt butler{ .Project.Name }

[Here](https://golang.org/pkg/text/template/) you can find an overview about all template features. We use a unique delimiter to avoid collision with existing template engines. We use a unique delimiter to avoid collsion with existing template engines.

## Delimiter

```
butler{ .Project.Name }
```
<b>Default variables</b>
<br>
butler{ .Project.Description }
<br>
Date: butler{ .Date }
<br>
Year: butler{ .Year }
<br>
Company: butler{ .Vars.company }
<br>
Email: butler{ .Vars.email }
<br>
<b>Helper functions</b>
<br>
butler{ toCamelCase .Project.Name }

<a href="mailto:butler{ .Vars.email }">Contact</a>
