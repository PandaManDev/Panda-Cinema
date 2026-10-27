# Panda Cinema

A responsive, static movie-library website designed for GitHub Pages. It starts with **zero movies** and allows visitors to add authorized direct video URLs, poster image URLs, titles, years, genres, and descriptions. Movies can be searched, filtered, played in the built-in HTML video player, and removed.

## Deploy on GitHub Pages

1. Create a GitHub repository named `Panda-Cinema` (or use an existing repository intended for this site).
2. Upload `index.html` to the repository root. Keep `README.md` if you want these instructions online.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. After the Pages build completes, your site will be available at `https://YOUR-USERNAME.github.io/Panda-Cinema/`.

## Add a movie

Use **Add a movie** and enter a title plus a direct HTTPS video-file URL (for example, a URL ending in `.mp4` or `.webm`). Poster images are optional. The site does not supply movies or bypass restrictions. Use only video sources you own or have permission to stream.

## Important limitations

- This is a static GitHub Pages site; there is no server or central shared database.
- Movie metadata is stored in `localStorage` in the visitor's browser. A movie added on one device/browser will not automatically appear for other visitors, and clearing site data can erase the collection.
- Playback works best with direct MP4/WebM/Ogg file URLs and hosts that allow cross-site playback. Some hosts block playback, require authentication, or provide watch pages rather than direct files.
- The site does not host uploaded video files; it stores links only.
