# Ulas Can Sahin

<p align="center">
  <a href="README.de.md">&#127465;&#127466; Deutsch</a> ? <a href="README.es.md">&#127466;&#127480; Espa&ntilde;ol</a> ? <a href="README.md">&#127468;&#127463; English</a> ? <a href="README.pt-BR.md">&#127463;&#127479; Portugu&ecirc;s (Brasil)</a> ? <a href="README.tr.md">&#127481;&#127479; T&uuml;rk&ccedil;e</a> ? <a href="README.fr.md">&#127467;&#127479; French</a>
</p>

Pagina publica de perfil y entrada a proyectos de productos de seguridad, vaults autohospedados, workflows Codex y documentacion engineering public-safe.

## Por que existe este repositorio

Pagina publica de perfil y entrada a proyectos de productos de seguridad, vaults autohospedados, workflows Codex y documentacion engineering public-safe.

Esta portada localizada se mantiene para que el lector entienda el repositorio sin depender de una etiqueta de idioma corta. La referencia canonica profunda sigue en README.md; esta pagina contiene suficiente contexto para elegir el punto de entrada, el limite de seguridad y la verificacion correcta.

## Para quien es

Equipos de seguridad, operadores, reviewers y developers que quieren entender rapido MyVuln, PassMan o los repos starter de Codex.

## Inicio rapido

| Si necesitas... | Abre |
| --- | --- |
| MyVuln live product | [https://myvuln.io/](https://myvuln.io/) |
| PassMan release hub | [https://github.com/ucsahinn/passman](https://github.com/ucsahinn/passman) |
| Codex Skill Forge | [https://github.com/ucsahinn/codex-skill-forge](https://github.com/ucsahinn/codex-skill-forge) |
| Codex CLI Handbook | [https://github.com/ucsahinn/codex-cli-best-practice](https://github.com/ucsahinn/codex-cli-best-practice) |
| Prompt Architect | [https://github.com/ucsahinn/codex-enterprise-prompt-architect](https://github.com/ucsahinn/codex-enterprise-prompt-architect) |

## Mapa del repositorio

- README.md - canonical profile page
- README.tr.md / README.de.md / README.es.md / README.pt-BR.md / README.fr.md - localized front doors
- GitHub profile repositories - project-specific source of truth

## Validacion e higiene de release

Antes de commit o publicacion, revisa links, Markdown, validacion existente del repo y Gitleaks.

Ruta recomendada de release/readiness:

1. Revisar el README relevante y los documentos enlazados.
2. Ejecutar la validacion del repositorio cuando exista un comando.
3. Comprobar links Markdown y assets locales.
4. Ejecutar Gitleaks o el secret scan configurado.
5. Verificar origin/main despues del push antes de afirmar que la publicacion termino.

## Limite de seguridad y alcance publico

La pagina de perfil apunta a repos publicos y superficies live. Codigo privado, datos de clientes, secretos y rutas locales no pertenecen a esta superficie.

## Contribucion y mantenimiento

Mant?n las paginas localizadas alineadas con el README canonico cuando cambien el alcance, los pasos de instalacion, las reglas de release o los limites de seguridad. No agregues afirmaciones que no esten respaldadas por el repositorio, docs live del producto o evidencia publica de release.

## Estandar de completitud

Este README localizado no es una nota corta. Explica proposito, entrada, superficies del repositorio, validacion, limite de seguridad y referencias canonicas.

Referencia canonica: [README.md](README.md).
