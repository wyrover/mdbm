.. $Id$
   $URL$

.. _mdbm_digest:

mdbm_digest
===========

SYNOPSIS
--------

mdbm_digest [-hmsv] [-w *size*] *mdbm*

DESCRIPTION
-----------

``mdbm_digest`` displays a digest (hash) code for an MDBM.

OPTIONS
-------

-h            Show help message
-m            Generate md5
-s            Generate sha-1
-v            Show verbose stats
-w size
    Open database in windowed mode with specified window size\n\
    Suffix k/m/g may be used to override default of b.

RETURN VALUE
------------

Returns 0 upon success, non-zero upon failure.

EXAMPLES
--------

::

  mdbm_digest -m /tmp/bar.mdbm
  mdbm_digest -s /tmp/bar.mdbm
  mdbm_digest -msv -w 1m /tmp/bar.mdbm

SEE ALSO
--------

mdbm_check(1), mdbm_compare(1), mdbm_copy(1), mdbm_create(1),
mdbm_digest(1), mdbm_dump(1), mdbm_export(1), mdbm_fetch(1), mdbm_import(1),
mdbm_purge(1), mdbm_replace(1), mdbm_restore(1), mdbm_save(1), mdbm_stat(1),
mdbm_sync(1), mdbm_trunc(1)

CONTACT
-------

mdbm-users <mdbm-users@yahoo-inc.com>


.. End of documentation

   emacsen buffer-local ispell variables -- Do not delete.

   === content ===
   LocalWords: emacsen hlL hmsv md mdbm msv sha trunc

   Local Variables:
   mode: text
   fill-column: 80
   indent-tabs-mode: nil
   tab-width: 4
   End:
