<div align="center">

# Gabriel Vaca

Desarrollador de Software · Flutter · Python · TypeScript
Latacunga, Ecuador

[![Email](https://img.shields.io/badge/Email-alejovaca19%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alejovaca19@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gabriel%20Vaca-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gavaca06/)

</div>

---

## Sobre mí

Egresado de Ingeniería en Software (ESPE), con defensa de tesis en enero 2027.

Construyo software para problemas operativos reales: dos de mis proyectos están en uso por un negocio y un hospital. Trabajo con arquitectura documentada, tests y desarrollo asistido por IA guiado por especificaciones, revisando cada PR.

---

## Proyectos destacados

### [De Vacos: POS móvil offline-first](https://github.com/ElMichi08/de_vacos)

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

POS para el negocio de comida rápida de mi familia: pedidos, pantalla de cocina en tiempo real, caja, control de stock e impresión térmica. Funciona sin internet y sincroniza los reportes con la nube.

- Sostuvo el crecimiento de ~40 a más de 100 pedidos diarios (picos de 160) sin cambiar el proceso operativo.
- Hook pre-commit que bloquea cualquier commit si fallan `flutter analyze` o los tests. Los tests se generaron con IA a partir de las reglas de negocio que definí.

### [LuxMed: validación de seguros médicos on-premise](https://github.com/ElMichi08/LuxMed)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![PyQt6](https://img.shields.io/badge/PyQt6-41CD52?style=flat-square&logo=qt&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

App de escritorio, hecha en equipo de 2, que valida la cobertura de seguro de pacientes en 3 portales gubernamentales y consolida sus PDF de respaldo. Ningún dato de pacientes sale de la máquina local (LOPDP).

- La validación pasó de hasta 45 min a menos de 1 min por paciente. En el piloto, un lote de ~400 pacientes se procesó en ~4 h.
- Arquitectura hexagonal con ADRs y 13 especificaciones Gherkin escritas por nosotros. Los tests en pytest se generaron con IA a partir de esas especificaciones, incluidos tests que impiden que las capas de la arquitectura se mezclen. CI con GitHub Actions.

### [Dashboard predictivo de stock](https://github.com/joel12sa/S_stock_ia) (pasantía en Import-Quivenza)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)


## Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=flutter,dart,py,fastapi,java,spring,ts,nextjs,react&perline=9" />
  <br />
  <img src="https://skillicons.dev/icons?i=postgres,sqlite,supabase,docker,githubactions,git,github,aws&perline=9" />
</p>

![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Gherkin](https://img.shields.io/badge/BDD%20Gherkin-23D96C?style=flat-square&logo=cucumber&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=claude&logoColor=white)

---

## Cómo trabajo

- Escribo los requisitos en Gherkin antes del código. El agente implementa y genera los tests a partir de esas especificaciones; mi parte es definir qué se prueba y revisar y corregir cada PR.
- Uso ramas por feature y pull requests revisados.
- Documento las decisiones de arquitectura en ADRs.
