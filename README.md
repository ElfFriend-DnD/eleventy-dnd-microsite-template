# A Dungeons and Dragons Microsite template repository

Implements 11ty via eleventy-base-blog. Reskins with a lightly trimmed homebrewery phb stylesheet.

The idea is to make an easy to spin up D&D Styled microsite + blog (session log) for a D&D group. The DM posts markdown files about their campaign primer, homebrew rules, and session logs into the right places and boom, a permanent site is deployed, easy to reference.

## Getting Started

1. Create a New Repository using this one as a template. See Github's help page for more [Creating a repository from a template](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template). Name it what you want your microsite's url to look like (e.g. `camp-awesome` will be `username.github.io/camp-awesome`)

2. Change the following:
   - [ ] `.eleventy.js:95` - `pathPrefix` needs to be the name of your repo
   - [ ] `package.json:2` - `name` should be the name of your repo
   - [ ] `_data/metadata.json`
     - `title` - Should be what you want the site's name to be.
     - `description` - Subtext that goes under the site's name.
     - `author` - Your name.
     - Update the `url`s

3. Change the Pages as you desire.

    Use the `/primer` as your guide here. Basically you need a directory for each page, and the header of the `index.md` within that directory informs the nav how to handle it.

4. Populate!

   Add Markdown files as you please to the `posts` directory. These get turned into Sessions (blog style).

   Other pages will be added as you create directories for them. I personally use two pages: a Campaign Primer and a Homebrew Rules & Rulings digest.

5. Push
   Deploy should be automatic.

### eleventy-base-blog

This is all based on eleventy's [Eleventy Base Blog Repo](https://github.com/11ty/eleventy-base-blog), so there's a lot more useful information about customization there.
