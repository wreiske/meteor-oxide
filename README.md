# meteor-oxide

This is a docker compose test that runs the meteor-blaze-tutorial app using Oxide and PostgreSQL instead of MongoDB.

## What is Oxide?

[OxideDB](https://github.com/fcoury/oxide) is a translation layer that works as a MongoDB database server while using PostgreSQL's JSON capabilities as the underlying data store. Teach your PostgreSQL database how to speak MongoDB Wire Protocol!

### Getting started

```bash
git clone https://github.com/wreiske/meteor-oxide.git
cd meteor-oxide
docker-compose up -d --no-deps --build app
docker-compose up
```

Visit [http://localhost:8888](http://localhost:8888) to see the app.

## Credits

- [https://github.com/disney/meteor-base](https://github.com/disney/meteor-base)
- [https://github.com/FerretDB/example](https://github.com/FerretDB/example)

## Discussion

- [Meteor support for PostgreSQL using OxideDB / FerretDB #12150](https://github.com/meteor/meteor/discussions/12150)
