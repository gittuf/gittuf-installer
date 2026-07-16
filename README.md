# gittuf-installer GitHub Action

This GitHub Action installs gittuf in your workflow. It can be used to verify
gittuf policies for your Git repositories.

## Current Status

gittuf-installer is in beta. Feel free to give it a whirl! See
[here](https://github.com/gittuf/gittuf#current-status) for the current status
of gittuf itself.

## Optional Input

`gittuf-version`: Used to specify the version of gittuf to install (default:
`0.15.0`). In addition to the specific version number, `main` is also supported
to build off the [source repository](https://github.com/gittuf/gittuf)'s `main`
branch. Note: do not prefix `v` in the version number.

## Supported Versions

gittuf-installer currently supports installing gittuf version `0.13.1` and
newer. The last version of gittuf-installer with support for older versions of
gittuf (`0.13.0` and older) is `0.10.0`. This is due to a change in how gittuf's
release artifacts are signed with [Sigstore
Cosign](https://github.com/sigstore/cosign).

Using gittuf-installer `0.11.0` or greater with gittuf versions `0.13.0` or
older will cause the action to fail.