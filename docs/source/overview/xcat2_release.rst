The following table is a summary of the New Operating System, New Hardware and New features that are supported in certain xCAT release.

The New OS and New Hardware which listed in the table have been fully tested. The OS which comes with the same source code or Hardware comes with the same CPU should also work, but you need to try it by yourself.

For a complete list of new functions, bug fixes, restrictions, and known problems, refer to the individual release notes.

xCAT 2.10 Releases
==================

+------------------------------+---------------+-------------+----------------------------------+
|xCAT                          |New OS         |New          |New Feature                       |
|Version                       |               |Hardware     |                                  |
+==============================+===============+=============+==================================+
|| xCAT 2.10                   |- RHEL 7.1 LE  |- Power 8 LE |- Ubuntu LE -> RH 7.1 Mix         |
|| 2015/07/31                  |- UBT 15.4 LE  |             |- Cuda install for Ubuntu 14.4.2  |
||                             |- SLES 12 LE   |             |- additional kernel parameters    |
| `Rlease Notes <https://      |- RHEL 6.7     |             |- customized disk part (Ubuntu)   |
| sourceforge.net/p/xcat/wiki/ |- CentOS 7.1   |             |- Raid configure base iprconfig   |
| XCAT_2.10_Release_Notes/>`_  |- SLES 11 SP4  |             |- New command: switchdiscover     |
|                              |               |             |- New command: makentp            |
|                              |               |             |- New command: bmcdiscovery       |
|                              |               |             |- Support getmacs --noping        |
|                              |               |             |- site.xcatdebugmode              |
|                              |               |             |- validate netboot attribute      |
|                              |               |             |- buildcore on local server       |
|                              |               |             |- copycds genereates less osimage |
|                              |               |             |- nodeset only accecpt osimage=   |
+------------------------------+---------------+-------------+----------------------------------+

xCAT 2.9 Releases
=================

+------------------------------+---------------+-------------+----------------------------------+
|xCAT                          |New OS         |New          |New Feature                       |
|Version                       |               |Hardware     |                                  |
+==============================+===============+=============+==================================+
|| xCAT 2.9.1                  |- RHEL 7.1     |             |- Nvidia GPU                      |
|| 2015/03/20                  |- UBT 14.4.2   |             |- Ubuntu Local Mirror             |
||                             |               |             |- Sles12 diskless                 |
| `Rlease Notes <https://      |               |             |- Energy management for Power 8   |
| sourceforge.net/p/xcat/wiki/ |               |             |- RHEL 7.1 LE -> BE mix cluster   |
| XCAT_2.9.1_Release_Notes/>`_ |               |             |- nics.nicextraparams             |
|                              |               |             |- xCAT in Docker Image            |
|                              |               |             |- Confluent replaces conserver    |
|                              |               |             |- TLSv1 in xcatd                  |
|                              |               |             |- New GPG key for xCAT packages   |
|                              |               |             |- fast restart xcatd (systemd)    |
|                              |               |             |- netboot method: grub2-tftp      |
|                              |               |             |- netboot method: grub2-http      |
+------------------------------+---------------+-------------+----------------------------------+
|| xCAT 2.9                    |- UBT 14.4 LE  |- Power 8 LE |- sysclone enhancements           |
|| 2014/12/12                  |- UBT 14.4.1 LE|             |- site.auditnosyslog              |
||                             |- UBT 14.10    |             |- site.nmapoptions                |
| `Rlease Notes <https://      |- SLES 12      |             |- customize postscripts           |
| sourceforge.net/p/xcat/wiki/ |- RHEL 6.6     |             |- Power 8 LE hw discovery         |
| XCAT_2.9_Release_Notes/>`_   |- AIX 7.1.3.15 |             |- IB support for P8 LE            |
|                              |- PowerKVM     |             |                                  |
|                              |               |             |                                  |
+------------------------------+---------------+-------------+----------------------------------+

xCAT 2.8 Releases
=================

+------------------------------+---------------+-------------+----------------------------------+
|xCAT                          |New OS         |New          |New Feature                       |
|Version                       |               |Hardware     |                                  |
+==============================+===============+=============+==================================+
|| xCAT 2.8.4                  |- RHEL 6.5     |             |- RHEL 7 experimental,            |
|| 2014/03/23                  |- RHEL 5.10    |             |- support xCAT clusterzones       |
||                             |               |             |- commands enhancements           |
| `Rlease Notes <https://      |               |             |                                  |
| sourceforge.net/p/xcat/wiki/ |               |             |                                  |
| XCAT_2.8.4_Release_Notes/>`_ |               |             |                                  |
+------------------------------+---------------+-------------+----------------------------------+
|| xCAT 2.8.3                  |- AIX 7.3.1.1  |- Xeon Phi   |- xcatd flow control              |
|| 2013/11/15                  |- AIX 7.3.1.0  |  (P2)       |- sysclone x86_64 image           |
||                             |- AIX 7.1.2    |- NS nx360M4 |- enhance genitird and nodeset    |
| `Rlease Notes <https://      |               |             |- enhance confignics, KIT         |
| sourceforge.net/p/xcat/wiki/ |               |             |- enhance sequential discovery    |
| XCAT_2.8.3_Release_Notes/>`_ |               |             |- deploy OpenStack on Ubuntu      |
+------------------------------+---------------+-------------+----------------------------------+
|| xCAT 2.8.2                  |- SLES 11 SP3  |- Xeon Phi   |- HPC KIT for ppc64               |
|| 2013/06/26                  |               |  (P1)       |- sysclone x86_64 image (P1)      |
||                             |               |             |- enhance xdsh, updatenode        |
| `Rlease Notes <https://      |               |             |- localdisk for diskless          |
| sourceforge.net/p/xcat/wiki/ |               |             |- enhance sequential discovery    |
| XCAT_2.8.2_Release_Notes/>`_ |               |             |- deploy OpenStack on Ubuntu      |
+------------------------------+---------------+-------------+----------------------------------+
|| xCAT 2.8.1                  |- RHEL 6.4     |             |- energy management for flex      |
|| 2013/06/26                  |- RHEL 5.9     |             |- sequential discovery            |
||                             |               |             |- KIT enhancements                |
| `Rlease Notes <https://      |               |             |- osimage enhancements            |
| sourceforge.net/p/xcat/wiki/ |               |             |- IPv6 enhancements               |
| XCAT_2.8.1_Release_Notes/>`_ |               |             |- *def/xdsh/xdcp enhancements     |
|                              |               |             |- updatenode enhancements         |
+------------------------------+---------------+-------------+----------------------------------+
|| xCAT 2.8                    |- UBT 12.04    |             |- Flex IMM setup                  |
|| 2013/02/28                  |- WIN S 2012   |             |- Multiple Hostname               |
||                             |- WIN 8 Hv     |             |- KIT support                     |
| `Rlease Notes <https://      |               |             |- KVM/zVM enhancements            |
| sourceforge.net/p/xcat/wiki/ |               |             |- RHEV Support                    |
| XCAT_2.8_Release_Notes/>`_   |               |             |- Localdisk for statelite         |
|                              |               |             |- Manage MN itslef                |
|                              |               |             |- site auditskipcmds              |
|                              |               |             |- precreate postscripts           |
|                              |               |             |- mypostscript templates          |
|                              |               |             |- pasu command                    |
|                              |               |             |- postscripts on stateful boot    |
|                              |               |             |- node update status attrs        |
|                              |               |             |- updatenode enhancements         |
+------------------------------+---------------+-------------+----------------------------------+

xCAT 2.7 Releases
=================

+------------------------------+---------------+-------------+----------------------------------+
|xCAT                          |New OS         |New          |New Feature                       |
|Version                       |               |Hardware     |                                  |
+==============================+===============+=============+==================================+
|| xCAT 2.7.8                  |- AIX 7.1.3.1  |             |                                  |
|| 2014/01/24                  |- AIX 7.1.3.0  |             |                                  |
||                             |- AIX 6.1.9.1  |             |                                  |
| `Rlease Notes <https://      |               |             |                                  |
| sourceforge.net/p/xcat/wiki/ |               |             |                                  |
| XCAT_2.7.8_Release_Notes/>`_ |               |             |                                  |
+------------------------------+---------------+-------------+----------------------------------+
|| xCAT 2.7.7                  |- RHEL 6.4     |             |- sinv for devices                |
|| 2013/03/17                  |               |             |- Flex energy mgt and rbeacon     |
||                             |               |             |                                  |
| `Rlease Notes <https://      |               |             |                                  |
| sourceforge.net/p/xcat/wiki/ |               |             |                                  |
| XCAT_2.7.7_Release_Notes/>`_ |               |             |                                  |
+------------------------------+---------------+-------------+----------------------------------+
|| xCAT 2.7.6                  |- SLES 10 SP4  |             |- HPC Integration updates         |
|| 2012/11/30                  |- AIX 6.1.8    |             |                                  |
||                             |- AIX 7.1.2    |             |                                  |
| `Rlease Notes <https://      |               |             |                                  |
| sourceforge.net/p/xcat/wiki/ |               |             |                                  |
| XCAT_2.7.6_Release_Notes/>`_ |               |             |                                  |
+------------------------------+---------------+-------------+----------------------------------+
|| xCAT 2.7.5                  |- RHEL 6.3     |             |- virtualization with RHEV        |
|| 2012/10/29                  |               |             |- hardware discovery for x Flex   |
||                             |               |             |- enhanced AIX HASN               |
| `Rlease Notes <https://      |               |             |                                  |
| sourceforge.net/p/xcat/wiki/ |               |             |                                  |
| XCAT_2.7.5_Release_Notes/>`_ |               |             |                                  |
+------------------------------+---------------+-------------+----------------------------------+
|| xCAT 2.7.4                  |- SLES11 SP2   |- Flex       |- improved IPMI for large systems |
|| 2012/08/27                  |               |             |                                  |
||                             |               |             |                                  |
| `Rlease Notes <https://      |               |             |                                  |
| sourceforge.net/p/xcat/wiki/ |               |             |                                  |
| XCAT_2.7.4_Release_Notes/>`_ |               |             |                                  |
+------------------------------+---------------+-------------+----------------------------------+
|| xCAT 2.7.3                  |- SLES11 SP2   |- Flex       |- HPC Integration updates         |
|| 2012/06/22                  |- RHEL 6.2     |             |                                  |
||                             |               |             |                                  |
| `Rlease Notes <https://      |               |             |                                  |
| sourceforge.net/p/xcat/wiki/ |               |             |                                  |
| XCAT_2.7.3_Release_Notes/>`_ |               |             |                                  |
+------------------------------+---------------+-------------+----------------------------------+
|| xCAT 2.7.2                  |- AIX 7.1.1.3  |- Power 775  |- SLES 11 kdump                   |
|| 2012/05/25                  |               |- Flex for P |- HPC Integration updates         |
||                             |               |             |                                  |
| `Rlease Notes <https://      |               |             |                                  |
| sourceforge.net/p/xcat/wiki/ |               |             |                                  |
| XCAT_2.7.2_Release_Notes/>`_ |               |             |                                  |
+------------------------------+---------------+-------------+----------------------------------+
|| xCAT 2.7.1                  |- RHEL 6.3     |             |- minor enhancements              |
|| 2012/04/20                  |               |             |- bug fixes                       |
||                             |               |             |                                  |
| `Rlease Notes <https://      |               |             |                                  |
| sourceforge.net/p/xcat/wiki/ |               |             |                                  |
| XCAT_2.7.1_Release_Notes/>`_ |               |             |                                  |
+------------------------------+---------------+-------------+----------------------------------+
|| xCAT 2.7                    |- RHEL 6.2     |             |- xcatd memory usage reduced      |
|| 2012/03/19                  |               |             |- xcatdebug for xcatd and plugins |
||                             |               |             |- lstree command                  |
| `Rlease Notes <https://      |               |             |- x86_64 genesis boot image       |
| sourceforge.net/p/xcat/wiki/ |               |             |- ipmi throttles                  |
| XCAT_2.7_Release_Notes/>`_   |               |             |- rpower suspend select IBM hw    |
|                              |               |             |- stateful ESXi5                  |
|                              |               |             |- xnba UEFI boot                  |
|                              |               |             |- httpd for postscripts           |
|                              |               |             |- rolling updates                 |
|                              |               |             |- Nagios monitoring plugin        |
+------------------------------+---------------+-------------+----------------------------------+
