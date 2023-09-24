# hw2_mini_internet

https://cdn-uploads.piazza.com/paste/l78dcjpoj615ed/59d96dd159ba1094a7b22833e823fcbca915783586cb05a1bb38fc1b9c4a649f/DS_561-HW_2.pdf

## Python Commands
Running Python lint to check style
```
pylint pagerank.py 
```

Lint code
```
black pagerank.py
```

Make a virtual environment and run it in fish
```
python3 -m venv env
source venv/bin/activate.fish
```

## Regex
Running regex.compile to prevent making regex objects again anad again 
```
re.compile(str)
```

## Numba
Use numba only on static classes and do not pass in complex data types into the function or call them in the array

## Logic
- Make an adjacency matrix of the graphs where the rows are the nodes and the columns are the edges
- Compute the outgoing and incoming edges of each node
- in each iteration, get the pagerank for each node 
- check if the pagerank is converging
