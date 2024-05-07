# gittuf-installer GitHub Action

This GitHub Action installs gittuf in your workflow. It can be used to verify
gittuf policies for your Git repositories.

## Current Status

gittuf-installer is under initial development. Feel free to give it a whirl but
bear in mind that
[gittuf itself is still in alpha](https://github.com/gittuf/gittuf#current-status)!

## Optional Input

`gittuf-version`: Used to specify the version of gittuf to install (default:
`0.4.0`). In addition to the specific version number, `main` is also supported
to build off the [source repository](https://github.com/gittuf/gittuf)'s `main`
branch. Note: do not prefix `v` in the version number.
