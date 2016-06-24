Networks
=================

Ok, you have multi-container app now, and you know how to link containers together.
But we should remember container has to be up&running to link it to another
container. What if your db container crash? You would have to rebuild php as
well.

## Networks for the rescue!

Docker introduce networking tool which soon will take over linking functionality.
You can create networks and add containers to those networks so they can connect
each other. Let's build simple app with two networks:

- back-tier
- front-tier

First one groups all containers vital for our application, like php and db,
while second one contain only containers which are relevant for exposing app to
the outside world.

You can build your application as always:
```
docker-compose up -d db php app
```

One change - we run only containers we need, skipping drush.

You can still run drush on demand:
```
docker-compose run --rm drush bash
```
