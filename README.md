# Raghav Sharma — Portfolio

Personal portfolio of **Raghav Sharma**, Computer Science student at Bennett University (Class of 2028). Built with Next.js 16, GSAP, Three.js, and CSS Modules.

**GitHub:** [Raghav-prog-max](https://github.com/Raghav-prog-max) &nbsp;|&nbsp; **LinkedIn:** [raghav-sharma](https://www.linkedin.com/in/raghav-sharma-948b32324)

## Stack

| Layer      | Technology                                       |
| ---------- | ------------------------------------------------ |
| Framework  | Next.js 16.2 (App Router, React Compiler)        |
| Animations | GSAP 3 + Three.js                                |
| Styling    | CSS Modules + Tailwind v4 (tokens only)          |
| Icons      | react-icons                                      |
| Fonts      | Geist, Baloo 2, Dancing Script (via next/font)   |

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

To build for production:

```bash
npm run build
npm start
```

## Content

All personal information lives in `data/profile.json` — name, bio, experience, projects, certifications, and social links. Site copy (section taglines, CTA text) lives in `data/content.json`. Design tokens live in `app/globals.css`, and the canonical site URL in `lib/siteConfig.js`.

Media lives in `public/assets/` — hero portrait, about photo/video, footer media, and one `project-*.png` per project in `profile.json`.

## Deployment

Connect the repository to [Vercel](https://vercel.com) and it deploys automatically with zero configuration.

## Credits

Design adapted from [cinematic-portfolio](https://github.com/VaibhavKhushalani/cinematic-portfolio) by [Vaibhav Khushalani](https://www.linkedin.com/in/vaibhav-khushalani-760217136), used under its MIT license.
