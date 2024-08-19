# Stocks Sim

## Clonar el repositorio y configurar los submódulos

Para comenzar a utilizar el proyecto Stocks Sim, sigue los siguientes pasos:

1. Abre tu terminal y navega hasta el directorio donde deseas clonar el repositorio.

2. Ejecuta el siguiente comando para clonar el repositorio principal:

  ```shell
  git clone https://github.com/Krico16/stock-sim.git
  ```

3. Navega al directorio del repositorio clonado:

  ```shell
  cd stocks-sim
  ```

4. Inicializa y clona los submódulos utilizando el siguiente comando:

  ```shell
  git submodule update --init --recursive
  ```

<br>
  
## Actualizar los submódulos
  
  Si deseas actualizar los submódulos en el proyecto Stocks Sim, sigue estos pasos:
  
  1. Abre tu terminal y navega hasta el directorio del repositorio clonado:
  
    ```shell
    cd stocks-sim
    ```
  
  2. Para actualizar un submódulo específico, utiliza el siguiente comando:
  
    ```shell
    git submodule update --remote <nombre_del_submódulo>
    ```
  
     Reemplaza `<nombre_del_submódulo>` con el nombre del submódulo que deseas actualizar.
  
  3. Si deseas actualizar todos los submódulos al mismo tiempo, ejecuta el siguiente comando:
  
    ```shell
    git submodule update --remote --recursive
    ```
  
     Este comando actualizará todos los submódulos en el proyecto.
  
  Con estos pasos, podrás actualizar los submódulos en el proyecto Stocks Sim según tus necesidades.



Con estos pasos, habrás clonado el repositorio principal y configurado los submódulos necesarios para el proyecto Stocks Sim.

¡Ahora estás listo para comenzar a trabajar con el simulador de acciones!