# upload-to-netlify-example

[![Netlify Status](https://api.netlify.com/api/v1/badges/469c9d79-44a7-4e1b-9da3-1640d9c3548e/deploy-status)](https://app.netlify.com/sites/upload-to-netlify-example/deploys)

This repository demonstrates the usage of the
[upload-to-netlify-action](https://github.com/MrFlynn/upload-to-netlify-action)
for Github Actions. Every time a commit is made to master, the LaTeX document in
[`assets/asset.tex`](assets/asset.tex) is compiled and uploaded to the Netlify site at the relative
URL of `/asset.pdf`.
See the live site [here](https://upload-to-netlify-example.netlify.com).
