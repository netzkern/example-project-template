# Projekt butler{ .Project.Name }

[Here](https://golang.org/pkg/text/template/) you can find an overview about all template features. We use a unique delimiter to avoid collision with existing template engines. We use a unique delimiter to avoid collsion with existing template engines.

## Delimiter

```
butler{ .Project.Name }
```

butler{ .Project.Description }
<br>
Date: butler{ .Date }
<br>
Year: butler{ .Year }
<br>
Company: butler{ .Vars.company }
<br>
Email: butler{ .Vars.email }


<a href="mailto:butler{ .Vars.email }">Contact</a>
