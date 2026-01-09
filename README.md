# Quasar Note App

A simple note-taking application built with Vue 3 and Quasar Framework.

![Notes App Screenshot](imgs/demo.png)

## Features

- Create, edit, and delete notes
- Rich text editor for note content
- Local storage persistence
- Responsive design with Material Design UI

## Install the dependencies

```bash
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)

```bash
npm run dev
```

Or with Quasar CLI:

```bash
quasar dev
```

### Lint the files

```bash
npm run lint
```

### Format the files

```bash
npm run format
```

### Build the app for production

```bash
npm run build
```

Or with Quasar CLI:

```bash
quasar build
```

## Project Structure

```
src/
├── App.vue              # Root component
├── helper.js            # Local storage composables
├── components/
│   ├── Container.vue    # Layout container component
│   └── NoteCard.vue     # Note card component
├── css/
│   ├── app.scss         # Global styles
│   └── quasar.variables.scss # Quasar theme variables
├── layouts/
│   └── MainLayout.vue   # Main application layout
├── pages/
│   ├── IndexPage.vue    # Home page (note list)
│   ├── NewPage.vue      # Create new note page
│   ├── NotePage.vue     # View/edit note page
│   └── ErrorNotFound.vue # 404 page
└── router/
    ├── index.js         # Router configuration
    └── routes.js        # Route definitions
```

## Customize the configuration

See [Configuring quasar.config.js](https://v2.quasar.dev/quasar-cli-vite/quasar-config-js).
