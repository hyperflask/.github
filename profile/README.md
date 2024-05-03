# The Hyperflask project

Full stack, batteries-included, Python framework to build, deploy and run websites and web apps with as little boilerplate as possible. All the tech choices have been made so you can focus on building your product, not your tech stack.

Checkout the [hyperflask](https://github.com/hyperflask/hyperflask) repository for a more detailed explainer and getting started instructions.

Hyperflask combines multiple Flask extensions and frontend libraries into a seamless experience. This page lists all projects and components used as part of the Hyperflask project.

## Backend libraries developed as part of the Hyperflask project

**Each of these projects is usable standalone outside of Hyperflask!**

### Flask extensions

| Name | Description | Status |
| --- | --- | --- |
| [Flask-SQLORM](https://github.com/hyperflask/flask-sqlorm) | Flask integration of [sqlorm](https://github.com/hyperflask/sqlorm) | ✅ |
| [Flask-Configurator](https://github.com/hyperflask/flask-configurator) | File based configuration | ✅ |
| [Flask-Assets-Pipeline](https://github.com/hyperflask/flask-assets-pipeline) | Modern asset pipeline | ✅ |
| [Flask-Babel-Plus]() | [Flask-Babel](https://github.com/python-babel/flask-babel) (i18n) with additional utilities | 🚧 |
| [Flask-Geo](https://github.com/hyperflask/flask-geo) | Geolocation using [Maxmind](https://www.maxmind.com/en/geoip-databases) | ✅ |
| [Flask-Files](https://github.com/hyperflask/flask-files) | [Fsspec](https://filesystem-spec.readthedocs.io/en/latest/) based files management (upload, storage and image manipulation) | 🚧 |
| [Flask-Pages](https://github.com/hyperflask/flask-pages) | File-based routing with a new file format combining python and jinja template in a single file | 🚧 |
| [Flask-Collections](https://github.com/hyperflask/flask-collections) | Manage collections of static content | 🚧 |
| [Flask-Stream](https://github.com/hyperflask/flask-stream) | Update pages in realtime from the backend | 🚧 |
| [Flask-Mercure](https://github.com/hyperflask/flask-mercure) | Push events via server-sent events using the [Mercure](https://mercure.rocks) protocol | ✅ |
| [Flask-Mailman-Templates](https://github.com/hyperflask/flask-mailman-templates) | Email templates for [Flask-Mailman](https://github.com/waynerv/flask-mailman) | 🚧 |
| [Flask-Sentry](https://github.com/hyperflask/flask-sentry) | Sentry and Spotlight integration | ✅ |
| [Flask-Super-Macros](https://github.com/hyperflask/flask-super-macros) | Better macro management for Jinja | 🚧 |

### Jinja extensions

| Name | Description | Status |
| --- | --- | --- |
| [Jinja-Super-Macros](https://github.com/hyperflask/jinja-super-macros) | Better macro management for Jinja | 🚧 |
| [Jinja-Layout](https://github.com/hyperflask/jinja-layout) | Easier layout handling for Jinja | ✅ |
| [Jinja-WTForms](https://github.com/hyperflask/jinja-wtforms) | Create [WTForms](https://wtforms.readthedocs.io) classes from Jinja templates | 🚧 |
| [Jinja-Page-Modules](https://github.com/hyperflask/jinja-page-modules) | Mix code file format combining python code and a jinja template | 🚧 |
| [Jinja-Frontmatter](https://github.com/hyperflask/jinja-frontmatter) | Frontmatter support for jinja templates | 🚧 |

### Other libraries

| Name | Description | Status |
| --- | --- | --- |
| [sqlorm](https://github.com/hyperflask/sqlorm) | SQL focused ORM | ✅ |

### Optional projects developed as part of Hyperflask

| Name | Description | Status |
| --- | --- | --- |
| [Flask-Stripe-Checkout](https://github.com/hyperflask/flask-stripe-checkout) | Handle payments and subscriptions using Stripe Checkout | ✅ |

## Third-party Flask extensions used by Hyperflask

| Name | Description |
| --- | --- |
| [Frozen-Flask](https://github.com/Frozen-Flask/Frozen) | Generate a static website from your Flask app |
| [Flask-Talisman](https://github.com/wntrblm/flask-talisman) | HTTP security headers for Flask |
| [Htmx-Flask](https://github.com/sponsfreixes/htmx-flask) | HTMX integration for Flask |
| [Flask-Mailman](https://github.com/waynerv/flask-mailman) | Send emails |
| [Flask-Login](https://github.com/maxcountryman/flask-login) | User session management |
| [Flask-Babel](https://github.com/python-babel/flask-babel) | I18n (bundled as part of Flask-Babel-Plus) |

## Third party frontend libraries used by Hyperflask

| Extension | Description |
| --- | --- |
| [htmx](https://htmx.org/) | Easy AJAX requests from HTML |
| [daisyUI](https://daisyui.com/) | UI component library using Tailwind |
| [Bootstrap Icons](https://icons.getbootstrap.com/) | Icon pack |

## Frontend libraries developed as part of the Hyperflask project 

| Project | Description | Status |
| --- | --- | --- |
| [htmx-pwa](https://github.com/hyperflask/htmx-pwa) | Easily support PWA features for your htmx sites | 🚧 |
| [htmx-active-url](https://github.com/hyperflask/htmx-active-url) | Highlight the currently active url | ❌ |

*(also usable independently)*

## Supporting projects part of Hyperflask

| Project | Description | Status |
| --- | --- | --- |
| [hyperflask-docs](https://github.com/hyperflask/hyperflask-docs) | Documentation | ❌ |
| [hyperflask-cookiecutter](https://github.com/hyperflask/hyperflask-cookiecutter) | Template for new Hyperflask projects | 🚧 |
| [hyperflask-cli](https://github.com/hyperflask/hyperflask-cli) | CLI to create and manage Hyperflask projects | 🚧 |
| [hyperflask-site](https://github.com/hyperflask/hyperflask-docs) | [hyperflask.io](https://hyperflask.io) | ❌ |
| [hyperflask-studio](https://github.com/hyperflask/hyperflask-studio) | All-in-one web console (CMS, IDE, Analytics, ...) | ❌ |