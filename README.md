# ☀️ Wakacyjne Wyzwanie 2026 – moja frontendowa przygoda

Latem 2026 wziąłem udział w **Wakacyjnym Wyzwaniu** – 7-tygodniowym kursie frontendu prowadzonym przez [KN Solvro](https://solvro.pwr.edu.pl/) (Politechnika Wrocławska). Co tydzień: wykład, nowy temat i zadanie praktyczne oddawane przez Pull Request.

To repozytorium jest zapisem tej drogi – **od pierwszego komponentu w React po renderowanie ISR i SEO w Next.js**. Każdy folder to osobny tydzień, więc najlepiej czytać je po kolei i widać, jak z tygodnia na tydzień rosła skala i złożoność zadań.

![Next.js](https://img.shields.io/badge/Next.js_16-000000?logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?logo=shadcnui&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?logo=reactquery&logoColor=white)

## 🗺️ Tydzień po tygodniu

| # | Rozdział | Co zbudowałem | Czego się nauczyłem |
|---|----------|---------------|---------------------|
| 1 | [Wstęp](./rozdzial-1-wstep) | Komponent `ProjectCard` – wizytówka projektu z listą technologii i przełączanym statusem | React + Vite, komponenty, propsy typowane w TypeScript, `useState`, renderowanie list |
| 2 | [Pierwszy projekt](./rozdzial-2-pierwszy-projekt) | Pierwsza aplikacja Next.js z kartą członka zespołu `TeamMemberCard` | Struktura projektu Next.js, Tailwind CSS, responsywność, tryb ciemny |
| 3 | [Komponenty nextowe](./rozdzial-3-komponenty-nextowe) | Rozbudowana karta ze zdjęciem, własną czcionką i linkiem | `next/image`, `next/link`, `next/font`, `next/script` – optymalizacje wbudowane w Next.js |
| 4 | [Routing](./rozdzial-4-routing) | Aplikacja z listą użytkowników, dynamicznymi profilami i panelem statystyk | App Router, trasy dynamiczne `[id]`, **parallel routes** (`@stats`), `loading` / `error` / `not-found` |
| 5 | [Shadcn i UI](./rozdzial-5-shadcn-i-ui) | Odświeżony interfejs: karty profili, nawigacja w zakładkach, profil otwierany w modalu | shadcn/ui (Card, Avatar, Dialog, Tabs, Skeleton), **intercepting routes** `(.)users/[id]`, container queries |
| 6 | [Ładowanie danych](./rozdzial-6-ladowanie-danych) | Katalog produktów z wyszukiwarką na żywo i formularzem dodawania produktu | Server vs Client Components, fetch po stronie serwera, **TanStack Query** (`useQuery`, `useMutation`, `initialData`, invalidacja cache) |
| 7 | [Static vs dynamic](./rozdzial-7-static-vs-dynamic) | „Render & SEO Lab” – katalog przyjazny wyszukiwarkom | **SSG / ISR / SSR** (`revalidate`, `force-dynamic`, `generateStaticParams`), `generateMetadata`, Open Graph, canonical, `sitemap.ts`, `robots.ts`, deduplikacja zapytań przez `cache()` |
