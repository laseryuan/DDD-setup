1. Install Nuxt
```
read -p 'Project Name: ' PROJECT_NAME && PROJECT_NAME=${PROJECT_NAME:-nuxt-ddd} && echo $PROJECT_NAME
npx create-nuxt-app $PROJECT_NAME
cd $PROJECT_NAME
npm run dev
```
