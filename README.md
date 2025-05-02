**Unfortunately, the site is currently not working due to the unavailability of the database.**

# Marvel Information Portal

A single-page React application for browsing Marvel characters and comics using the official Marvel API.

## Description

- **Main Page**: Browse a list of Marvel characters, view detailed information about a selected character, and search for characters by name.
- **Comics Page**: Browse a list of Marvel comics and view detailed information about each comic.
- **Character/Comic Pages**: View detailed information about a selected character or comic.
- **Error Handling**: Custom components for displaying errors and skeleton loaders.
- **Responsive Design**: Styled with SCSS.

## Technologies

- React 18
- React Router DOM
- SCSS (Sass)
- Formik + Yup (for forms and validation)
- Marvel API
- PropTypes

## Project Structure

```
src/
  components/      // UI components (organized in subfolders)
  services/        // Marvel API logic
  hooks/           // Custom React hooks
  style/           // SCSS styles
  resources/       // Images and resources
  index.js         // Entry point
public/
  index.html       // HTML template
```

## Getting Started

1. **Install dependencies:**
   ```
   npm install
   ```

2. **Run in development mode:**
   ```
   npm start
   ```
   The app will be available at [http://localhost:3000](http://localhost:3000).

3. **Build for production:**
   ```
   npm run build
   ```

## Main Components

- **App** — Main component, routing.
- **AppHeader** — Header with navigation.
- **MainPage** — Main page with characters.
- **ComicsPage** — Comics page.
- **CharList, CharInfo** — Character list and details.
- **ComicsList** — Comics list.
- **ErrorBoundary, ErrorMassage, Skeleton, Spinner** — Error handling, loading, skeletons.

## Additional Notes

- All styles are written in SCSS.
- Forms are managed with Formik + Yup.
- All components are typed with PropTypes.
- No debug logs or dead code remain in the project (please check before deployment).

## License

This project is created for educational purposes.
