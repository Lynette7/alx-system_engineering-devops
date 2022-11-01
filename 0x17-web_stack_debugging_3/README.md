Wordpress is a very popular tool, it allows you to run blogs, portfolios, e-commerce and company websites… It actually powers 26% of the web, so there is a fair chance that you will end up working with it at some point in your career.

Wordpress is usually run on LAMP (Linux, Apache, MySQL, and PHP), which is a very widely used set of tools.

The web stack being debugged in this project is a Wordpress website running on a LAMP stack.

- 0-strace_is_your_friend.pp: Puppet manifest that fixes a typo error causing a WordPress application being served by an Apache web server to fail after using strace to find out why Apache is returning a 500 error.