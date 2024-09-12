# AI_Lab_2023-24
LAB EXPERIMENTS 
REQUIREMENTS 
1. PYHTON
2. SWI-PROLOG
3. PDDL 0R PDDL EDITOR ONLINE
4. JUPITER OR COLAB NOTEBOOK 

```
graph = {
    '5': ['3', '7'],
    '3': ['2', '4'],
    '7': ['8'],
    '2': [],
    '4': ['8'],
    '8': []
}

visited = set()  # Set to keep track of visited nodes of the graph.

def dfs(visited, graph, node):
    if node not in visited:
        print(node)
        visited.add(node)
        for neighbour in graph[node]:
            dfs(visited, graph, neighbour)

# Driver Code
print("Following is the Depth-First Search")
dfs(visited, graph, '5')
```
                                           
output:![WhatsApp Image 2024-08-19 at 15 13 01_8558ca71](https://github.com/user-attachments/assets/04e72250-86e3-437a-b886-cb5504260d49)


