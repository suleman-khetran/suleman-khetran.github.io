`pip install mkdocs-glightbox==0.1.0`

[Interactive web](https://github.com/abhisheknaiidu/awesome-github-profile-readme?tab=readme-ov-file#game-mode-)

[AI Chat - Powered by Encore](https://chatty.encore.dev/?ref=producthunt)

[Changing the colors - Material for MkDocs (squidfunk.github.io)](https://squidfunk.github.io/mkdocs-material/setup/changing-the-colors/)

[mkdocs/catalog: 🏆 A list of awesome MkDocs projects and plugins. (github.com)](https://github.com/mkdocs/catalog)

[MkDocs Plugins (neoteroi.dev)](https://www.neoteroi.dev/mkdocs-plugins/)

https://gsap.com/cheatsheet

[readme-components/docs/experienceComponent.md at master · harish-sethuraman/readme-components (github.com)](https://github.com/harish-sethuraman/readme-components/blob/master/docs/experienceComponent.md)

![qq](https://readme-components.vercel.app/api?component=logo&logo=javascript&fill=linear-gradient%2862deg%2C%20%238EC5FC%200%25%2C%20%23E0C3FC%20100%25%29%3B%0A&text=false)

![experience component](https://readme-components.vercel.app/api?component=experience&company=freshworks&role=software%20developer%20intern&duration=12m&location=chennai&fill=ffc0cd&textfill=000000)

const createComponent = require("../src/createComponent");
const componentNotFound = require("../src/component-not-found");
module.exports = async (req, res) => {
  const {
    component,
    skill,
    value,
    design,
    fill,
    duration,
    role,
    company,
    logo,
    text,
    location,
    stackoverflowid,
    theme,
    textfill,
    animation,
    repoowner,
    reponame,
    svgfill,
    desc,
    scale,
  } = req.query;
  res.setHeader("Content-Type", "image/svg+xml");
  if (component && req.query) {
    let createcomponent = await createComponent(component, {
      skill,
      value,
      design,
      fill,
      duration,
      role,
      company,
      logo,
      text,
      location,
      stackoverflowid,
      theme,
      textfill,
      animation,
      repoowner,
      reponame,
      svgfill,
      desc,
      scale,
    });
    res.send(createcomponent);
  } else {
    res.send(componentNotFound());
  }
};


theme/feature 

- content.code.annotate

```yaml

#(1)

```

1. :man_raising_hand: I'm a code annotation! I can contain `code`, __formatted text__, images, ... basically anything that can be written in Markdown.




---

```powershell

images effets:
pip install mkdocs-glightbox==0.1.0 

```
