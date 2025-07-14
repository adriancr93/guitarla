# React + Vite

Statements

En javascript

Una app de JS es una serie de statements, cada statement es una instruccion para hacer algo

Algunos statements son:
   Creacion de Varaiables
   Codigo condicionales con if
   Lanzar errores con throw new Error()
   Iterar con While o For


Expressions

Una expressions es algo que produce un valor.

Algunas Expressions son:
   Ternarios
   Utilizar una Array Method que genere una nuevo Array.
   .map que genera un nuevo array a diferencia de forEach

Props en React

Compartir informacion entre Componentes

Que son los Props?

Los componentes de React utilizan Props para comunicarse entre ellos. Puedes pasarle informacion de un componente padre al hijo por medio de estos props.

Los props se parecen a los atributos en HTML, pero puedes pasarle arryas, objetos o funciones.

Los Props se pasan del padre al hijo, nunca se pueden pasar del hijo al padre

Los Props se pasan desde el Padre hacia el hijo

Si tienes un state que se va a pasar por diferentes componentes, lo mejor es colocarlo en el archivo principal.

Cada Nivel de Componentes debera tomar y pasar el Prop hacia otros componentes, tecnologias como Redux, Zustand, Jotai o Context evitan tener que hacerlo de esta forma.

Eventos en React

Sobre los eventos en React

La forma en que React maneja los eventos es muy similar a como lo hace Javascript de froma nativa con algunos cambios.

Los eventos son camelCase, es decir en lugar de onchange se utiliza onChange, en lugar de onclick se utiliza onClick

Tambien a diferencia de JS y HTML, donde se coloca el nombre de la funcion en un string en React(JSX) se utiliza la funcion entre llaves{}

Crear tus propios

Hooks

Existe una gran ventaja de crear tus propios Hooks y es la de incorporar State y otros Hooks de React a tu propio codigo para poderlo re-utilizar en otros proyectos.

Otra gran ventaja es la de organizar tu codigo, de esa froma el hook se encarga de toda la logica del state mientras que tus componentes solo de mostrar la informacion.

Ventaja
De crear tus propios Hooks

Tu Codigo personalizado tendra todas las ventajas de React como son: state, effects, integrar otros hooks y el performance.

Re-utilizable en otros proyectos.

Facul de escribir pruebas.

Como crear tus propios Hooks?

Los hooks son funciones de JavaScript pero tienen algunas reglas.

Tus hooks deben seguir la convencion de react use{hook} de esta forma React escanea tu codigo en busqueda de posibles problemas con las Reglas de los Hooks.

Un Hook usualmente solo debe tener logica y no presentacion (para eso es un componente)

