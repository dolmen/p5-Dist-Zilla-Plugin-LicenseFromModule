# NAME

Dist::Zilla::Plugin::LicenseFromModule - Extract License and Copyright from its main\_module file

# SYNOPSIS

    ; dist.ini
    [LicenseFromModule]

# DESCRIPTION

Dist::Zilla::Plugin::LicenseFromModule is a Dist::Zilla plugin to
extract license, author and copyright year from your main module's POD
document.

Dist::Zilla by default already extracts license from POD when it's not
specified, but it will bail out if you don't specify the right
copyright holder. This plugin will scan license __and__ copyright
holder from the POD document, like [Module::Install](https://metacpan.org/pod/Module::Install)'s
`license_from` and `author_from`.

# AUTHOR

Tatsuhiko Miyagawa <miyagawa@bulknews.net>

# COPYRIGHT

Copyright 2013- Tatsuhiko Miyagawa

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO

[Dist::Zilla](https://metacpan.org/pod/Dist::Zilla) [Dist::Zilla::Plugin::VersionFromModule](https://metacpan.org/pod/Dist::Zilla::Plugin::VersionFromModule)
