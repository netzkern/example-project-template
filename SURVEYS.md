Your are able to create an interactive survey before your template is proceed. The results can be used as template variables.

**butler-survey.yml**
```yml
questions:
  - type: input
    name: drink
    message: "What is your favorite drink?"
    help: "Allowed character 0-9, A-Z, _-"
    required: true
```

**Access**
```
butler{getSurveyResult "drink"}
```

If you add a `multiselect` question your result will be joined with `,`
