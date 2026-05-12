# Proyecto Experto en materia laboral
Repositorio perteneciente a la materia Proyecto 1: Introducción a los Large Language Models

Planteamos para nuestro proyecto un LLM, experto en Derecho Laboral, al
que el usuario pueda realizarle consultas respecto a cuestiones que envuelven las
relaciones laborales. Algunos ejemplos de los posibles cuestionamientos son:
- Mi jefe me dijo que nos daba el d´ıa y a´un as´ı me lo descont´o, ¿Es eso legal?
- Me contrataron como t´ecnico de mantenimiento, pero me cobran por el uso de la herramienta ¿Hay algo que pueda hacer?


Para nuestro proposito, nuestra fuente primaria de informaci´on ser´a la Ley
Federal del Treabajo, texto disponible en linea en formatos PDF y .doc, adem´as
de apoyarnos en otras leyes tales como el C´odigo de Comercio, seg´un sea necesario. Naturalmente, ´estos textos pertenecen al dominio legal

Como arquitecura base, proponemos usar un encoder-only, tomando como
opción BERT Multilingüe, o un RAG multiagentico, pues, dado el
proposito de nuestro LLM, y como cualquier persona lo sabe, en derecho, el
contexto y la forma constituyen el fondo.

Como Baseline, esperamos que el modelo se comporte como cualquier persona ajena al ambito legal al tratar de leer una Ley, que sea capaz de relacionar
los cuestionamientos con los ariculos relacionados, pero no necesariamente ser´a
capaz de dar las respuestas adecuadas a los mismos.

Considero que este proyecto es importante por el simple hecho 
de que el mexicano promedio desconoce tanto sus derechos, 
como sus obligaciones en materia laboral, dando paso a un abuso 
constante y sist´emico en las relaciones laborales en las que se 
ve involucrado. Tener acceso facil a un experto en materia laboral,
podr´ıa ayudar a cambiar ´esta din´amica.



```text
├───data
│   ├───processed
│   └───raw
├───docs
├───models
└───notebooks
    └───.ipynb_checkpoints