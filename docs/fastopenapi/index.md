<p align="center">
  <img src="https://raw.githubusercontent.com/mr-fatalyst/fastopenapi/master/logo.png" alt="Logo">
</p>

<p align="center">
  <b>FastOpenAPI</b> is a library for generating and integrating OpenAPI schemas using Pydantic and various frameworks.
</p>

<p align="center">
  This project was inspired by <a href="https://fastapi.tiangolo.com/">FastAPI</a> and aims to provide a similar developer-friendly experience.
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/mr-fatalyst/fastopenapi">
  <img src="https://github.com/mr-fatalyst/fastopenapi/actions/workflows/master.yml/badge.svg">
  <img src="https://codecov.io/gh/mr-fatalyst/fastopenapi/branch/master/graph/badge.svg?token=USHR1I0CJB">
  <img src="https://img.shields.io/pypi/v/fastopenapi">
  <img src="https://img.shields.io/pypi/pyversions/fastopenapi">
  <img src="https://static.pepy.tech/badge/fastopenapi" alt="PyPI Downloads">
</p>

---

## Links

- Documentation: [**Docs**](https://fastopenapi.fatalyst.dev)
- Repository: [**GitHub**](https://github.com/mr-fatalyst/fastopenapi)
- PyPi: [**FastOpenAPI**](https://pypi.org/project/fastopenapi/)

---

## Why FastOpenAPI?

It was built out of frustration with fragmented tooling and inconsistent documentation standards across frameworks. FastOpenAPI aims to bring the developer experience of FastAPI — automatic docs, validation, and schema generation — to any Python web stack, with minimal dependencies and maximum control.

FastOpenAPI is especially useful when:

- You want OpenAPI documentation without being locked into a single framework
- You need consistent API docs across a multi-service architecture
- You prefer Pydantic v2 models and want tight integration.

Most OpenAPI tools are tied to a specific framework, like FastAPI or Flask. FastOpenAPI breaks that limitation by offering a shared, flexible engine that works across:

- AioHttp
- Flask
- Falcon
- Quart
- Starlette
- Sanic
- Tornado

Instead of forcing migration to a specific stack, FastOpenAPI uses lightweight "proxy routing" to register endpoints in a FastAPI-like style — while integrating directly with your existing framework.

The library supports router composition (like FastAPI's `APIRouter`), automatic Swagger and ReDoc generation, and provides strong Pydantic v2-based typing and validation.
