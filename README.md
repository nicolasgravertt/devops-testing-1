# Pruebas API Reservas

Este repositorio contiene una pequeña API de reservas desarrollada en Python. Se implementaron pruebas automatizadas utilizando `pytest`, siguiendo buenas prácticas de desarrollo y automatización con GitHub Actions.

## 🧪 Preguntas de reflexión sobre pruebas

### ✅ ¿En qué se diferencia Agile Testing del enfoque tradicional?

Agile Testing se integra desde el inicio del desarrollo, permitiendo validar funcionalidades en ciclos cortos e iterativos. A diferencia del enfoque tradicional (Waterfall), donde las pruebas se realizan al final, en Agile los testers colaboran activamente con el equipo de desarrollo, detectando errores más temprano y adaptándose a cambios frecuentes.

### ✅ ¿Qué ventajas viste al usar TDD? ¿Qué te costó más?

Las principales ventajas de usar TDD fueron:
- Mayor claridad en los requisitos funcionales antes de escribir el código.
- Reducción de errores en etapas tempranas.
- Diseño de código más limpio y modular.

Lo más desafiante fue cambiar el enfoque mental: pensar primero en los tests antes que en la implementación, lo cual requiere práctica y disciplina.

### ✅ ¿Qué tipo de prueba crees que más valor aportó hoy?

Las pruebas de unidad fueron las más valiosas, ya que permitieron validar funciones críticas como la verificación de disponibilidad sin necesidad de levantar toda la aplicación. Esto hizo que la retroalimentación fuera rápida y el desarrollo más confiable.

### ✅ ¿Cómo mantendrías esta suite de pruebas con el tiempo?

- Automatizando su ejecución con GitHub Actions ante cada cambio.
- Usando `pytest.ini` para configurar el entorno de forma clara.
- Escribiendo pruebas legibles, bien nombradas y organizadas por módulo.
- Refactorizando pruebas cuando cambie la lógica del negocio, para que sigan reflejando los requerimientos reales.
- Documentando los casos de prueba importantes para el equipo.

---

## 🚀 Automatización

El proyecto incluye un workflow de GitHub Actions (`.github/workflows/test.yml`) que ejecuta automáticamente las pruebas en cada `push` o `pull request`, asegurando calidad continua en el desarrollo.

