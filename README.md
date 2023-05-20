# workshop-uav-sims-icra2023
Webpage for the workshop on "The Role of Robotics Simulators for Unmanned Aerial Vehicles" (hosted at ICRA 2023)

The webpage uses the static site generator [Jekyll](https://jekyllrb.com/) with a custom theme based on the CSS framework [Bulma](https://bulma.io/).
on github using [jekyll-action](https://github.com/helaili/jekyll-action).

## Initial Set Up

```
gem install jekyll bundler
```

## Building/Testing

```
jekyll serve
```

And go to `http://localhost:4000` in your browser. The page will automatically update, unless `_config.yml` is changed (in which case you have to restart jekyll).

## Docker for Jekyll

As an alternative, you can also use docker to build the website in a Jekyll container

```
docker-compose up
```

## Deployment

Simply push to the main branch. The site will be deployed automatically.
