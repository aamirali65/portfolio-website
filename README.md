# Portfolio Website

My personal portfolio site — where I list my projects, skills and experience, and link out to the things I've built.

Live at **[aamiralmani.vercel.app](https://aamiralmani.vercel.app/)**.

## Stack

- **React** + **TypeScript** on **Vite**
- **Tailwind CSS** for styling, with **shadcn/ui** components (`components.json`, `src/components/ui/`)
- **lucide-react** icons and a custom cursor-glow effect
- Deployed on Vercel

## Sections

`src/components/` holds one file per section — `HeroSection`, `ProjectsSection`, `SkillsSection`, `ExperienceSection`, `ContactSection`, `Header`, `Footer` — composed in `src/pages/Index.tsx`. A downloadable résumé and project imagery live in `public/assets/`.

## Running locally

```bash
npm install
npm run dev
```

Vite serves on `http://localhost:5173`. Other scripts: `npm run build`, `npm run preview`, `npm run lint`.

## Notes

The `public/assets/` folder carries the images, fonts and résumé PDF the site serves, which is most of the repo's size.
