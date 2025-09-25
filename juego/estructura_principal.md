# Estructura del programa

## 1. Inicializar tratamiento
- Mensaje de bienvenida
  - Si no quiere jugar se salta al final
- Crear el mapa
- Crear detective
## 2. Inicializar adquisición
- Situar al detective en la primera sala
## 3. Obtener elemento siguiente
- Cambiar de sala:
  - *MostrarOpcionesSalida*
  - Actualizar la sala
## 4. Tratar elemento
Realizar acciones en la sala
- hablar con el personaje
- ver el objeto de la sala
- apuntar la información en la libreta
- Si el detective cree que ha descubierto al asesino llama a acusar

## 5. Finalizar tratamiento
El método acusar ha dado un resultado correcto

## Métodos

**MostrarSala**(List<Sala> salas, string nombreSala)
// Muestra por consola el nombre de la sala, del personaje y del objeto
// Si la sala no existe se envía un mensaje de error

**MostrarOpcionesSalida**(int x, int y)
// Muestra los movimientos posibles a hacer desde esa habitación
