# AI Image Generator — by Aikaksh Singh Routela

**Live Demo:** [https://ai-art-generator-ochre.vercel.app](https://ai-art-generator-ochre.vercel.app) | **Source Code:** [https://github.com/Aikaksh-Singh-Routela/ai-art-generator](https://github.com/Aikaksh-Singh-Routela/ai-art-generator)

A production-ready AI image generator that turns text prompts into custom images using the community-powered AI Horde network. Built, customized, and deployed as a personal portfolio project.

## 📸 Examples

Here are images generated using this tool:

| Image 

| ![Leopard](https://raw.githubusercontent.com/Aikaksh-Singh-Routela/ai-art-generator/main/public/screenshots/leopard.png)
 
| ![Wolf](https://raw.githubusercontent.com/Aikaksh-Singh-Routela/ai-art-generator/main/public/screenshots/wolf.png) 
*Replace the image links above with your own screenshots after uploading them to `public/screenshots/`*

| ![Pink hair anime girl](https://raw.githubusercontent.com/Aikaksh-Singh-Routela/ai-art-generator/main/public/screenshots/pink hair anime girl.png) 
*Replace the image links above with your own screenshots after uploading them to `public/screenshots/`*

| ![Smiling old man](https://raw.githubusercontent.com/Aikaksh-Singh-Routela/ai-art-generator/main/public/screenshots/smiling old man.png) 
*Replace the image links above with your own screenshots after uploading them to `public/screenshots/`*

## 🛠️ What I Built

- **Web Application:** Customized Next.js front-end with my own branding
- **API Integration:** Connected to AI Horde REST API for async image generation
- **GPU Worker:** Configured and run my own GTX 1660 worker that contributes processing power to the network
- **Deployment:** Hosted live on Vercel with continuous deployment

## 💻 Tech Stack

| Category | Technologies |
|----------|--------------|
| Framework | Next.js 14, React |
| Language | TypeScript |
| Styling | Tailwind CSS |
| API | AI Horde REST API |
| Deployment | Vercel |
| Version Control | Git, GitHub |

## 🖥️ My GPU Worker

Part of this project includes running a dedicated worker on my own PC (GTX 1660, 16GB RAM). This worker:
- Processes image generation requests from other users
- Earns Kudos (priority currency) for faster generations
- Contributes to a free, open source community network

## Table of Contents

- [Intro](#intro)
- [Setup](#setup)
  - [Requirements](#requirements)
  - [Installing](#installing)
- [Usage](#usage)
  - [Development](#development)
  - [Production](#production)
- [Contributions](#contributions)
- [Acknowledgements](#acknowledgements)

## Intro

ArtBot is a front-end web client designed for interacting with the [AI Horde](https://aihorde.net/) open source distributed cluster -- a group of GPUs running Stable Diffusion whose processing time has been kindly donated by an enthusiastic community of volunteers.

ArtBot is built using [Next.js 14](https://nextjs.org/) and [Typescript](https://www.typescriptlang.org/). It uses client-side technologies such as IndexedDB and LocalStorage APIs in order to securely and privately store the AI generated images you've created using the cluster within your own web browser.

## Setup

### Requirements

- node `>= 18.18.0`
- npm `>= 9.5.1`

Most of these steps should be applicable to Linux, MacOS, or Windows environments.

Installing various versions of Node.js on your machine can be tricky. I am a big fan of [nvm](https://github.com/nvm-sh/nvm), which allows you to run multiple isolated versions of Node.js on your machine with ease.

Using `nvm`, you can install Node like this:

```bash
> nvm install v18.18.0
> nvm alias default node
> node -v # Checks which version of Node is currently running
