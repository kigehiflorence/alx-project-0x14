# alx-project-0x14
# ALX‑Project‑0x14: MovieDB API Integration

## 🧩 API Overview
The project integrates with The Movie Database (TMDb) API—a community-driven RESTful service offering detailed data on movies, TV shows, actors, images, and more :contentReference[oaicite:1]{index=1}.

## 📌 API Version
**Version:** v3 of TMDb API (also referred to alongside newer v4; v3 is fully documented and widely used) :contentReference[oaicite:2]{index=2}.

## 📜 Available Endpoints
- `GET /movie/{movie_id}` — Retrieve metadata for a specific movie (title, overview, genres, release date, etc.) :contentReference[oaicite:3]{index=3}.
- `POST /movie/{movie_id}/rating` — Submit or update user rating (0.5–10.0 scale) :contentReference[oaicite:4]{index=4}.
- `GET /search/movie` — Search for movies using query parameters like `query`, `page`, `year`, etc.
- `GET /genre/movie/list` — Retrieve available movie genres (IDs and names) for filtering.
- `GET /configuration` — Retrieve essential static meta (image base URLs, sizes, language options) :contentReference[oaicite:5]{index=5}.
*(Add additional endpoints you plan to use: TV, people, credits…)*

## 📦 Request & Response Format

### Example: Fetch movie details
