# Proyecto Experto en materia laboral
Repositorio perteneciente a la materia Proyecto 1: Introducción a los Large Language Models



Planteamos para nuestro proyecto un LLM, experto en Derecho Laboral, al
que el usuario pueda realizarle consultas respecto a cuestiones que envuelven las
relaciones laborales. Algunos ejemplos de los posibles cuestionamientos son:
- Mi jefe me dijo que nos daba el día y aún as´ı me lo descontó, ¿Es eso legal?
- Me contrataron como técnico de mantenimiento, pero me cobran por el uso de la herramienta ¿Hay algo que pueda hacer?

Para nuestro proposito, nuestra fuente primaria de información será la Ley
Federal del Treabajo, texto disponible en linea en formatos PDF y .doc, además
de apoyarnos en otras leyes tales como el Código de Comercio, según sea necesario.
Naturalmente, ´estos textos pertenecen al dominio legal.

Como arquitecura base, proponemos usar un encoder-only, tomando como
opción BERT Multilingüe, o un RAG multiagentico, pues, dado el
proposito de nuestro LLM, y como cualquier persona lo sabe, en derecho, el
contexto y la forma constituyen el fondo.

Como Baseline, esperamos que el modelo se comporte como cualquier 
persona ajena al ambito legal al tratar de leer una Ley, que sea 
capaz de relacionar los cuestionamientos con los ariculos 
relacionados, pero no necesariamente será
capaz de dar las respuestas adecuadas a los mismos.

Considero que este proyecto es importante por el simple hecho 
de que el mexicano promedio desconoce tanto sus derechos, 
como sus obligaciones en materia laboral, dando paso a un abuso 
constante y sistémico en las relaciones laborales en las que se 
ve involucrado. Tener acceso facil a un experto en materia laboral,
podría ayudar a cambiar ésta dinámica.

## Estado del proyecto


| Fase | Estado |
|------|--------|
| Repositorio y estructura | ✅ ECompletado|  
| Curación del corpus | ⬜ Pendiente |
| Baseline (modelo sin fine-tuning) | ⬜ Pendiente |
| Fine-tuning | ⬜ Pendiente |
| Evaluación | ⬜ Pendiente |
| Deployment (HuggingFace Spaces) | ⬜ Pendiente |


##Papers 

```text
├───data
│   ├───processed
│   └───raw
├───docs
├───models
└───notebooks
    └───.ipynb_checkpoints
```

