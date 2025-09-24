<div><img src="https://github.com/hyperflask/hyperflask/raw/main/assets/banner.svg" width="100%"></div>
<hr>
<div align="center">

**Full stack Python web framework and infrastruture to build, deploy and run websites and web apps with as little boilerplate as possible. All the tech choices have been made so you can focus on building your product, not your tech stack.**

</div>

The goal of the Hyperflask stack is to provide a single unified web stack, built on top of Python and proven technologies, where all components have been designed to work together seamlessly.

It intends to provide solo devs and small teams a solution that allows them to build and operate a website/web app with minimal boilerplate and overhead. All the focus can go to work on the actual product.

Key goals:

 - Full stack experience, from dev environment to UI framework to deployment
 - Backend driven with static content generation when needed
 - Great developer experience and high productivity
 - All the tech choices have been made so you don't need to ask yourself tech stack questions
 - Fully Open-Source stack that is 100% self-hostable if desired (no dependencies on cloud services)
 - Use proven technologies and rely on standards as much as possible
 - Built for pragmatical but professional production apps
 - Limit "magic", things should be understandable, evolvable and maintanable
 - Beginner friendly but well engineered for advanced use cases
 - Optimized for solo developers and small teams
 - Can run on cheap machines or VMs from any server/cloud providers

Visit [hyperflask.dev](https://hyperflask.dev) for more information

## Core projects

| Project | Description | Key technologies | Status |
| --- | --- | --- | --- |
| [hyperflask](https://github.com/hyperflask/hyperflask) | Full stack Python web framework | [Python](https://www.python.org/), [Flask](https://flask.palletsprojects.com), [SQLite](https://www.sqlite.org/), [htmx](https://htmx.org/), [tailwindcss](https://tailwindcss.com/), [daisyUI](https://daisyui.com/) | 🚧
| [hyperflask-start](https://github.com/hyperflask/hyperflask-start) | Starter template for new projects | [Docker](https://www.docker.com/), [Development Containers](https://containers.dev/) | 🚧
| [hyperflask-users](https://github.com/hyperflask/hyperflask-users) | Authentication and user management for your apps |  | 🚧

## Independant projects developed as part of the Hyperflask project

Each of these projects is usable standalone outside of Hyperflask!

### Projects

| Name | Description | Status |
| --- | --- | --- |
| [sqlorm](https://github.com/hyperflask/sqlorm) | SQL-focused Python ORM | ✅ |
| [jinjapy](https://github.com/hyperflask/jinjapy) | Hybrid file format combining a jinja template and python code together | ✅ |
| [uilib-spec](https://github.com/hyperflask/uilib-spec) | A specification to generate bindings for UI component libraries | 🚧 |
| [docker-web-deploy](https://github.com/hyperflask/docker-web-deploy) | Docker based deployments target VPS and docker based cloud hosting | ❌
| [Jinja-Super-Macros](https://github.com/hyperflask/jinja-super-macros) | Better macro management for Jinja | ✅ |

### Flask extensions

| Name | Description | Status |
| --- | --- | --- |
| [Flask-Assets-Pipeline](https://github.com/hyperflask/flask-assets-pipeline) | Modern asset pipeline using [esbuild](https://esbuild.github.io/) | ✅ |
| [Flask-Babel-Hyper](https://github.com/hyperflask/flask-babel-hyper) | [Flask-Babel](https://github.com/python-babel/flask-babel) fork with additional utilities | 🚧 |
| [Flask-Collections](https://github.com/hyperflask/flask-collections) | Manage collections of static content | ✅ |
| [Flask-Configurator](https://github.com/hyperflask/flask-configurator) | File based configuration | ✅ |
| [Flask-File-Routes](https://github.com/hyperflask/flask-file-routes) | File-based routing with a new file format combining python and jinja template in a single file | ✅ |
| [Flask-Files](https://github.com/hyperflask/flask-files) | [Fsspec](https://filesystem-spec.readthedocs.io/en/latest/) based files management (upload, storage and image manipulation) | ✅ |
| [Flask-Geo](https://github.com/hyperflask/flask-geo) | Geolocation using [Maxmind](https://www.maxmind.com/en/geoip-databases) | ✅ |
| [Flask-Mailman-Templates](https://github.com/hyperflask/flask-mailman-templates) | Email templates for [Flask-Mailman](https://github.com/waynerv/flask-mailman) | ✅ |
| [Flask-Mercure-SSE](https://github.com/hyperflask/flask-mercure-sse) | Push events via server-sent events using the [Mercure](https://mercure.rocks) protocol | ✅ |
| [Flask-Observability](https://github.com/hyperflask/flask-observability) | Observable Flask apps with [OpenTelemetry](https://opentelemetry.io/), logging and more | ✅ |
| [Flask-Product-Analytics](https://github.com/hyperflask/flask-product-analytics) | Easily track product usage | 🚧 |
| [Flask-Sentry](https://github.com/hyperflask/flask-sentry) | Sentry and Spotlight integration | ✅ |
| [Flask-SQLORM](https://github.com/hyperflask/flask-sqlorm) | Flask integration of [sqlorm](https://github.com/hyperflask/sqlorm) | ✅ |
| [Flask-Stripe-Checkout](https://github.com/hyperflask/flask-stripe-checkout) | Handle payments and subscriptions using Stripe Checkout | ✅ |
| [Flask-Super-Macros](https://github.com/hyperflask/flask-super-macros) | Better macro management for Jinja | ✅ |
| [Flask-Suspense](https://github.com/hyperflask/flask-suspense) | Suspense support for Flask | ✅ |

*Note: as a convention, forks will be named `[original]-hyper`. `hyperflask-something` is reserved for hyperflask specific extensions.*

### Other contributions

| Name | Description | Status |
| --- | --- | --- |
| [Jinja-Frontmatter](https://github.com/hyperflask/jinja-frontmatter) | Frontmatter support for jinja templates | ✅ |
| [Jinja-Layout](https://github.com/hyperflask/jinja-layout) | Easier layout handling for Jinja | ✅ |
| [Jinja-WTForms](https://github.com/hyperflask/jinja-wtforms) | Create [WTForms](https://wtforms.readthedocs.io) classes from Jinja templates | ✅ |
| [Dramatiq-SQLite](https://github.com/hyperflask/dramatiq-sqlite) | SQLite broker for [Dramatiq](https://dramatiq.io/) | 🚧 |
| [uilib-spec-daisyui](https://github.com/hyperflask/uilib-spec-daisyui) | uilib-spec for [daisyUI](https://daisyui.com) | ✅ |
