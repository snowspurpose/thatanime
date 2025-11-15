# thatanime

A clean and modern front-end demo for interacting with the [Jikan API](https://jikan.moe), an unofficial MyAnimeList REST API. Perfect for exploring anime data or building a foundation for your next project.

---

## Features
- **Minimal and Static**: A lightweight client-side app with no dependencies.
- **Dynamic Anime Data**: Fetch and display up-to-date information using the Jikan API.
- **Flexible and Extensible**: Use it as-is, or expand it to build your dream anime app.

---

## Usage

### Open the Project
1. **Directly**:
   - Simply open `index.html` in your browser.

2. **Run via Local Server** (Recommended):
   - For better support of `fetch`, ES modules, or CORS issues, use a local HTTP server:
     - Python:
       ```bash
       python3 -m http.server 8000
       ```
     - Node.js:
       ```bash
       npx serve .
       ```

   - Open [`http://localhost:8000`](http://localhost:8000) in your browser.

---

## Development

- **Polish the Front-End**:
  - Refine the HTML and CSS to improve the design.
  - Add animations, themes, or visual details.
  
- **Add Functionality**:
  - Introduce search filters or pagination.
  - Include user ratings, watchlists, or other features that enhance engagement.

- **Expand the Scope**:
  - Connect to a backend for user authentication, caching, or additional API integrations.
  - Convert it into a full-stack application using frameworks like React, Vue, or Angular.

---

## API Notes
### Jikan API Guidelines
- **Rate Limit**: Requests are limited—implement retries and backoff to handle delays.
- **CORS Restrictions**: Use a proxy or server-side logic if CORS policies block requests during development.
- **Error Handling**: Properly manage API errors and provide fallback content when necessary.

Be sure to check the [Jikan API documentation](https://jikan.moe) for detailed information.

---

## Deployment
### Recommended Hosting Options
This project is static and can be deployed quickly to:
- **GitHub Pages**:
  1. Commit the `index.html` file and assets to your repo.
  2. Enable GitHub Pages in **Settings → Pages → Source**.
  3. Your site will be visible at `https://<username>.github.io/<repo-name>/`.
  
- **Alternative Hosts**:
  - [Netlify](https://www.netlify.com/)
  - [Vercel](https://vercel.com/)
  - [Surge](https://surge.sh/)

---

## Contributing
Contributions are welcome! Whether it's fixing bugs, improving design, or adding new features:
1. Open an **Issue** to propose changes or report bugs.
2. Send focused **Pull Requests** with a clear description of the changes.

---

## License
This project is licensed under the MIT License. You are free to use, modify, and share it under the terms of [LICENSE](./LICENSE).

---
