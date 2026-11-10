# Higanbana Portfolio

Static portfolio site (plain HTML, CSS, JS). No build step.

## Edit your content
Open `index.html` and replace:
- `Your Name` (hero title and footer), `Y.N` (top-left mark)
- the role line under the title
- the 4 project cards in `#work` (title, text, tags, and `href="#"` links)
- the About text and facts, the Skills lists
- `hello@yourname.dev` and the social links in `#contact`

Colors and fonts are the variables at the top of the `<style>` block (`--blood`, `--sky-low`, `--f-display`, and so on).

## Deploy to Vercel
Option A, GitHub:
1. Create a new GitHub repository and upload these files.
2. Go to vercel.com/new, import the repository.
3. Framework Preset: Other. Leave build command and output directory empty. Click Deploy.

Option B, CLI:
1. `npm i -g vercel`
2. In this folder run `vercel`, then `vercel --prod`.
