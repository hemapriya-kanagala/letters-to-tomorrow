<div align="center">

# 💌 Letters to Tomorrow

### A June Solstice Story

*A narrative web game about unfinished letters, quiet moments, and the things we choose to carry into tomorrow.*

[🎮 Play the Game](https://letters-to-tomorrow-game.vercel.app/) • [📝 DEV Article](https://dev.to/hemapriya_kanagala/letters-to-tomorrow-a-june-solstice-game-about-the-things-we-carry-into-tomorrow-1lnf)

</div>

---

## Table of Contents

* [About](#about)
* [Core Features](#core-features)
* [Design Philosophy](#design-philosophy)
* [Technology Stack](#technology-stack)
* [Google AI Usage](#google-ai-usage)
* [Privacy First](#privacy-first)
* [Project Structure](#project-structure)
* [Running Locally](#running-locally)
* [June Solstice Game Jam](#june-solstice-game-jam)
* [Learn More](#learn-more)
* [Feedback & Discussion](#feedback--discussion)

---

<a id="about"></a>

## About

**Letters to Tomorrow** is a narrative web game created for the **June Solstice Game Jam**.

A sudden summer storm has scattered the town's annual letters to the future, leaving many of them unfinished just before sunset.

You play as the Postmaster working the twilight shift on the longest day of the year. Your role is to read these letters, understand the people behind them, and help them find the words they were trying to carry into tomorrow.

Each letter belongs to someone standing at a different point in life. A baker opening his first shop. A musician wondering whether she deserves to be heard. A teacher reflecting on a lesson that stayed with him. Someone remembering a small act of kindness years later. Someone trying to figure out what comes next.

As the day progresses, you help these voices find their endings before the sun finally sets. If none of the provided endings feel right, you are free to write your own.

At the end of your shift, one final envelope remains on the desk.

This one belongs to you.

---

<a id="core-features"></a>

## Core Features

At its heart, Letters to Tomorrow is a game about helping people complete unfinished thoughts.

Players move through four phases of the solstice - Morning Light, Midday Sun, Afternoon Gold, and Sunset Glow - meeting different characters and stories along the way. Every letter presents a missing final thought that can be completed through multiple choices or through words written entirely by the player.

Progression is intentionally flexible. Players only need to help a minimum number of voices before moving into the next phase of the day, but they are always free to stay longer and complete additional letters if they wish. Only the letters they choose to finish are sealed and carried forward into tomorrow.

Throughout the journey, hidden fragments of a mystery letter can be discovered and assembled, eventually revealing a message left behind by a previous Postmaster. Every completed story, custom response, discovered fragment, and personal reflection is preserved inside a Review Book that can be revisited at any time.

The experience concludes with a final empty envelope addressed to Tomorrow, inviting players to write something of their own.

The game also includes automatic local saving, a built-in How to Play guide, an FAQ section, responsive layouts for mobile and desktop devices, and accessibility-focused design choices intended to make the experience comfortable to read and navigate.

---

<a id="design-philosophy"></a>

## Design Philosophy

Most games ask players to move faster.

Letters to Tomorrow asks players to slow down.

I intentionally chose not to include scores, timers, combat, failure states, or competitive mechanics. The goal is not to win. The goal is to listen.

The June Solstice represents a turning point. The longest day of the year eventually becomes evening. Time moves forward whether we are ready or not.

That idea became the foundation of the game.

Each character is trying to carry something into tomorrow: a lesson, a hope, a memory, a fear, a question, or a reminder. By helping them complete their letters, players are ultimately preparing for the same question themselves.

What do you want to carry forward?

---

<a id="technology-stack"></a>

## Technology Stack

The project was intentionally designed as a lightweight, fully client-side experience.

It is built using HTML5, CSS3, Vanilla JavaScript, Tailwind CSS, and the browser's Local Storage API. The game is deployed through Vercel and requires no backend infrastructure, database, account system, or server-side processing.

Everything lives inside a single HTML file. This approach keeps the project easy to maintain, easy to deploy, and accessible across a wide range of devices.

---

<a id="google-ai-usage"></a>

## Google AI Usage

Google AI was used throughout development as a coding and implementation partner.

It helped with frontend implementation, responsive design, accessibility improvements, animation refinement, onboarding content, FAQ review, interface polishing, and general development troubleshooting.

The game's concept, narrative structure, themes, characters, and letters were created by me. AI occasionally provided implementation support and editing feedback, but the stories themselves came from my own writing, experiences, and creative direction.

---

<a id="privacy-first"></a>

## Privacy First

Privacy was one of the most important design decisions in the project.

Everything written by the player remains on their own device. Progress, completed letters, custom responses, and personal reflections are stored locally using the browser's Local Storage API.

Nothing is uploaded to a server. Nothing is collected, transmitted, or shared.

The final letter to Tomorrow belongs entirely to the player.

---

<a id="project-structure"></a>

## Project Structure

```text
index.html
├── HTML Structure
├── Narrative Content
├── CSS Styling & Animations
├── Game Logic
├── Phase Progression System
├── Save / Load System
├── Review Book
├── Mystery Fragment System
├── Help & FAQ System
└── Accessibility Features
```

The entire game is intentionally contained within a single file to keep deployment and maintenance simple.

---

<a id="running-locally"></a>

## Running Locally

Clone the repository:

```bash
git clone https://github.com/hemapriya-kanagala/letters-to-tomorrow.git
```

Navigate into the project directory:

```bash
cd letters-to-tomorrow
```

Then simply open `index.html` in your browser.

No installation is required.

No build step is required.

No dependencies need to be installed.

---

<a id="june-solstice-game-jam"></a>

## June Solstice Game Jam

This project was created for the **June Solstice Game Jam**.

The game explores themes of time, transition, belonging, reflection, kindness, hope, and personal growth through the lens of the longest day of the year.

It also includes **The Blue Envelope**, a special story inspired by Alan Turing's legacy and the importance of remaining true to yourself, even when you feel different from those around you.

---

<a id="learn-more"></a>

## Learn More

This README focuses on the game itself, but there is a much larger story behind the project.

If you would like to learn more about the design process, the June Solstice inspiration, the tribute to Alan Turing, how Google AI was used during development, the real-life story behind Hema's letter, and the challenge of creating and narrating the demo video, you can read the full write-up below.

👉 **[DEV Article](https://dev.to/hemapriya_kanagala/letters-to-tomorrow-a-june-solstice-game-about-the-things-we-carry-into-tomorrow-1lnf)**

👉 **[Play the Game](https://letters-to-tomorrow-game.vercel.app/)**

---

<a id="feedback--discussion"></a>

## Feedback & Discussion

If you would like to share feedback, discuss the letters, suggest new stories, or talk about the project, please visit the DEV article linked above.

I would love to hear which parts of the game resonated with you and what you would like to see improved in future versions.

Thank you!
