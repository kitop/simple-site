# simple-site

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/kitop/simple-site)

## Instructions

1. Deploy to Netlify

2. Create a [build hook](https://docs.netlify.com/configure-builds/build-hooks/)

3. Trigger a build via the hook's URL, provide page content via the hook's body.
   Optionally, you can also provide a title for the deploy to be displayed in
   Netlify's UI.
   ```
     curl -X POST -d 'Hola, mundo!' -H 'Content-Type: text/plain' https://api.netlify.com/build_hooks/XXXXXXXXXXXXXXXXXXXXXXXX?trigger_title=Build+triggered+via+hook
   ```

