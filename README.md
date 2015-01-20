# NAME

Plack::Middleware::ConsoleLogger - Write logs to Firebug or Webkit Inspector

# SYNOPSIS

    enable "ConsoleLogger";

# DESCRIPTION

This middleware captures logs from PSGI applications and plack
middleware components and makes them available to see on JavaScript
console for Firebug and Webkit Inspector.

# CONFIGURATIONS

- group

    Set the group to use with console log. Defaults to undef.

# AUTHOR

Tatsuhiko Miyagawa

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO

Rack::FirebugLogger
