.. _mmctl_user_deleteall:

mmctl user deleteall
--------------------

Delete all users and all posts. Local command only.

Synopsis
~~~~~~~~


Permanently delete all users and all related information including posts. This command can only be run in local mode.

::

  mmctl user deleteall [flags]

Examples
~~~~~~~~

::

    user deleteall

Options
~~~~~~~

::

      --confirm   Confirm you really want to delete the user and a DB backup has been performed
  -h, --help      help for deleteall

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --config-path string           path to the configuration directory. If "$HOME/.mmctl" exists it will take precedence over the default value (default "$XDG_CONFIG_HOME")
      --format string                the format of the command output [plain, json] (default "plain")
      --insecure-sha1-intermediate   allows to use insecure TLS protocols, such as SHA-1
      --insecure-tls-version         allows to use TLS versions 1.0 and 1.1
      --local                        allows communicating with the server through a unix socket
      --strict                       will only run commands if the mmctl version matches the server one

SEE ALSO
~~~~~~~~

* `mmctl user <mmctl_user.rst>`_ 	 - Management of users

