# 🏛️ Comunidad de Arquitectura y Gobernanza Técnica

Bienvenido al repositorio central de decisiones técnicas. El objetivo de este espacio es democratizar el diseño de sistemas, fomentar la colaboración entre equipos y garantizar que las decisiones importantes queden documentadas de forma transparente.

---

## 📑 Conceptos Fundamentales

Para participar en esta comunidad, es esencial entender la diferencia entre una propuesta de cambio (RFC) y un registro de decisión (ADR).

| Concepto | ¿Qué es? | ¿Cuándo usarlo? | Estado Final |
| :--- | :--- | :--- | :--- |
| **RFC** *(Request for Comments)* | Un documento de **discusión** para proponer nuevas ideas o cambios significativos. | Se usa cuando el problema aún no tiene una solución consensuada y se busca feedback. | Se cierra una vez que hay consenso. |
| **ADR** *(Architecture Decision Record)* | Un registro **estático e inmutable** de una decisión técnica específica. | Se usa para documentar "por qué" se eligió una tecnología o patrón, después de la discusión. | Se mergea en la rama `main` como histórico. |

---

## 👥 Comité de Aprobación (Comitters)

Para garantizar la calidad y la coherencia técnica, las decisiones son revisadas por un comité multidisciplinario. Este comité no actúa como un "cuello de botella", sino como facilitadores de estándares.

### Composición del Comité:
1.  **Staff / Principal Engineers:** Responsables de la visión técnica global y consistencia entre dominios.
2.  **Tech Leads de Squads:** Representantes de los equipos que ejecutarán la decisión, asegurando la viabilidad práctica.
3.  **Especialistas de Dominio (SME):** Miembros de SRE/Infraestructura o Seguridad cuando la propuesta impacte sus áreas.

> [!IMPORTANT]
> **Regla de Oro:** Para que una decisión sea aceptada, requiere la aprobación de al menos **2 miembros del comité** y que no existan bloqueos de seguridad pendientes.

---

## 🚀 Flujo de Trabajo (Workflow)

Seguimos el modelo de "Arquitectura como Código":

1.  **Apertura de Issue:** Use el template `RFC: [Título]` para plantear el problema.
2.  **Debate:** La comunidad tiene un período de **7 a 14 días** para comentar y proponer alternativas.
3.  **Definición de Due Date:** Cada Issue debe tener un campo de "Fecha de Cierre" en el Project para evitar discusiones infinitas.
4.  **Pull Request:** Una vez alcanzado el consenso, se envía un PR con el archivo `.md` en la carpeta `/adrs`.
5.  **Aprobación y Merge:** Los Comitters revisan, aprueban y el documento queda como referencia histórica.

---

## 📂 Estructura del Repositorio

* `/rfcs`: Borradores y propuestas en fase de debate.
* `/adrs`: Registro histórico de decisiones aprobadas.
* `/templates`: Plantillas oficiales para nuevas propuestas.
* `.github/CODEOWNERS`: Configuración de revisores automáticos por área.

---

## 🛠️ Cómo Contribuir

1.  Revisa el **GitHub Project** para ver qué decisiones están en proceso.
2.  Si tienes una idea, abre una **Issue** detallando el contexto.
3.  Participa en las discusiones de otros equipos; tu feedback es valioso independientemente de tu nivel de seniority.

---
*Última actualización: 22 de enero de 2026*
