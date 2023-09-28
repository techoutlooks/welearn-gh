# welearn-gh

Instructions for building the Github page at [welearn-gh](https://github.com/techoutlooks/welearn-gh). Find the original Jekyll template [here](https://github.com/sandoche/Mobile-app-landingpage-template).

weLearn is an EdTech platform from the TESS project. TESS comprises of following microservices:

- [welearn-backend]() 
- [welearn-app]()
- tess-core
- tess-auth
- tess-pay


## Test locally

1. Read: 
- [Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)

2. Run:

Note: that `bundle exec jekyll serve` won't work where. Deeper work needs performing here.
`npm start` calls Jekyll under the hoods, check `package.json`.

```shell
bundle install
npm start
```

3. Head to [http://localhost:3000/](http://localhost:3000/)

## Production

Create production build once satisfied.

```shell
npm run build
```