
## Tanzu Application Accelerator Sample Project

This is some very important placeholder text that should describe what this project can do and how to use it.

Here are some configurable parameters:

* CONFIGURABLE_PARAMETER_1
* CONFIGURABLE_PARAMETER_2


```shell
tanzu accelerator generate-from-local \
    --accelerator-path simple-accelerator="$(pwd)" `# The path to new accelerator` \
    --server-url TANZU-APPLICATION-ACCELERATOR-URL `# Example: https://accelerator.mytapcluster.myorg.com` \
    --options '{"firstConfigurableParameter": "Parameter 1", "secondConfigurableParameterCheckbox": true, "secondConfigurableParameter":"Parameter 2"}' \
    -o "${HOME}/simple-accelerator/" `# Change this path to change where the project folder gets generated`
```

```shell
tanzu accelerator create simple-accelerator --git-repository https://github.com/robertocolella/tap-accelerators.git --git-sub-path myProject --git-branch main
``````