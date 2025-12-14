# GitHub Repository Finder

This is a **GitHub Repository Finder** project built with **Astro**, focused on practicing **API integration**, **asynchronous JavaScript**, and **UI state management**.

The application allows users to select a programming language and fetch a **random GitHub repository** related to that language.

---

## Description

The app fetches data from **two external sources**:

1. **Programming languages list** (static JSON)
2. **GitHub Repository Search API**

Users can:

* Select a programming language from a dropdown
* Fetch a random repository related to that language
* View key repository information:

  * Name
  * Description
  * Language
  * Stars
  * Forks
  * Open issues
* Click a **Refresh** button to get another random repository.

The application properly handles:

* Loading states
* Empty results
* API errors (including GitHub rate limits)

---

## Tech Stack

* **Astro**
* **Vanilla JavaScript**
* **Tailwind CSS**
* **GitHub REST API**

---

## External APIs & Resources

* **GitHub Repository Search API**
  [https://docs.github.com/en/rest/search/search?apiVersion=2022-11-28#search-repositories](https://docs.github.com/en/rest/search/search?apiVersion=2022-11-28#search-repositories)

* **Programming Language Data (JSON)**
  [https://raw.githubusercontent.com/kamranahmedse/githunt/master/src/components/filters/language-filter/languages.json](https://raw.githubusercontent.com/kamranahmedse/githunt/master/src/components/filters/language-filter/languages.json)

---

## Getting Started

### Prerequisites

Make sure you have the following installed:

* **Node.js** (v18 or later recommended)
* One of the following package managers:

  * **pnpm** (recommended)
  * **npm**
  * **yarn**

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/Steven-lh/github-random-repo-finder.git
cd ../github-random-repo-finder
```

---

### 2. Install dependencies

#### Using pnpm (recommended)

```bash
pnpm install
```

#### Using npm

```bash
npm install
```

#### Using yarn

```bash
yarn install
```

---

## Running the Project

Start the development server:

```bash
pnpm dev
# or
npm run dev
# or
yarn dev
```

The application will be available at:

```
http://localhost:4321
```

---

## Build for Production

```bash
pnpm build
# or
npm run build
# or
yarn build
```

Preview the production build:

```bash
pnpm preview
```

---

## Project Structure

```
github-random-repo-finder/
├─ public/
├─ src/
│  ├─ assets/
│  ├─ components/
│  │  ├─ Header.astro
│  │  ├─ LanguageSelector.astro
│  │  ├─ RepositoryPreview.astro
│  ├─ layouts/
│  │  └─ Layout.astro
│  ├─ pages/
│  │  └─ index.astro
│  ├─ styles/
│  │  └─ global.css
├─ astro.config.mjs
├─ package.json
├─ pnpm-lock.yaml
├─ tsconfig.json
└─ README.md
```

---

## Project Goals

This project is designed to help you practice:

* Working with **external APIs**
* Handling **asynchronous requests** using `fetch`
* Managing **UI states** (loading, error, empty)
* Component-based structure in Astro
* Building a responsive and user-friendly interface

---

## Reference

This project follows the requirements described in:

[https://roadmap.sh/projects/github-random-repo](https://roadmap.sh/projects/github-random-repo)

---

## Contact

If you have suggestions or feedback, feel free to open an issue or reach out via GitHub.

---

Thanks.

