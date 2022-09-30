**<h1 style="text-align: center">Dartware Blog</h1>**

Project that resembles a blog application. It is sepparated between the **database**, [**backend**](https://github.com/viniciusvviterbo/blog_backend) (or `API`), and the [**frontend**](https://github.com/viniciusvviterbo/blog_frontend).

# Setting the project up

## Docker Compose

Clone this repository and execute:

```bash
docker compose up -d
```

## CLI

It is also possible to run each of the parts manually, be it through the CLI or individual docker containers. For that, set up a Mongo DB container by executing:

```bash
docker run --rm -d -p 27017:27017 -v $PWD/blog_database:/data/db --name blog_database mongo
```

Afterwards, follow the instructions from the repositories "Setting the project up" segments:

1. [**Backend**](https://github.com/viniciusvviterbo/blog_backend#cli)
2. [**Frontend**](https://github.com/viniciusvviterbo/blog_frontend#cli)

# Usage

Feel free to browse the frontend at [http://localhost:4444](http://localhost:4444), and to access the API endpoints at [http://localhost:4400](http://localhost:4400).

---

**[GNU AGPL v3.0](https://www.gnu.org/licenses/agpl-3.0.html)**
