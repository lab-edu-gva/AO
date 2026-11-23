---
tipo: sesion
asignatura: AO
unidad: "UD1 - Instalación de Aplicaciones y Entornos de Trabajo Colaborativo"
numero_sesion: 12
fecha: 
duracion: 55
estado: preparado
resultado_aprendizaje: ['RA9']
criterios_evaluacion: ['RA9.f', 'RA9.g', 'RA9.h']
tags:
  - AO
  - UD1
  - alumnado
  - estudio
---

# Sesión 12 – Salvaguarda y recuperación de la información

> **Material de estudio del alumnado.** Esta sesión está preparada para su estudio y trabajo; su estado no implica que ya se haya impartido.

## 1. Objetivos de aprendizaje
Al finalizar esta sesión deberías ser capaz de explicar los conceptos desarrollados, aplicar el procedimiento guiado y resolver las actividades propuestas justificando tus decisiones.

## 2. Relación curricular
- **Unidad:** Instalación de Aplicaciones y Entornos de Trabajo Colaborativo.
- **Resultados de aprendizaje:** RA9.
- **Criterios trabajados:** RA9.f, RA9.g, RA9.h.

## 3. Contenidos y explicación teórica
# 1. Qué es una copia de seguridad
Una **copia de seguridad** (backup) es una copia de información que se conserva para poder recuperarla si los datos originales se pierden, dañan, modifican accidentalmente o quedan inaccesibles. No debe confundirse con sincronización: si un archivo se elimina o cifra y el cambio se sincroniza, también puede desaparecer o quedar dañado en los demás dispositivos.

# 2. Qué información proteger
Antes de copiar hay que identificar los datos importantes: documentos de trabajo, configuraciones, perfiles, bases de datos o archivos de proyecto. No siempre es necesario copiar toda la unidad. Se debe definir qué información se protege, con qué frecuencia, dónde se guarda y quién puede recuperarla.

# 3. Tipos de copia
- **Completa:** copia todos los datos seleccionados. Es sencilla de restaurar, pero requiere más tiempo y espacio.
- **Incremental:** copia los cambios desde la última copia realizada. Ahorra espacio, aunque la recuperación puede requerir varias copias.
- **Diferencial:** copia los cambios desde la última copia completa. Ocupa progresivamente más espacio hasta la siguiente completa, pero simplifica la restauración respecto a una cadena incremental.

# 4. Regla 3-2-1
Una recomendación habitual consiste en mantener tres copias de los datos, en dos tipos de soporte y una copia fuera de la ubicación principal. No es una garantía absoluta, pero ayuda a reducir riesgos por fallo físico, robo, incendio o ataque. La estrategia debe adaptarse al valor de los datos y a las políticas del centro.

# 5. Restauración
Restaurar significa recuperar datos desde una copia. Antes de restaurar se identifica qué versión es correcta, qué archivos se van a sobrescribir y si existe una copia del estado actual. La restauración debe probarse y documentarse. Una copia que nunca se ha probado puede estar incompleta o ser ilegible.

# 6. Recuperación ante incidencias
Si una aplicación deja de funcionar o se pierden datos, primero se delimita el problema y se evita escribir sobre el soporte afectado cuando exista riesgo de sobrescritura. Se consulta el procedimiento oficial, se selecciona una copia válida y se recupera en un entorno controlado. Si los datos son críticos o el caso supera las competencias, se escala.

# 7. Seguridad de las copias
Las copias pueden contener información sensible. Deben protegerse mediante permisos, cifrado cuando proceda, almacenamiento autorizado y control de acceso. No se deben subir documentos del centro a cuentas personales o servicios no aprobados.

## 4. Ejemplo práctico guiado
## Ejemplo guiado: recuperar un documento
1. Confirma qué archivo falta o está dañado y cuándo se detectó.
2. Evita sobrescribir la versión recuperable.
3. Localiza la copia autorizada y comprueba su fecha.
4. Identifica si la copia es completa, incremental o diferencial y qué cadena necesita.
5. Recupera el archivo en una ubicación temporal o controlada.
6. Abre el archivo y comprueba que su contenido es válido.
7. Compara con la versión actual y decide cuál conservar.
8. Registra origen, fecha de copia, archivo recuperado y resultado.

Nunca se restaura sobre el original sin comprobar antes el impacto.

## 5. Desarrollo temporal de la sesión (55 minutos)
| Tiempo | Trabajo |
|---:|---|
| 5 min | Presentación del objetivo y activación de conocimientos previos. |
| 20 min | Lectura y explicación razonada de los contenidos teóricos. |
| 15 min | Desarrollo del ejemplo práctico guiado. |
| 12 min | Realización de actividades y resolución de dudas. |
| 3 min | Síntesis final y comprobación de aprendizaje. |

## 6. Material necesario
- Equipo informático y sistema operativo disponible en el aula.
- Aplicación o documentación oficial relacionada con el contenido, cuando proceda.
- Cuaderno o documento digital para registrar observaciones y resultados.
- Entorno de pruebas autorizado. No realices instalaciones ni cambios de configuración sin permiso.

## 7. Material del alumnado: actividades
## Actividad 1. Tipo de copia
Explica qué tipo de copia elegirías para un equipo que cambia muchos archivos cada día y para un equipo que apenas modifica información. Justifica la decisión.

## Actividad 2. Plan 3-2-1
Diseña una estrategia de copia para los documentos de un pequeño despacho. Indica qué se copia, frecuencia, soportes, ubicación externa, responsables y pruebas de restauración.

## Actividad 3. Recuperación
Un usuario ha sobrescrito un documento importante. Describe las actuaciones que realizarías para intentar recuperarlo sin empeorar la situación.

## 8. Preguntas de repaso y preparación del examen
- ¿Qué diferencia existe entre copia de seguridad y sincronización?
- ¿Cómo se diferencian las copias completa, incremental y diferencial?
- ¿En qué consiste la regla 3-2-1?
- ¿Por qué es necesario probar las restauraciones?
- ¿Qué medidas protegen las copias frente a accesos no autorizados?

## 9. Resumen de estudio
En esta sesión se han trabajado los conceptos y procedimientos necesarios para comprender **salvaguarda y recuperación de la información**. Para preparar el examen, debes poder definir los términos principales, explicar por qué se realiza cada paso, identificar riesgos y justificar una actuación técnica adecuada. No memorices únicamente listas: relaciona cada decisión con el problema que evita o resuelve.

## 10. Autoevaluación
Marca cada afirmación cuando puedas realizarla sin consultar los apuntes:
- [ ] Puedo explicar los conceptos fundamentales de la sesión con vocabulario técnico correcto.
- [ ] Puedo describir el procedimiento práctico en el orden adecuado.
- [ ] Sé identificar errores habituales y explicar cómo prevenirlos.
- [ ] Puedo justificar mis decisiones en un supuesto profesional.
- [ ] He respondido las preguntas de repaso con mis propias palabras.

---
**Ruta en Obsidian:** `~/Docencia/02 - AO/UD1 - Instalación de Aplicaciones y Entornos de Trabajo Colaborativo/Sesiones/S12 - Salvaguarda y recuperación de la información.md`
