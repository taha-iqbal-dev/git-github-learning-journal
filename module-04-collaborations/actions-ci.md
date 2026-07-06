# GitHub Actions & Continuous Integration

## What is Continuous Integration?

Continuous Integration (CI) automatically builds and tests code whenever changes are pushed.

GitHub Actions provides built-in CI/CD automation.


## Workflow

```
Push Code

↓

GitHub Actions

↓

Build

↓

Run Tests

↓

Success

↓

Merge
```


## Workflow Location

```
.github/workflows/
```

Example

```
python.yml

build.yml

test.yml
```


## Benefits

- Automated testing

- Faster development

- Detect bugs early

- Better software quality