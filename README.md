## Login form with Vue

[![Build Status](https://travis-ci.org/peterdee/vue-login-form-frontend.svg?branch=stage)](https://travis-ci.org/peterdee/vue-login-form-frontend)

[![Known Vulnerabilities](https://snyk.io/test/github/peterdee/vue-login-form-frontend/badge.svg?targetFile=package.json)](https://snyk.io/test/github/peterdee/vue-login-form-frontend?targetFile=package.json)

Backend project: [`vue-login-form-backend`](https://github.com/peterdee/vue-login-form-backend)

Stack: [`Vue`](https://vuejs.org), [`Vuex`](https://vuex.vuejs.org/) [`Vue Router`](https://router.vuejs.org), [`Axios`](https://github.com/axios/axios), [`Bootstrap`](https://getbootstrap.com)

**DEV**: http://localhost:8080

**STAGE**: https://vue-login-form-frontend.herokuapp.com

Hardcoded user credentials:
```text
login: user@test.com
password: qwerty123
```

### Deploy

- `git clone https://github.com/peterdee/vue-login-form-frontend`
- `cd ./vue-login-form-frontend`
- `nvm use 13.2` (please see the actual Node version in [package.json](package.json) file)
- `npm i` (use `npm i --prod` for `stage` / `production`)

### Launch

Development:

- `npm run serve`

Stage / production:

- `npm run build`

### Heroku

The `stage` branch is deployed to [Heroku](https://herokuapp.com) automatically
