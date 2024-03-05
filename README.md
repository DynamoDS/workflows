# Workflows

Collection of reusable workflows and compostite actions

## Reusable Workflows

| workflow | description | example workflow | status |
| -- |  -- | -- | -- |
| [greeting.yml](.github/workflows/greeting.yml) | sample workflow | [greeting_workflow.yml](.github/workflows/greeting_workflow.yml) | [![Greeting (Workflow)](https://github.com/DynamoDS/workflows/actions/workflows/greeting_workflow.yml/badge.svg)](https://github.com/DynamoDS/workflows/.github/workflows/greeting_workflow.yml) |
| [msbuild.yml](.github/workflows/msbuild.yml) | Build a project with msbuild | [msbuild_workflow.yml](.github/workflows/msbuild_workflow.yml) | [![MSBuild (Workflow)](https://github.com/DynamoDS/workflows/actions/workflows/msbuild_workflow.yml/badge.svg)](https://github.com/DynamoDS/workflows/actions/workflows/msbuild_workflow.yml) |
| [npm_build.yml](.github/workflows/npm_build.yml) | Build a project with npm | [npm_build_workflow.yml](.github/workflows/npm_build_workflow.yml) | [![NPM Build (Workflow)](https://github.com/DynamoDS/workflows/actions/workflows/npm_build_workflow.yml/badge.svg)](https://github.com/DynamoDS/workflows/actions/workflows/npm_build_workflow.yml) |

## Composite Actions

| action | description | example workflow | status |
| -- |  -- | -- | -- |
| [greeting](.github/actions/greeting/action.yml) | sample workflow | [greeting_action.yml](.github/workflows/greeting_action.yml) | [![Greeting (Action)](https://github.com/DynamoDS/workflows/actions/workflows/greeting_action.yml/badge.svg)](https://github.com/DynamoDS/workflows/actions/workflows/greeting_action.yml) |
| [msbuild](.github/actions/msbuild/action.yml) | Build a project with msbuild | [msbuild_action.yml](.github/workflows/msbuild_action.yml) | [![MSBuild (Action)](https://github.com/DynamoDS/workflows/actions/workflows/msbuild_action.yml/badge.svg)](https://github.com/DynamoDS/workflows/actions/workflows/msbuild_action.yml) |
| [npm_build](.github/actions/msbuild/action.yml) | Build a project with npm | [npm_build_action.yml](.github/workflows/npm_build_action.yml) | [![NPM Build (Action)](https://github.com/DynamoDS/workflows/actions/workflows/npm_build_action.yml/badge.svg)](https://github.com/DynamoDS/workflows/actions/workflows/npm_build_action.yml) |

More info:

- [Reusing Workflows](https://docs.github.com/en/actions/using-workflows/reusing-workflows)
- [Creating a composite action](https://docs.github.com/en/actions/creating-actions/creating-a-composite-action)
