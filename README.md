Add the following line to your rebar.config:
    {deps, [
            {reloader, ".*", {git, "git://github.com/brendanhay/reloader.git", {branch, "master"}}}
           ]}.