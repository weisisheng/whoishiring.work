# whoishiring.work

Runs the [whoishiring.work](https://www.whoishiring.work).

## Getting Started for Local Development

```sh
docker-compose up --detach
cd frontend
npm install
npm run develop
```

The frontend is served at http://localhost:8000 and the backend is served at http://localhost:8080

## Features

This is the both the present and WIP features list. If there are features you want added or modified, open a feature request issue.

- [x] Serve HTTPS traffic, and redirect HTTP to HTTPS.
- [ ] Automate populate HN data.
- [x] Update URLs for each month.
- [x] Pagination.
- [x] Client-side caching.
- [ ] Deploy using terraform or cloudformation.
- [ ] Automate deployments within GitHub.
- [ ] Add search capability.
- [ ] Add filtering capabilities: on-site, new, noted, applied, hidden, etc.
- [ ] Add sorting capabilities: posted date, popularity, view count, company.
- [ ] Add notes capability: users can manage private notes per post.
- [ ] Add capability to upvote or downvote.
- [ ] Add discussions.
- [ ] Add threaded discussions.
- [ ] Integrate with GitHub OAuth.
