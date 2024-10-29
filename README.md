# Calculadora de Árboles Binomiales para Productos Derivados

Este repositorio contiene un archivo de Excel con una macro incorporada que permite calcular el valor de productos financieros derivados mediante árboles binomiales. Esta herramienta es ideal para evaluar opciones europeas, americanas, digitales y con dividendos, utilizando parámetros específicos de mercado.

## Funcionalidades

La calculadora de árboles binomiales permite el cálculo de precios de los siguientes productos derivados:

- **Opciones Europeas y Americanas**:
  - Call
  - Put
- **Opciones Digitales**:
  - Call digital
  - Put digital

Además, la herramienta considera opciones con **dividendos discretos** y **dividendos continuos**.

## Parámetros de Entrada

El usuario puede personalizar los siguientes parámetros para realizar los cálculos:

- **Volatilidad del Subyacente**: La volatilidad anualizada del activo subyacente.
- **Tasa de Interés Libre de Riesgo**: La tasa de interés sin riesgo del mercado.
- **Número de Períodos**: El número de pasos o períodos para construir el árbol binomial.
- **Precio de Ejercicio (Strike)**: El precio al cual se ejercerá la opción.
- **Monto para Opciones Digitales**: Valor del pago al momento de ejercer una opción digital.

## Cálculos Realizados por la Macro

La macro utiliza un modelo binomial para estimar el precio de opciones mediante una estructura de probabilidad. Los cálculos incluyen:

1. **Probabilidades de Subida y Bajada**: Las probabilidades implícitas de subida y bajada del precio del subyacente en cada período.
2. **Construcción de Árboles Binomiales**:
   - **Árbol del Subyacente**: Representa la evolución de precios del subyacente en cada período.
   - **Árbol del Derivado**: Cálculo del valor del derivado en cada nodo del árbol.
   - **Árbol de Alphas**: La cantidad de subyacente necesaria para realizar la cobertura (estrategia de cobertura dinámica).
   - **Árbol de Betas**: La cantidad de dinero a invertir en el mercado de dinero para la cobertura.

## Formulario

Incluimos un formulario que permite a los usuarios ver todas las fórmulas matemáticas utilizadas en la macro. Esto ofrece una visión detallada de los cálculos internos y facilita la comprensión del modelo.

## Requisitos

- **Microsoft Excel**: Se recomienda la versión más reciente de Excel para evitar problemas de compatibilidad con macros.
- **Habilitar Macros**: Asegúrate de habilitar las macros en Excel para utilizar esta calculadora de derivados financieros.

## Instrucciones de Uso

1. **Descarga** el archivo de Excel desde este repositorio.
2. **Abre el archivo** en Microsoft Excel y **habilita las macros** si es necesario.
3. **Introduce los parámetros** en las celdas correspondientes:
   - Volatilidad
   - Tasa de interés
   - Número de períodos
   - Precio de ejercicio (strike)
   - Monto para opciones digitales
4. **Ejecuta la macro** para calcular los valores de los árboles binomiales.
5. Opcionalmente, revisa el formulario de fórmulas para obtener información detallada de los cálculos.

## Contribuciones

¡Las contribuciones son bienvenidas! Si tienes sugerencias para mejorar la calculadora, no dudes en crear un *issue* o enviar un *pull request*.

## Licencia

Este proyecto está licenciado bajo la [Licencia MIT](LICENSE).

---

> **Nota**: Esta herramienta es únicamente para fines educativos y no constituye asesoramiento financiero. Utilízala bajo tu propio riesgo y considera siempre realizar un análisis financiero independiente.

