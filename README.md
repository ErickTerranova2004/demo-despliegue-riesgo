# demo-despliegue-riesgo

Repositorio de **demostración** para la plataforma predictiva de riesgo de
despliegue (proyecto de titulación). El workflow `deploy-demo.yml` construye una
imagen mínima y la publica en GitHub Container Registry con el `GITHUB_TOKEN`
integrado.

Los fallos se provocan a propósito para probar la verificación del resultado
real: un commit cuyo mensaje contiene `[fallo]`, o una ejecución manual con
`simular_fallo = true`, hace fallar el paso previo a la publicación.

Sus ejecuciones **no** son datos de validación del modelo.
