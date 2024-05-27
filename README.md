# Analyse et Conception des Algorithmes

## Aperçu

Ce projet fournit des outils et des fonctions pour l'analyse et la conception des algorithmes. Il comprend des fonctionnalités pour visualiser des graphes non orientés et orientés, ainsi que pour créer des animations pour des algorithmes tels que la traversée BFS.

## Table des matières

1. [Installation](#installation)
2. [Utilisation](#utilisation)
3. [Contributions](#contributions)
4. [Licence](#licence)

## Installation

Pour utiliser ce projet, assurez-vous que Matplotlib est installé. Sinon, installez-le à l'aide de pip :
```python
pip install --upgrade matplotlib
```


## Utilisation

Partie 1: Afficher un Graphe Non Orienté
Pour afficher un graphe non orienté, utilisez la fonction plot_undirected_graph 

```python
# Example usage
edges = [((0, 1), (1, 2)), ((0, 1), (1, 0)), ((1, 2), (1, 0)), ...]
node_labels = { (0, 1): 'A', (1, 2): 'B', ... }
plot_undirected_graph(edges, node_labels)
```

Partie 3: Créer une Animation pour le Parcours BFS
Pour créer une animation pour la traversée BFS, utilisez la fonction animate_bfs :

```python
# Example usage
edges = [('A', 'B'), ('A', 'C'), ('B', 'C'), ...]
animate_bfs(edges, start_node='A')
```

## Contributions

Les contributions sont les bienvenues ! Veuillez suivre ces étapes :

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/fooBar`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some fooBar'`).
5. Push to the branch (`git push origin feature/fooBar`).
6. Create a new Pull Request.

## Licence
Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE)pour plus de détails.

