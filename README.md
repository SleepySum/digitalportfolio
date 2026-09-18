# Sumit Bhoi — Portfolio

My personal portfolio site: https://sumit-bhoi-portfolio.vercel.app

It's a single static page. Plain HTML, Tailwind from the CDN, and vanilla JS all in one file, so there's no build step.

## What's in it

- Scroll-driven zoom effect on the hero
- Custom cursor with trailing physics (desktop only — touch devices get the normal cursor)
- Canvas animations inside each project card
- Ambient background sound synthesized with the Web Audio API, no audio files
- Contact form handled by FormSubmit. Email field only accepts @gmail.com addresses, checked both by HTML validation and in the submit handler before anything is sent

## Projects

| Project | What it is | Links |
|---|---|---|
| LaLiga Player Value Predictor | ML web app that predicts 2024-25 La Liga player market values from season performance data | [app](https://laliga-player-value-estimator.vercel.app), [code](https://github.com/SleepySum/LaLiga_Player_Prediction) |
| PhysX | Multi-body planetary gravity simulation with real-time orbital mechanics | [app](https://physx.vercel.app), [code](https://github.com/SleepySum/PhysX) |
| Takrar | Platform concept for turning complaints and feedback into structured resolutions | architecture only |
| Gravity Well | Canvas particle system driven by radial attraction and velocity damping | [app](https://gravity-well-sooty.vercel.app), [code](https://github.com/SleepySum/Gravity-Well) |

## Running locally

Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Deploying

Hosted on Vercel as a static site:

```
npx vercel --prod
```

## Contact

- Email: bhoisumit322s@gmail.com
- GitHub: https://github.com/SleepySum
- LinkedIn: https://www.linkedin.com/in/sumit-bhoi-b15a43330
- Phone: +91 88558 11810
