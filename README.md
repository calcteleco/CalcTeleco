## Hi there 👋

# CalcTeleco

Calculadoras web gratuitas para el diseño de radioenlaces, basadas en las recomendaciones de la **ITU-R**.

🔗 **Web:** https://calcteleco.github.io

## ¿Qué es?

CalcTeleco reúne en una sola página varias calculadoras de radioenlaces. Puedes cambiar los parámetros y ver al momento cómo varían los resultados. Está pensada para estudiantes y para cualquiera que quiera hacer cálculos rápidos sin abrir MATLAB.

Los cálculos parten de scripts de MATLAB hechos en las asignaturas de radiocomunicaciones del grado, y los resultados de la web se han comprobado contra ellos.

## Calculadoras

| Calculadora | Qué calcula |
|---|---|
| **Balance de enlace** | Potencia recibida y pérdidas con la fórmula de Friis |
| **Reflexión / difracción en tierra esférica** | Efecto de la reflexión en el suelo y de la curvatura terrestre |
| **Difracción por obstáculos** | Pérdidas por obstáculos con los métodos *knife-edge* y Bullington |
| **Atenuación por lluvia** | Atenuación e indisponibilidad por lluvia en enlaces terrestres y por satélite |
| **Alturas de antena** | Alturas necesarias para cumplir el despejamiento de la zona de Fresnel |

## Base técnica

Recomendaciones ITU-R utilizadas:

- **P.526**: propagación por difracción
- **P.530**: diseño de radioenlaces terrenales con visibilidad directa
- **P.618**: enlaces Tierra-espacio
- **P.838-3**: atenuación específica por lluvia (coeficientes k y α)
- **P.837**: intensidad de lluvia
- **P.839**: altura de la lluvia

## Uso

No hace falta instalar nada. Basta con abrir la web en el navegador.

Toda la herramienta está en un único archivo `index.html`, sin dependencias de servidor.

## Autor

Álvaro, estudiante de Ingeniería en Sistemas de Telecomunicación en la Universidad de Alcalá (UAH).

Si encuentras un error en algún cálculo, puedes abrir un *issue* en este repositorio.
