Para correr local: ng serve --port 4600
para firebase: firebase init 
               ng build --prod
               firebase deploy 
Para ver cambios en modo incognito porque se guarda en cache 
Las Directivas extienden la funcionalidad del HTML usando para ello una nueva sintaxis. Con ella podemos usar lógica que será ejecutada en el DOM (Document Object Model).
Directivas de Atributo
Alteran la apariencia o comportamiento de un elemento del DOM y son usados como atributos de los elementos
ngModel: Implementa binding
ngClass: permite añadir/eliminar varias clases
ngStyle: permite asignar estilos inline

Directivas Estructurales
Alteran la estructura del DOM, agregando, eliminando y manipulando los elementos host a los que están unidos.
ngIf: Nos permite incluir condicionales de lógica en nuestro código
ngFor: Permite ejecutar bucles, los bucles son los que conocemos en lógica de programación como: for, while, foreach, etc. 
ngSwitch: esta directiva es similar al *ngIf, y es como el switch en lógica de programación
ngPlural: es una directiva que permite agregar o remover elementos del DOM, basado en un valor númerico.
ngTemplate: esta directiva como su nombre lo indica es un template en Angular.
ngComponentOutlet: nos permite crear componentes dinámicos.


Los cinco principios de SOLID para el diseño de aplicaciones de software son: 

S – Single Responsability Principle (SRP) (Principio de responsabilidad única) 
componente o clase debe tener una responsabilidad única, sencilla y concreta

O – Open/Closed Principle (OCP) (Principio abierto / cerrado) 
 componentes del software deben estar abiertos para extender a partir de ellos, pero cerrados para evitar que se modifiquen

L – Liskov Substitution Principle (LSP) (Principio de substitución de Liskov) 
una subclase puede ser sustituida por su superclase

I – Interface Segretation Principle (ISP) (Principio de segregación de interfaz)
clientes no deben ser forzados a depender de interfaces que no utilizan

D – Dependency Inversion Principle (DIP) (Principio de inversión de dependencias) 
módulos de alto nivel no deben de depender de los de bajo nivel

swipper slash bonitos

para que js corra son 4 pasos: descargar, parse(Gramatica), compilar, ejecutar
se fragmenta para que corra mas rapido

flexbox grid

toolbar

Protractor es un marco de prueba de un extremo a otro para aplicaciones Angular y AngularJS. Protractorr ejecuta pruebas contra su aplicación que se ejecuta en un navegador real, interactuando con ella como lo haría un usuario.

Karma brinda un entorno de prueba productivo a los desarrolladores

TSLint es una herramienta extensible de análisis estático que verifica el código TypeScript para detectar errores de legibilidad, mantenibilidad y funcionalidad. (Quedo deprecado en el 2019). similar: Prettier

Cambiar la version de Node: 
Se desistala el actual Node
Descargar el binary 
descomprimirlo 
Copiar y pegarlo en ProgramFiles en C
Despues ir a las variables de entorno y agregar C:\ProgramFiles\nodejs\
node -v para confirmar la instalacion 