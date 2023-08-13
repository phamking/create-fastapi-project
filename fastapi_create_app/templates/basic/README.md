# FastAPI Project with `new-fastapi-app`

This is a FastAPI project initialized using [`new-fastapi-app`](https://github.com/allient/new-fastapi-app), designed to provide a quick start for building APIs with [FastAPI](https://fastapi.tiangolo.com/).

## Getting Started

The commands in this documentation can be customized on the **Makefile**. It can be started with and without docker.

First, make sure you have all packages installed:

```bash
make install
```


Run the server:
```bash
# Run locally without docker
make run-app
# or
# Run locally with docker in dev mode and force build
make run-dev-build
# or
# Run locally with docker in dev mode
make run-dev-build
# or
# Run locally with docker in prod mode
make run-prod
```

Open [http://localhost:8000/docs](http://localhost:8000/docs) with your browser to see the result.

You can start editing the server by modifying `app/main.py`.

## Learn More

To learn more about Fastapi, take a look at the following resources:

- [Fastapi Documentation](https://fastapi.tiangolo.com/).
- [fastapi-alembic-sqlmodel-async](https://github.com/jonra1993/fastapi-alembic-sqlmodel-async).
- [full-stack-fastapi-postgresql](https://github.com/tiangolo/full-stack-fastapi-postgresql).
- [sqlmodel-tutorial](https://sqlmodel.tiangolo.com/tutorial/fastapi/).
- [asyncer-tutorial](https://asyncer.tiangolo.com/tutorial/).
- [fastapi-pagination](https://github.com/uriyyo/fastapi-pagination).
- [fastapi-best-practices](https://github.com/zhanymkanov/fastapi-best-practices).
- [awesome-fastapi](https://github.com/mjhea0/awesome-fastapi).

## Why use Create FastAPI App?

`new-fastapi-app` provides a streamlined way to kickstart your FastAPI projects. Here are some compelling reasons to choose it for your project setup:

### Interactive Experience

Running `pip install new-fastapi-app@latest` (with no arguments) launches an interactive experience that guides you through the process of setting up your project. This interactive approach simplifies the initial configuration and gets you started quickly.

### Zero Dependencies

`new-fastapi-app` has been designed to be lightweight and efficient. It requires zero external dependencies, ensuring that your project remains unburdened by unnecessary packages.

### Reliability and Maintenance

`new-fastapi-app` is officially maintained by the [Allient development team](https://www.allient.io/). It is well-tested and aligns with best practices, ensuring that it functions as expected and remains up to date with FastAPI's releases.

By choosing `new-fastapi-app`, you streamline your initial project setup, leverage reliable patterns, and enjoy the convenience of a tool tailored for FastAPI development.


We love ❤️ [FastAPI](https://fastapi.tiangolo.com/) and its ecosystem. You can check out the [new-fastapi-app GitHub repository](https://github.com/allient/new-fastapi-app) - your feedback and contributions are welcome!