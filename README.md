# deepclassifier project


# Workflow
1. update config.yaml
2. update secrets.yaml [if available]
3. update params.yaml
4. update the entity
5. update configuration manager in src config
6. update components
7. update pipeline
8. test run pipeline stage
9. run tox for testing the package
10. update dvc.yaml
11. run "dvc repro" for running all the stages in pipeline