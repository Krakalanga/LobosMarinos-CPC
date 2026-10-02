# Costa viva — El mar no olvida

Web documental para la Feria Científica del **Instituto Cumbre de Cóndores Poniente, Renca, 4° C**. Tema: la caza de lobos marinos en Chile, su historia y los desafíos actuales de conservación y convivencia.

**Equipo:** Matías González, Rodrigo Nuñez y Benjamin Cortés. **Docentes:** Katalina Venegas y Marco González.

## Ver la web en tu computador

Instala Node.js 22.12 o posterior (recomendado: rama 22 LTS), descomprime el ZIP y abre una terminal dentro de `costa-viva`:

```bash
npm ci
npm run dev
```

Abre la dirección que muestra la terminal, normalmente `http://localhost:5173`.

Para comprobar exactamente la versión de producción:

```bash
npm run build
npm run preview
```

Abre `http://localhost:4173`. La carpeta **`dist/`. Si tienes Python 3, puedes verla sin instalar dependencias de Node:

```bash
python3 -m http.server 4173 --directory dist
```
---> Usamos Codex para el desarrollo de este trabajo <-----