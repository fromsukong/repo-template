# {Repo Name}

> **Belongs to Product**: [`{product-name}`](https://github.com/fromsukong/products-dev/blob/main/products/{product-name}/prd.md)  
> **Repository URL**: [`https://github.com/fromsukong/{repo-name}`](https://github.com/fromsukong/{repo-name})  
> **Visibility**: Public  
> **Maintainer**: @fromsukong  

---

## Description
Short description of this repository and its role in the `@fromsukong` ecosystem.

## Structure
```
<repo-name>/
├── product/              # Product spec & tasks (tracked via products-dev sparse submodule)
│   ├── spec.md           # Repository specification
│   └── task/
│       ├── active/       # Active tasks (TASK-XXX-<slug>.md)
│       └── archive/      # Completed tasks
└── src/                  # Codebase source code (excluded from products-dev)
```

## Workflow
1. New work → open a TASK issue (use the `Task` issue template) and mirror it in `product/task/active/`.
2. Completed → move task file to `product/task/archive/` and close the issue.

Created from [`repo-template`](https://github.com/fromsukong/repo-template).
