# Zapata — Resortes (app publicada)

Motor de zapatas sobre suelo elástico (Rígido, Winkler, Pasternak),
conectado al motor en C++/WebAssembly. Incluye:
- Worker reutilizado entre cálculos (no se vuelve a descargar el motor).
- Factorización de la matriz de rigidez compartida entre las 10
  combinaciones de carga cuando el contacto es completo (el caso más
  común), en vez de rehacerla desde cero cada vez.
