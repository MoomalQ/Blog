# Static website using HUGO + Netlify
Testing deployement of hugo theme using Netlify on github pages for my personal blug. 

# Points for future reference. 

# Using Netlify
1. If the website fails to build in netlify you might be required to add `netlify.toml` file specifiying the version of hugo.
2. You have modify the base url in the `config.toml` file of your theme.

# Using Hugo theme

Hugo uses public folder to render your website. In my test case the public folder was not available, which could be generated  using. 
```
hugo server -renderToDisk

```
