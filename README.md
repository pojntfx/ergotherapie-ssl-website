# Ergotherapie Smeets-Labee Website

Static website for Ergotherapie Smeets-Labee. Supports offline usage and more PWA functionality using a service worker to achieve it's **100** lighthouse score. Uses [Netlify CMS](https://www.netlifycms.org/) for production and [Jekyll Admin](https://jekyll.github.io/jekyll-admin/) for local/"decentralized" editing.

![Home page screenshot](/img/home_page_screenshot.png)

![100 Lighthouse audit score screenshot](/img/lighthouse_score.png)

## Demo

Visit [ergotherapie-ssl.de](https://ergotherapie-ssl.de/) and take a look at the official instance.

## Usage

```bash
# Install Ruby and other dependencies (Debian/Ubuntu):
sudo apt install ruby ruby-dev cmake

# Install Ruby and other dependencies (Fedora/CentOS/RHEL):
sudo dnf group install "C Development Tools and Libraries"
sudo dnf install ruby ruby-devel redhat-rpm-config

# Install Jekyll and Bundler gems through RubyGems:
gem install jekyll bundler

# Install dependencies:
bundle install

# Build and serve development version on http://localhost:4000/
bundle exec jekyll serve
# Build and serve development version on http://your-ip:4000/
bundle exec jekyll serve --host your-ip

# When running this site locally, an admin interface (jekyll-admin) is available at http://localhost:4000/admin
# If you have deployed this site on Netlify, /admin will redirect you to Netlify CMS
```

## Screenshots

> TODO: Add screenshots

## Documentation

> TODO: Add docs

## Deployment

We use [GitLab CI/CD](https://about.gitlab.com/features/gitlab-ci-cd/), [GitLab Pages](https://about.gitlab.com/features/pages/) and [Netlify](https://www.netlify.com/) to automate deployment.

## License

### Source Code

Ergotherapie Smeets-Labee Website
Copyright (C) 2018 Felicitas Pojtinger

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.

### Media

Media of Ergotherapie Smeets-Labee Website (C) 2018 Felicitas Pojtinger

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
