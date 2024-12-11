# Comandos de git

* ![Creacion de un repositorio](https://github.com/TadeoCastllo/Ahorcado/blob/main/comandos.md#comandos-de-git)
* ![Codigo en python]()
* ![Imagen](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQyzGL-llljdhSbqyiWNiDq1Xj1KcOpGWHRQg&s)
## Creacion de un repositorio

Para crear un repositorio usar el comando `git init`, enseguida un ejemplo:

```bash
$ git init
ayuda: Usando 'master' como el nombre de la rama inicial. Este nombre de rama predeterminado
ayuda: está sujeto a cambios. Para configurar el nombre de la rama inicial para usar en todos
ayuda: de sus nuevos repositorios, reprimiendo esta advertencia, llama a:
ayuda: 
ayuda: 	git config --global init.defaultBranch <nombre>
ayuda: 
ayuda: Los nombres comúnmente elegidos en lugar de 'master' son 'main', 'trunk' y
ayuda: 'development'. Se puede cambiar el nombre de la rama recién creada mediante este comando:
ayuda: 
ayuda: 	git branch -m <nombre>
Inicializado repositorio Git vacío en /home/salas/Documentos/git/.git/
```
## Codigo en python
```python
class_names = ['airplane', 'automobile', 'bird', 'cat', 'deer',
               'dog', 'frog', 'horse', 'ship', 'truck']

plt.figure(figsize=(10,10))
for i in range(25):
    plt.subplot(5,5,i+1)
    plt.xticks([])
    plt.yticks([])
    plt.grid(False)
    plt.imshow(train_images[i])
    # The CIFAR labels happen to be arrays, 
    # which is why you need the extra index
    plt.xlabel(class_names[train_labels[i][0]])
plt.show()
```
<img src ="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQyzGL-llljdhSbqyiWNiDq1Xj1KcOpGWHRQg&s">


## Lista de comandos git
| Comando de git | Descripción                                      | Ejemplo  |
|----------------|--------------------------------------------------|----------|
| git init       | Creación de un repositorio                       | git init |
| git pull       | Obtención de la última version de un repositorio | git pull |
