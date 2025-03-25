<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">Docs Editor</h3>

  <p align="center">
    Google-Docs inspired, a light docx editor!
    <br />
    <a href=""><strong>Visit »</strong></a>
    <br />
    <br />
  </p>
</div>

<!-- ABOUT THE PROJECT -->

## About The Project

A Google Docs inspired awesome docs editor. Built with React, Quill, Tailwind CSS , Socket.io and MongoDB.

Here's what's available:

- Multi user collaborative functionality using websockets and node/express backend server
- Advanced markdown editor with features like text alignment, text sizing images, colors, list headings and many more.
- Easily access and manage your documents (documents are saved to database)




#### Why is the deployed project is not working?
While I'm excited to share Docs with you, its current deployment on Render's free tier has limitations due to the inherent restrictions of free hosting platforms. Unfortunately, free hosting options does not offer robust websocket functionality, which is crucial for  Docs' full potential.

I'm currently unable to invest in paid hosting for the project. Therefore, I kindly request you to test OG Docs' functionalities directly on your local machine. This will allow you to experience the full range of features without the limitations of free hosting.

## Getting Started

### Prerequisites

Install dependencies in `/api`
and `/client`

```sh
npm install
```

Environment variables in `api/.env`
```
DB_USER= MongoDB Username 
DB_PASS= MongoDB Password
CLIENT_URL= Client Origin (eg. example.com)
```

Environment variables in `client/.env`
```/
VITE_API_URL= Backend endpoint
`````

<!-- ROADMAP -->

## Roadmap

- [ ] Skeleton and bar loading
- [ ] Make responsive 
- [ ] Header

### Future Plans
- [ ] Add login & signup (google auth)
- [ ] Homepage : Showcase created docs, with links. Docs should be sorted by date of completion


