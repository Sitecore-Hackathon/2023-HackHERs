# Hackathon Submission Entry form

## Team name
2023-HackHERS

## Category
Best Enhancement to Sitecore XMCloud

## Description
Sitecore XM Cloud already offers strong personalization features, but there are always ways to improve. In this module, we have integrated Sitecore Demo Team's XMCLoud based site PlaySummit with CDP & Azure cognitive Image analysis to provide enhanced personalization to our customers. With the power of AI's Image analysis, we personalize the suggestions based on the Visitior's favourite image.

The CDP Sandbox has all the features to bring this experience to the Play Summit User.

![CDP Flow Chart](docs/images/canvas.png?raw=true "canvas")

## Video link
⟹ Provide a video highlighing your Hackathon module submission and provide a link to the video. You can use any video hosting, file share or even upload the video to this repository. _Just remember to update the link below_

⟹ [Replace this Video link](#video-link)

## Pre-requisites and Dependencies

⟹ Does your module rely on other Sitecore modules or frameworks?

- Sitecore XM Cloud
  - XM Cloud Pages Personalize
  - XM Cloud Pages Analyze
- Sitecore JavaScript Services (JSS)
- Next.js
- Vercel
- Tailwind CSS
- Storybook

The Demo is local container based. Once built, it integrates with the following composable stack technologies
- CDP
- Personalize

## Installation instructions

Follow the instructions in this document [Docker](docs/docker.md) to bring up the site.

## Usage instructions

1. Browse to the Url https://www.xmcloudcm.localhost/about-us

2. Fill out the form with your favourite image url. (https://th.bing.com/th/id/R.d8c55c2fa5917bd6c52e252ccdecd2f8?rik=kIqbViHvFCzQSQ&pid=ImgRaw&r=0)
   ![Form](docs/images/form.png?raw=true "Request Form with Image Url")

3. Submit it

4. On refresh, you will see a popup analyzing your favourite image.
   ![outdoor](docs/images/demo-outdoor.png?raw=true "demo outdoor")

5. Retry with another Url. (https://th.bing.com/th/id/OIP.MpTK7yhGKxwZhHnl3ArthwHaHa?pid=ImgDet&rs=1)
   ![tech](docs/images/demo-tech.png?raw=true "demo tech")