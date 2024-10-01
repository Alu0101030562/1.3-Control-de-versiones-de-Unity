# 1.3-Control-de-versiones-de-Unity

Objetivo:Experimentar el control de versiones con Unity

## 1. Crear un proyecto Unity 3D básico con control de versiones en Unity. 

Lo primero será crear un nuevo proyecto y, antes de crearlo, debemos marcar la casilla de **Use Unity Version Control** para poder conectar nuestro proyecto con el sistema de control de versiones de Unity.

![Crear Proyecto](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.3ControlDeVersionesDeUnity/CreacionRepositorio.PNG)

## 2. Realizar 2 cambios, agregando 2 objetos 3D, por ejemplo, una esfera y un plano. Añadirles material de color rojo y azul respecivamente. Grabar el proyecto.

Tras haber creado el proyecto tendremos que añadir dos objectos a la escena, en este caso un plano y una esfera. Tras eso habrá que añadirles materiales de color azul y rojo respectivamente a los objetos añadidos.

![GameObject](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.3ControlDeVersionesDeUnity/GameObject%20en%20escena.PNG)

Una vez hecho eso guardamos los cambios para que se suban al repositorio. Para eso debemos añadir el mensaje y una vez añadido pulsamos el botón **check in changes**.

![Commit](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.3ControlDeVersionesDeUnity/commit%20gameObject.PNG)


## 3. Chequear los cambios en SCM

Para poder ver los cambios lo podemos hacer desde la propia interfaz de unity o desde unity cloud, lugar donde se guardan los repositorios con los que trabajamos.

![SCM](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.3ControlDeVersionesDeUnity/SCM.PNG)

## 4. Agregar un nuevo objeto, por ejemplo, un cilindro verde, guardar los cambios.

Ahora debemos agregar un objeto cilindro y asignarle un material de color verde, tras eso guardamos los cambios los cuales se reflejaran como un commit.

![gameObjectCylinder](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.3ControlDeVersionesDeUnity/gameobject%20cylinder.PNG)

![SCM2](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.3ControlDeVersionesDeUnity/SCM2.PNG)

## 5. Añadir una cápsula con una textura, agregar este cambio a una nueva rama.

Lo primero que tendremos que hacer sera crear una rama. Esta rama se llamará *develop* y estará centrada en los cambios de desarrollo. Para poder crearla debemos ir a la pestaña **branches** dentro de la parte de **Unity Version Control** y la creamos pulsando click derecho sobre la rama *main*. Unity nos da la posibilidad de hacer un **checkout** a la vez que creamos la nueva rama por lo que una vez creada nos dirigira automaticamente sobre esta y todos los cambios se haran en esta nueva rama.

![develop](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.3ControlDeVersionesDeUnity/rama%20develop.PNG)

Ahora debemos añadir un objeto de tipo capsula y, añadirle un material con textura, en este caso se han usado varias texturas para formar un material de tipo piedra.

![GameObjectSphere](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.3ControlDeVersionesDeUnity/gameObject%20capsula.PNG)

Una vez hecho, hacemos el commit para subir los cambios al repositorio

![SCM develop](https://github.com/Alu0101030562/Screenshots/blob/main/Screenshots/1.3ControlDeVersionesDeUnity/SCM%20develop.PNG)
