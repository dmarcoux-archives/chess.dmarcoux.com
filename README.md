# <a href="https://github.com/dmarcoux/chess.dmarcoux.com">dmarcoux/chess.dmarcoux.com</a>

![Netlify Status](https://api.netlify.com/api/v1/badges/dc3a2951-75a5-4502-b3bd-3fff6be780f0/deploy-status)

## Development

Built with [Vue.js 2](https://vuejs.org/). The chessboard is from [vue-chessboard](https://github.com/vitogit/vue-chessboard).

### Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

## Production

### Host

The application is hosted on [Netlify](https://www.netlify.com/) with the following settings:
- Build command: `npm run build`
- Publish directory: `dist`

[Deploy notifications](https://docs.netlify.com/site-deploys/notifications/#github-pull-request-comments)
are commenting in pull requests whenever the deploy preview is ready. The notification's event is `Deploy Preview succeeded`.

### Domain

The domain `dmarcoux.com` is managed on [Cloudflare](https://www.cloudflare.com/) with a `CNAME` record for `chess`
pointing to the default site name provided by Netlify. A custom domain is then set for `chess.dmarcoux.com` on Netlify.
