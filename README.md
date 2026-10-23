# bitcoin.gob.sv — propuesta de rediseño

Borrador de rediseño del sitio de la Oficina Nacional de Bitcoin de El Salvador. **No es el sitio oficial.**

Secciones: Reserva Estratégica (datos en cadena en vivo), Novedades (X), Zonas Bitcoin, CUBO+, Bitcoin Histórico y Bitcoin Diploma 2.0.

Todo el sitio vive en `index.html` (un solo archivo, sin dependencias de compilación). Los datos en vivo de la reserva se leen de `/api/v1/wallet/ONBTC` cuando el sitio corre en bitcoin.gob.sv.
