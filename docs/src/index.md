```@meta
CurrentModule = COPIERTemplate
```

# COPIERTemplate - Copier OPInionated Evolving Reusable Template

![COPIERTemplate.jl](assets/logo-wide.png)

Welcome to the documentation of COPIERTemplate.jl. This package provides a template in the [copier](https://copier.readthedocs.io) engine for a Julia package. Furthermore, it provides a wrapper around convenience calls to that package.

The main features of this package/template are:

- It provides a curated (opinionated) list of tools and best practices for Julia package development;
- It can be applied and reapplied to existing packages, allowing the updates in the template to be imported into the package;

## Using

To fully benefit from the template, there are some steps to be done **before** and **after** you generate your package.
Check the [full guide](@ref full_guide) for more details.

However, if you kinda know what you need to do, this is the TL;DR:

```julia-repl
julia> using COPIERTemplate
julia> COPIERTemplate.generate("YourPackage.jl")
```

Or, alternatively, using [copier](https://copier.readthedocs.io), run

```bash
copier copy https://github.com/abelsiqueira/COPIERTemplate.jl YourPackage.jl
```

I really recommend checking the [full guide](@ref full_guide), though.

To understand more about our motivation and what the template provides, check the [explanation page](@ref explanation).

## Getting and providing help

I hope you find this package useful. If you have any questions, requests, or comments, check the [issues](https://github.com/abelsiqueira/COPIERTemplate.jl/issues) and [discussion](https://github.com/abelsiqueira/COPIERTemplate.jl/discussions) pages.

If you would like to get involved in the COPIERTemplate growth, please check our [contributing guide](90-contributing.md). We welcome contributions of many types, including coding, reviewing, creating issues, creating tutorials, interacting with users, etc. Make sure to follow our [code of conduct](https://github.com/abelsiqueira/COPIERTemplate.jl/blob/main/CODE_OF_CONDUCT.md).

If your interest is in developing the package, check the [development guide](90-developer.md) as well.

## Contributors

```@raw html
<!-- markdown-link-check-disable -->

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://abelsiqueira.com"><img src="https://avatars.githubusercontent.com/u/1068752?v=4?s=100" width="100px;" alt="Abel Soares Siqueira"/><br /><sub><b>Abel Soares Siqueira</b></sub></a><br /><a href="#code-abelsiqueira" title="Code">💻</a> <a href="#projectManagement-abelsiqueira" title="Project Management">📆</a> <a href="#doc-abelsiqueira" title="Documentation">📖</a> <a href="#maintenance-abelsiqueira" title="Maintenance">🚧</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://tmigot.github.io"><img src="https://avatars.githubusercontent.com/u/25304288?v=4?s=100" width="100px;" alt="Tangi Migot"/><br /><sub><b>Tangi Migot</b></sub></a><br /><a href="#code-tmigot" title="Code">💻</a> <a href="#doc-tmigot" title="Documentation">📖</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

```
