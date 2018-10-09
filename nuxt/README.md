# Install
1. Install Nuxt
```
read -p 'Project Name: ' PROJECT_NAME && PROJECT_NAME=${PROJECT_NAME:-nuxt-ddd} && echo $PROJECT_NAME
npx create-nuxt-app $PROJECT_NAME
cd $PROJECT_NAME
npm run dev
```

1. Install crconsole
```
sudo npm install crconsole
```

# DDD
1. Start the chrome browser
```
google-chrome --remote-debugging-port=9222 --user-data-dir=/tmp/chrome-debug
```

1. Navigate to the development page
localhost:3000

1. Debug
Put debugger in client code and referesh page. i.e. Put following code to script
tag in vue component
```
  mounted: function () {
    this.$nextTick(function () {
      let x = 1
      debugger
    })
  }
```

1. Connect crconsole
```
crconsole
.tabs
.switch  # to the page tab
```

