# AL-Go Template
## Per Tenant Extension Project
This template repository can be used for managing Per Tenant Extensions for Business Central.

Please consult https://github.com/microsoft/AL-Go/#readme for scenarios on usage

```AL
pageextension 50000 CustomerListExt extends "Customer List"
{
    trigger OnOpenPage();
    begin
        Message('App published: Hello world!');
    end;
}
```
