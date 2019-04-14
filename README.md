### THIS IS INSTUCTION OF SAVING ATOM CONFIG AND LOADING

Use [Git] to version control your config file (`~/.atom/config.cson`), and any other config files (dotfiles) you may have.

You can then host your Git repository for free on somewhere like [GitHub], and retrieve it on other computers simply by running `git clone https://github.com/{username}/{repo}`.

You can then keep it up to date using `git push` (to upload changes) and `git pull` (to download changes).

To track installed packages as well, you will need to run:

    apm list --installed --bare > ~/.atom/package.list

and add that file to Git also.  



To restore, use:

    apm install --packages-file ~/.atom/package.list


  [Git]: https://git-scm.com/
  [GitHub]: https://github.com
