Kyle Dominic L. Revilla
BS COMPUTER SCIENCE
WEBSITE:https://revillakyle.github.io/

Before you can create your site, you must have a repository for your site on GitHub. If you're not creating your site in an existing repository, see Creating a repository for your site.

Warning

GitHub Pages sites are publicly available on the internet, even if the repository for the site is private (if your plan or organization allows it). If you have sensitive data in your site's repository, you may want to remove the data before publishing. For more information, see About repositories.

    On GitHub, navigate to your site's repository.

    Decide which publishing source you want to use. For more information, see Configuring a publishing source for your GitHub Pages site.

    Create the entry file for your site. GitHub Pages will look for an index.html, index.md, or README.md file as the entry file for your site.

    If your publishing source is a branch and folder, the entry file must be at the top level of the source folder on the source branch. For example, if your publishing source is the /docs folder on the main branch, your entry file must be located in the /docs folder on a branch called main.

    If your publishing source is a GitHub Actions workflow, the artifact that you deploy must include the entry file at the top level of the artifact. Instead of adding the entry file to your repository, you may choose to have your GitHub Actions workflow generate your entry file when the workflow runs.

    Configure your publishing source. For more information, see Configuring a publishing source for your GitHub Pages site.

    Under your repository name, click 

Settings. If you cannot see the "Settings" tab, select the

dropdown menu, then click Settings.

In the "Code and automation" section of the sidebar, click

Pages.

To see your published site, under "GitHub Pages", click

Visit site.
Screenshot of a confirmation message for GitHub Pages listing the site's URL. The gray "Visit site" button is outlined in orange.

Note

It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub. If you don't see your GitHub Pages site changes reflected in your browser after an hour, see About Jekyll build errors for GitHub Pages sites.

Your GitHub Pages site is built and deployed with a GitHub Actions workflow. For more information, see Viewing workflow run history.

    Note

    GitHub Actions is free for public repositories. Usage charges apply for private and internal repositories that go beyond the monthly allotment of free minutes. For more information, see Usage limits, billing, and administration.

Note

    If you are publishing from a branch and your site has not published automatically, make sure someone with admin permissions and a verified email address has pushed to the publishing source.
    Commits pushed by a GitHub Actions workflow that uses the GITHUB_TOKEN do not trigger a GitHub Pages build.


Key takeaways: Fonts are not universal on all operating systems, thus is the need for a bulletproof font-family
