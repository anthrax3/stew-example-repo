This is an example repository for example app [stew-example-app](https://github.com/vti/stew-example-app).

See also [stew](https://github.com/vti/stew) to learn what's it all about.

# How did I generate CPAN modules?

    perl /path/to/cpan2stew --local --repo /path/to/repo --stewfile stewfile Plack

Where

    --local downloads CPAN module sources
    --repo puts generated stewfiles into repository
    --stewfile appends generated stew names
