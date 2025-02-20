# Polimorfismo
Principio de diseño Grasp - Polimorfismo

🔴 Reto: Código que Incumple el Principio de Polimorfismo en GRASP

📌 Enunciado del Reto
El siguiente código no sigue el principio de polimorfismo en GRASP, ya que usa condicionales para diferenciar el comportamiento de cada tipo de vehículo, en lugar de delegar la responsabilidad a las clases correspondientes mediante herencia y sobreescritura.

📌 Problema del código:
La clase VehiculoManager depende directamente de los tipos de vehículos
Fuerte acoplamiento: La clase VehiculoManager depende directamente de las implementaciones concretas.
Dificultad para escalar: Si agregamos más tipos de vehículos (como Motocicleta), tendremos que modificar el código existente.
Falta de polimorfismo: En lugar de aprovechar la herencia y la sobreescritura, se usan condicionales para determinar el comportamiento de cada tipo de vehículo.
