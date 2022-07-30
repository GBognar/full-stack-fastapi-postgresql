# full-stack-fastapi-postgresql

This template is based on the FastAPI template/cookiecutter template 
[`whythawk-full-stack-fastapi-postgresql`](https://github.com/whythawk/full-stack-fastapi-postgresql),
which is a modernized version of the *original canonical* FastAPI template
[`tiangolo-full-stack-fastapi-postgresql`](https://github.com/tiangolo/full-stack-fastapi-postgresql).

The current template is at https://git.seisachtheia.com/kedvenczrt/02-full-stack-fastapi-postgresql/
which is tracked in GitHub at https://github.com/GBognar/full-stack-fastapi-postgresql

More information about the *generated*/to-be-generated project is/will be in the
README of the *generated* project, but it can be previewed in the 
[README of the template](./%7B%7Bcookiecutter.project_slug%7D%7D/README.md) and the
[original README of the template](./%7B%7Bcookiecutter.project_slug%7D%7D/README.orig.md)

*   The copy of the original README is at [`README.orig.md`](./README.orig.md)
*   The *original* `README` for the generator: https://github.com/whythawk/full-stack-fastapi-postgresql
*   The README for the *tiangolo* generator is at: https://github.com/tiangolo/full-stack-fastapi-postgresql

## Starting the generated containers

The front-end uses a Nuxt-based application (as a default, but not
planned to use it) built using yarn. To build it, first run 
`npm install` locally.

```shell
cd frontend
npm install
cd ..
docker-compose up -d
```