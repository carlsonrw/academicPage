## Publication files on this site

Each paper's page lives in `content/publication/<name>/index.md`. To host its PDF here, save it as `static/papers/<name>.pdf` and add `url_pdf: "papers/<name>.pdf"` to the page's front matter; it's then served at `carlsonr.com/papers/<name>.pdf`. Use the same name for the folder and the PDF:

**`firstAuthor[EtAl]Year_topicInCamelCase`**

- First author's last name, lowercase: `carlson`, `davis`, `weisz`.
- `EtAl` when the paper has co-authors; leave it off for solo papers.
- The year the CV cites (the issue year, not the online-first date).
- An underscore, then a few title words in camelCase. Abbreviations go in capitals at the end.

Examples: `carlsonEtAl2022_psychologicalSelfishness`, `carlson2026_dialogueSkillsAI`, `carlsonEtAl2016_intuitiveGivingERP`.

Hugo lowercases page addresses; PDF addresses keep their capitals. Don't put a PDF inside its page folder: the address would repeat the name in two cases. If you rename a page folder or PDF that's already live, add redirects from the old addresses in `netlify.toml`, following the existing rules there.

---

<p align="center"><a href="https://wowchemy.com/templates/" target="_blank" rel="noopener"><img src="https://wowchemy.com/uploads/readmes/academic_logo_200px.png" alt="Hugo Academic Template for Wowchemy Website Builder"></a></p>

# Academic Template for [Hugo](https://github.com/gohugoio/hugo)

The Hugo **Academic Resumé Template** empowers you to create your job-winning online resumé and showcase your academic publications.

[Check out the latest demo](https://academic-demo.netlify.app/) of what you'll get in less than 10 minutes, or [view the showcase](https://wowchemy.com/user-stories/).

[**Wowchemy**](https://wowchemy.com) makes it easy to create a beautiful website for free. Edit your site in Markdown, Jupyter, or RStudio (via Blogdown), generate it with Hugo, and deploy with GitHub or Netlify. Customize anything on your site with widgets, themes, and language packs.

- 👉 [**Get Started**](https://wowchemy.com/templates/)
- 📚 [View the **documentation**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- 🐦 Twitter: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=(%23MadeWithWowchemy%20OR%20%23MadeWithAcademic)&src=typed_query)
- 💡 [Request a **feature** or report a **bug** for _Wowchemy_](https://github.com/wowchemy/wowchemy-hugo-modules/issues)
- ⬆️ **Updating Wowchemy?** View the [Update Guide](https://wowchemy.com/docs/guide/update/) and [Release Notes](https://wowchemy.com/updates/)

## Crowd-funded open-source software

To help us develop this template and software sustainably under the MIT license, we ask all individuals and businesses that use it to help support its ongoing maintenance and development via sponsorship.

### [❤️ Click here to unlock rewards with sponsorship](https://wowchemy.com/plans/)

## Ecosystem

* **[Hugo Academic CLI](https://github.com/wowchemy/hugo-academic-cli):** Automatically import publications from BibTeX

[![Screenshot](https://raw.githubusercontent.com/wowchemy/wowchemy-hugo-modules/main/academic.png)](https://wowchemy.com)

## Demo image credits

- [Open book](https://unsplash.com/photos/J4kK8b9Fgj8)
- [Course](https://unsplash.com/photos/JKUTrJ4vK00)

## Latest news
<!--START_SECTION:news-->
* [Hugo vs Quarto: Which One is Better for 2023?](https:&#x2F;&#x2F;hugoblox.com&#x2F;blog&#x2F;hugo-vs-quarto&#x2F;)
* [Easily make an academic CV website to get more cites and grow your audience 🚀](https:&#x2F;&#x2F;hugoblox.com&#x2F;blog&#x2F;easily-make-academic-website&#x2F;)
* [What&#39;s new in v5.2?](https:&#x2F;&#x2F;hugoblox.com&#x2F;blog&#x2F;whats-new-in-v5.2&#x2F;)
* [What&#39;s new in v5.1?](https:&#x2F;&#x2F;hugoblox.com&#x2F;blog&#x2F;whats-new-in-v5.1&#x2F;)
* [Version 5.0 (February 2021)](https:&#x2F;&#x2F;hugoblox.com&#x2F;blog&#x2F;version-5.0-february-2021&#x2F;)
<!--END_SECTION:news-->

[![Analytics](https://ga-beacon.appspot.com/UA-78646709-2/starter-academic/readme?pixel)](https://github.com/igrigorik/ga-beacon)
