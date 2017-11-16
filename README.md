# Muzooka Public Demos

- Demos are hosted using [Github Pages](https://pages.github.com/)
- Push to `master` to deploy
- Demos will be available at http://demos.muzooka.com 
- Make sure to *use a trailing /* when linking to a demo, otherwise the user will be redirected to the Github page:
  - :white_check_mark: http://demos.muzooka.com/brooklyn-bowl/
  - :x: http://demos.muzooka.com/brooklyn-bowl
- Content is served over Cloudfront and can be accessed directly at https://d3lxix2ia4mrrg.cloudfront.net/ if you need HTTPS
- Demos can also be accessed at https://muzooka.github.com/muzooka-demos/ which is another good way to get https
- Demos can take 5 or more minutes to prop
- If you end up getting a 404 that might get cached in Cloudfront, in which case you will need to create an invalidation
