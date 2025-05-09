# Maths for Chemists

Welcome to the repository for the Maths for Chemists resource. 
To see the built resource, please access the following link [pythoninchemistry.org/maths-for-chemists](http://pythoninchemistry.org/maths-for-chemists).
As detailed on the resource itself, this is a reworking of an existing resource prepared by Allan Cunningham and Rory Whelan (supported by Michael Grove, Joe Kyle, and Samantha Pugh) and currently [hosted by the Royal Society of Chemsitry](https://edu.rsc.org/download?ac=15395). 
The aim of this reworking is to make the material more accessible and add Python coding examples of the mathematical methods in the resource. 

## Contributing

We actively welcome contributors to this project. 
The aim is to rewrite the original Maths for Chemists booklet, adding examples of Python code where relevant. 
We suggest that you compare this resource to the original to get an idea of what that means.
So if you want to write a section, please feel free. 

So that we don't duplicate effort, there are issues for each chapter subsection associated with the GitHub repository. 
If you want to write a specific section, please comment on the relevant issue so it is clear you are working on it. 
To try and emulate some of the formatting from the source materials, we have created special admonitions for the Example and Chemistry Example boxes. 
These can implements with the following:

````{markdown}
```{admonition} Example
:class: Example
Details of the example. Blah, blah. 
```
````

And 

````{markdown}
```{admonition} Van der Waals Equation
:class: chem
Information about a chemistry relevant example. 
```
````

For adding Python, we ask that the Python section is demarcated with horizontal lines:

```{markdown}
<hr>

print('Hello World!)

<hr>
```

Generally, the Python does not necessarily require explanation, in terms of *how* Python works. 
Just give it some context if necessary. 
However, if you really want to include some additional commentary, please use the Python Note admonition: 

````{markdown}
```{admonition} Python Note
:class: python
Perhaps some information about an interesting library?
```
````