# Snippets
Visual Studio Code Snippet to use make easy dispose object inside override dispose method


## To add the snippet into Visual Studo

Tools > Code Snippet Manager > MySnippets > Import

## To use it

- type in code ` disposeObjetc ` tab + tab

or

- ctrl + k , ctrl + x

Insert Isnippet > MySnippets > Dispose + tab 
  
Type objetct name and digit enter to change  ` ObjectToDispose ` with appropriate object to check if null then and dispose.
```
                    if (ObjectToDispose != null)
                    {
                        ObjectToDispose.Dispose();
                        ObjectToDispose = null;
                    } 
 ```
