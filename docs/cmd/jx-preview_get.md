## jx-preview get

Display one or more Previews

***Aliases**: list*

### Usage

```
jx-preview get
```

### Synopsis

Display one or more preview environments.

### Examples

  # List all preview environments
  jx-preview get
  
  # View the current preview environment URL
  # inside a CI pipeline
  jx-preview get --current

### Options

```
  -c, --current   Output the URL of the current Preview application the current pipeline just deployed
  -h, --help      help for get
```

### SEE ALSO

* [jx-preview](jx-preview.md)	 - Preview commands

###### Auto generated by spf13/cobra on 16-Apr-2021
