# playground

Community demos and projects built on or from ROOST projects. Projects listed in this repo are not developed or endorsed by ROOST, and may not be intended for production use. Check each project’s documentation for details.

## Project eligibility

- Built on, from, or to be used with an existing ROOST open source project

  - If related to online trust & safety but not a ROOST project specifically, please add it to [Awesome Safety Tools](https://github.com/roostorg/awesome-safety-tools)) instead

  - If related to an open-weight LLM or other safety model, please see the [ROOST Model Community](https://github.com/roostorg/model-community)

- Accessible on the web, ideally with source code

## Adding a project

Projects live in [`_data/projects.yml`](_data/projects.yml). Open a pull request or file an issue to add your own project, ensuring you include:

1. Title
2. Description
3. URL
4. Tags (see existing projects for reference)

Someone from @roostorg/roosters will review and merge your pull request if approved!

## Local development

If you want to hack on this project locally, it's a fairly simple static site built with [Jekyll](https://jekyllrb.com/) and served by [GitHub Pages](https://docs.github.com/en/pages).

1. **Prerequisites**: you'll need to install [Ruby](https://www.ruby-lang.org/en/documentation/installation/), [Bundler](https://bundler.io/), and [Jekyll](https://jekyllrb.com/docs/installation/).

2. **Project dependencies** are managed as Ruby gems with Bundler. Run `bundle install` to get everything set up the first time.

3. **Build and serve** the site locally with Jekyll using `bundle exec jekyll serve`, then navigate to [http://localhost:4000](http://localhost:4000).

   To make it accessible on your local network (e.g. to test from a mobile device), append `--host 0.0.0.0`, then navigate to `http://your-local-ip-address:4000` from the other device.

See the [GitHub docs](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll) for more information.
