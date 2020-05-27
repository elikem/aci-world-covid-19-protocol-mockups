## [ACI World COVID-19 Protocol Mockup](https://elikem.github.io/aci-world-covid-19-protocol-mockups/)
Style references based on [ACI World Insights](https://blog.aci.aero/).

### Run Mockups Locally
The framework driving this website is [Jekyll](https://jekyllrb.com/) and requires [Ruby](https://www.ruby-lang.org/en/).
Assuming you have Ruby installed, you can clone this repository and install Jekyll.
```
gem install bundler jekyll
```
In the repository folder start web server and browse to ```http://localhost:4000```
```
bundle exec jekyll serve
```
### UI Tools
[Bootstrap 4.5.0](https://getbootstrap.com/docs/4.5/components/alerts/)

[jQuery 3.5.1](https://jquery.com)

[Popper.js 1.16.0](https://popper.js.org)

### UI Configuration
#### Font
The primary font used is [**Muli**](https://fonts.google.com/specimen/Muli). This is an open source font that is available on the Google Fonts.
```css
html {
    font-family: "Muli", sans-serif;
    color: #565656;
}
```