# Personal website

A minimal, responsive portfolio inspired by the supplied screenshot: warm paper background, serif name, quiet green accents, and thin dividers. No dependencies or build step.

## Customize

Open index.html in any browser. Search for EDIT to find the places to change.

| Item | What to edit |
| --- | --- |
| Name | The title tag, description, and h1 |
| Introduction | The paragraph with class="intro" |
| GitHub | The existing GitHub href |
| LinkedIn | Replace its placeholder span with the commented link; insert your URL |
| Resume | Upload your PDF as files/resume.pdf, then use the commented resume link |
| Email | Use the commented mailto link with your address |
| Projects | Uncomment the optional projects section and duplicate its li block |
| Colors | Change the variables at the start of the style tag |

LinkedIn, resume, and email are intentionally plain text until you add your real destinations, so there are no fake working links.

## Link templates

```html
<a href="https://www.linkedin.com/in/YOUR-USERNAME/">LinkedIn <span class="arrow" aria-hidden="true">→</span></a>
<a href="files/resume.pdf">Resume <span class="arrow" aria-hidden="true">→</span></a>
<a href="files/YOUR-FILE.pdf">Download file <span class="arrow" aria-hidden="true">→</span></a>
<a class="email" href="mailto:you@example.com">you (at) example (dot) com</a>
```

## GitHub Pages

When ready to publish, open this repository's Settings → Pages. Under Build and deployment, choose Deploy from a branch, select main and / (root), and save. This has not been enabled automatically.
