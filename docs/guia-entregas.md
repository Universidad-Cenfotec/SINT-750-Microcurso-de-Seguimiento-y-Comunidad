# Guía 2: Cómo entregar tus tareas con un pull request

Tus tareas se trabajan en **tu fork** y se envían al **repositorio del curso** mediante un *pull request* (PR). Luego copias el enlace del PR y lo subes a Moodle.

> Si todavía no tienes tu fork, sigue primero la [Guía 1](guia-fork.md).
> En los ejemplos usamos el usuario **GabyHN**; reemplázalo por el tuyo.

## 1. Actualiza tu fork

En tu fork, haz clic en **Sync fork → Update branch**.

## 2. Sube tu tarea a tu fork

1. Entra a la carpeta que corresponde:
   - Tarea individual: `4. Estudiantes` → tu carpeta (si no existe, créala con tu nombre).
   - Tarea grupal: `6. Grupos` → la carpeta de tu grupo.
2. Haz clic en **Add file → Upload files** (o **Create new file**).
3. Arrastra tus archivos.
4. En el mensaje escribe qué entregas, por ejemplo: `Entrega Reto 1 - Nombre Apellido`.
5. Haz clic en **Commit changes**.

## 3. Crea el pull request hacia el repositorio del curso

1. En tu fork, haz clic en **Contribute → Open pull request**.
2. **Revisa la barra de arriba. Debe verse así:**

   ```
   base repository: Universidad-Cenfotec/SINT-750-Microcurso-de-Seguimiento-y-Comunidad   base: main
                         ←
   head repository: GabyHN/SINT-750-Microcurso-de-Seguimiento-y-Comunidad                 compare: main
   ```

   - **base repository** = el repo del **curso** (`Universidad-Cenfotec/...`). ✅
   - Si en *base repository* aparece **tu usuario**, cámbialo a `Universidad-Cenfotec/...`. ❌
3. Ponle un título claro, por ejemplo: `Entrega Reto 1 - Nombre Apellido`.
4. Haz clic en **Create pull request**.

## 4. Revisa el enlace del pull request

Al crearlo, quedas en la página del PR. Mira la dirección en el navegador:

✅ **Correcto** (el PR está en el repositorio del curso):

```
https://github.com/Universidad-Cenfotec/SINT-750-Microcurso-de-Seguimiento-y-Comunidad/pull/25
```

❌ **Incorrecto** (el PR quedó en tu propio fork):

```
https://github.com/GabyHN/SINT-750-Microcurso-de-Seguimiento-y-Comunidad/pull/1
```

Si tu enlace empieza con tu usuario, cierra ese PR (**Close pull request**) y repite el paso 3 revisando el *base repository*.

> El número al final (`/pull/25`) cambia en cada entrega; lo importante es que empiece con `github.com/Universidad-Cenfotec/`.

## 5. Sube el enlace a Moodle

1. Copia el enlace completo del PR desde la barra del navegador.
2. Entra a la tarea correspondiente en Moodle.
3. Pega el enlace en la entrega y envíala.

## Resumen rápido

| Paso | Dónde | Qué haces |
|---|---|---|
| 1 | Tu fork | Sync fork → Update branch |
| 2 | Tu fork | Subes tus archivos a tu carpeta o la de tu grupo |
| 3 | Tu fork | Contribute → Open pull request (base = Universidad-Cenfotec) |
| 4 | Página del PR | El enlace empieza con `github.com/Universidad-Cenfotec/` |
| 5 | Moodle | Pegas el enlace del PR |
