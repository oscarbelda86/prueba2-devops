# prueba2-devops

El presente proyecto tiene por objetivo subir una imagen Docker a un contenedor en AWS ECR, implemententando un flujo CI-CD para una aplicación simple escrita en node.js. 
Ciertas consideraciones:

- se utiliza ubuntu 22.04 para evitar usar latest, por posibles problemas de compatibilidad a futuro.
- Se guardaron ciertos secretos por seguridad.
- El workflow tiene dos etapas: una de build y otra de deploy. Esto principalmente por temas de orden.
