# ANM-butterfly-schema

Schema describing butterfly monitoring data, habitat data, and trait data

## Website

[https://ANM-Butterfly-Network.github.io/ANM-butterfly-schema](https://ANM-Butterfly-Network.github.io/ANM-butterfly-schema)

## Repository Structure

* [examples/](examples/) - example data
* [project/](project/) - project files (do not edit these)
* [src/](src/) - source files (edit these)
  * [anm_butterfly_schema](src/anm_butterfly_schema)
    * [schema](src/anm_butterfly_schema/schema) -- LinkML schema
      (edit this)
    * [datamodel](src/anm_butterfly_schema/datamodel) -- generated
      Python datamodel
* [tests/](tests/) - Python tests

## Developer Documentation

<details>
Use the `make` command to generate project artefacts:

* `make all`: make everything
* `make deploy`: deploys site
</details>

## Credits

This project was made with
[linkml-project-cookiecutter](https://github.com/linkml/linkml-project-cookiecutter).
