# Changelog

## v1.0.0 — 2026-11-17

- Entrega individual del experimento 1 (identidad de máquinas), separada del repositorio del grupo `clic_kiusys` (base v5.1.1).
- Credencial efímera del coordinador con alcance, audiencia, origen y revocación detrás de `IDENTIDAD_ESTRICTA`.
- Ronda 0: 3 de 3 usos adversos aceptados y sin detección. Ronda 1: 0 de 3 aceptados, MTTD 0,25 s, MTTC 0,02 s y 0 falsos positivos.
- Regla `uso-credencial-no-previsto` con caso positivo y negativo; 12 pruebas en `tests/test_identidad.py`.
- `app/services/sli.py` ya no falla en Windows por el módulo `resource`.
- Informe con la sección de tendencias del sector (Gartner 2027, CA/B Forum SC-081v3).
