
# Table of Contents

1.  [what is a shell?](#org3526759)


<a id="org3526759"></a>

# what is a shell?

-   shell = command-line interface to OS
    -   manages environment variables
    -   creates argument lists
    -   opens file descriptors and pipelines
    -   controls processes
-   shell does more than you might think: e.g., substitutions, expansions
-   shell does less than you might think: e.g., doesn't include: ls, ps, find, etc
-   shell variants: bash is the standard, do not use (t)csh <http://www.faqs.org/faqs/unix-faq/shell/csh-whynot/>

-   Why is bash the default shell in most OS?
    -   it is the default shell of GNU (used by most Linux based OS) <https://askubuntu.com/questions/638918/>
    -   also having 20 years of development behind it making it stable and well rounded,
    -   recall the last commands by simply moving the cursor up/down. BASH was IMO the first shell that implemented this on \*nix. <https://unix.stackexchange.com/questions/28749>
    -   What are the fundamental differences between the mainstream \*NIX shells? <https://unix.stackexchange.com/questions/3320>
    -   Which shell is better? <https://www.quora.com/Which-shell-is-better-Bash-Fish-Ksh-Tcsh-Zsh-and-why-choose-one-over-the-other>
-   In Ubuntu 6.10, the default system shell, /bin/sh, was changed to dash (the Debian Almquist Shell) <https://wiki.ubuntu.com/DashAsBinSh>
-   Apple replaces bash with zsh as the default shell in macOS Catalina <https://www.theverge.com/2019/6/4/18651872/apple-macos-catalina-zsh-bash-shell-replacement-features>

-   check shell version <https://stackoverflow.com/questions/38237907/how-to-find-my-shell-version-using-linux-command>
    $ $SHELL &#x2013;version

