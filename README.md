<h1 align="center">Football PRO</h1>

<p align="center">
  Gestión de un club de fútbol profesional para aprender relaciones JPA con Spring Boot.<br/>
  <sub>Professional football club management built to learn JPA relationships with Spring Boot.</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Web-38BDF8?style=flat" alt="Web"/>
  <img src="https://img.shields.io/badge/type-Academic%20practice-22C55E?style=flat" alt="Academic practice"/>
  <img src="https://img.shields.io/badge/year-2024-495057?style=flat" alt="2024"/>
</p>

<p align="center">
  <a href="#español">Español</a> · <a href="#english">English</a>
</p>

<p align="center">
  <img src="https://drey.is-a.dev/img/projects/project3/project3-1.png" alt="Football PRO home" width="90%"/>
</p>

## Tech stack

<p align="center">
  <img src="https://img.shields.io/badge/Java-21-ED8B00?style=flat&logo=openjdk&logoColor=white" alt="Java 21"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-3.4-6DB33F?style=flat&logo=springboot&logoColor=white" alt="Spring Boot 3.4"/>
  <img src="https://img.shields.io/badge/Spring%20Data%20JPA-Hibernate-6DB33F?style=flat&logo=hibernate&logoColor=white" alt="Spring Data JPA"/>
  <img src="https://img.shields.io/badge/Thymeleaf-Views-005F0F?style=flat&logo=thymeleaf&logoColor=white" alt="Thymeleaf"/>
  <br/>
  <img src="https://img.shields.io/badge/Bootstrap-UI-7952B3?style=flat&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
  <img src="https://img.shields.io/badge/H2-In--memory-4479A1?style=flat" alt="H2"/>
  <img src="https://img.shields.io/badge/Maven-Build-C71A36?style=flat&logo=apachemaven&logoColor=white" alt="Maven"/>
</p>

## Screenshots

<table>
  <tr>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project3/project3-2.png" alt="Modules"/>
      <br/><b>Módulos · Modules</b><br/><sub>Clubes, jugadores, entrenadores, asociaciones y competiciones</sub>
    </td>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project3/project3-4.png" alt="Clubs"/>
      <br/><b>Clubes · Clubs</b><br/><sub>Listado con entrenador, asociación, competiciones y jugadores</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project3/project3-3.png" alt="New club"/>
      <br/><b>Nuevo club · New club</b><br/><sub>Formulario con relaciones y escudo</sub>
    </td>
    <td width="50%" align="center">
      <img src="https://drey.is-a.dev/img/projects/project3/project3-6.png" alt="Competition"/>
      <br/><b>Competiciones · Competitions</b><br/><sub>Fechas, premio y clubes participantes</sub>
    </td>
  </tr>
</table>

---

## Español

> Proyecto de aprendizaje enfocado en mapear las relaciones entre entidades con Spring Data JPA, aplicado a la gestión de un club de fútbol.

### Relaciones implementadas

| Relación | Ejemplo en el proyecto |
|---|---|
| **OneToOne** | Un club tiene un entrenador. |
| **OneToMany / ManyToOne** | Un club tiene muchos jugadores; cada jugador pertenece a un club. |
| **ManyToOne** | Varios clubes pertenecen a una asociación. |
| **ManyToMany** | Los clubes participan en varias competiciones y cada competición tiene varios clubes. |

### Funcionalidades

- CRUD completo de clubes, jugadores, entrenadores, asociaciones y competiciones.
- Subida de imágenes (escudos de los clubes).
- Autenticación básica.
- Interfaz responsiva con Bootstrap.

### Cómo ejecutarlo

1. Requisitos: **JDK 21**. El proyecto incluye `mvnw`.
2. Ejecuta:
   ```bash
   ./mvnw spring-boot:run
   ```
3. Abre `http://localhost:8089`. La consola de H2 queda en `/h2-console`.

> [!NOTE]
> H2 es una base de datos en memoria: los datos se borran al reiniciar la aplicación.

---

## English

> A learning project focused on mapping entity relationships with Spring Data JPA, applied to managing a football club.

### Implemented relationships

| Relationship | Example in the project |
|---|---|
| **OneToOne** | A club has one coach. |
| **OneToMany / ManyToOne** | A club has many players; each player belongs to one club. |
| **ManyToOne** | Several clubs belong to one association. |
| **ManyToMany** | Clubs play in several competitions and each competition has several clubs. |

### Features

- Full CRUD for clubs, players, coaches, associations and competitions.
- Image uploads (club crests).
- Basic authentication.
- Responsive UI with Bootstrap.

### Getting started

1. Requirements: **JDK 21**. The project ships with `mvnw`.
2. Run:
   ```bash
   ./mvnw spring-boot:run
   ```
3. Open `http://localhost:8089`. The H2 console is at `/h2-console`.

> [!NOTE]
> H2 is an in-memory database: data is cleared when the app restarts.

---

## Autor · Author

Desarrollado por **Andrey Mantilla Leon** · Ingeniería de Sistemas. Portafolio: [drey.is-a.dev](https://drey.is-a.dev)
