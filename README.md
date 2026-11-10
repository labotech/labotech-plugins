# Plugins de Labotech

Marketplace de plugins para Claude de Labotech de Venezuela, C.A.

## Plugins

| Plugin | Qué hace |
|---|---|
| `labotech-brand` | Guía de marca: voz, tono, colores, tipografía y reglas de contenido para web y marketing. |

## Instalación

**claude.ai o Claude Desktop** (requiere plan Pro, Max, Team o Enterprise)

1. Customize > Plugins.
2. En "Personal plugins", "+" > "Add marketplace" > "Add from a repository".
3. Pegar la URL: `https://github.com/labotech/labotech-plugins`
4. Instalar `labotech-brand`.

**Claude Code**

```
/plugin marketplace add labotech/labotech-plugins
/plugin install labotech-brand@labotech
```

## Reglas del repositorio

- **Este repositorio es público.** Solo entra lo que Labotech publicaría en su página web. Nada de precios, clientes, proveedores, estrategia interna ni skills operativos (ERPNext, aduanas, compras).
- **Sin número de versión.** Los plugins no declaran `version`, así que quien los instala sigue los commits. Si algún día se agrega `version`, hay que subirla en cada cambio o nadie recibe la actualización.
- **Una sola fuente.** Quien use este plugin debe desactivar cualquier copia del skill subida a mano, para no trabajar con dos versiones de la marca.

---

© Labotech de Venezuela, C.A. Todos los derechos reservados.
