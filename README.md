<!--
  Sam Tukra · github.com/SamPlvs
  Profile image renders index.html (served at samplvs.github.io/SamPlvs)
  in dark + light variants.

  We can't use <picture> here because (a) wrapping <picture> in <a> makes
  GitHub's sanitizer hoist the <img> out and replace our link with an
  auto-zoom link to the raw PNG, and (b) putting <a> inside <picture>
  around the <img> breaks <picture>'s source-selection (the <img> must
  be a direct child of <picture> for the spec to work). The fragment
  approach below uses GitHub's CSS to hide the wrong image based on the
  viewer's GitHub theme, while keeping a single clean <a> wrapping both.
-->

<a href="https://samplvs.github.io/SamPlvs/">
  <img src="assets/profile-dark.png#gh-dark-mode-only" alt="Sam Tukra — Researcher · Programmer · Entrepreneur · Chief AI Officer at Applied Computing" width="100%">
  <img src="assets/profile-light.png#gh-light-mode-only" alt="Sam Tukra — Researcher · Programmer · Entrepreneur · Chief AI Officer at Applied Computing" width="100%">
</a>

---

### Connect

- 🌐 [samtukra.com](https://samtukra.com/)
- 🐦 [@SamTukra](https://twitter.com/SamTukra)
- 💼 [LinkedIn](https://www.linkedin.com/in/samyakhtukra/)
- 📚 [Google Scholar](https://scholar.google.com/citations?user=Mkxk50oAAAAJ)

<sub>↑ Click the image for the live interactive version at <a href="https://samplvs.github.io/SamPlvs/"><code>samplvs.github.io/SamPlvs</code></a>.</sub>
