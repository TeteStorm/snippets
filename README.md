# Snippets
Visual Studio Code Snippet to use make easy dispose object inside override dispose method


## To add the snippet into Visual Studo

Download this repo

Tools > Code Snippet Manager > MySnippets > Import > Select  downloaded file Dispose.snippet

## To use it

- type in code ` disposeObjetc ` tab + tab

or

- ctrl + k , ctrl + x

Insert Isnippet > MySnippets > Dispose + tab 
  
Type object name than digit enter and it's done!
This step will change  ` ObjectToDispose ` with appropriate object to check if null then and dispose.
```
                    if (ObjectToDispose != null)
                    {
                        ObjectToDispose.Dispose();
                        ObjectToDispose = null;
                    } 
 ```
