.. highlight:: sh

OpenSUSE
========

.. contents:: Table of Contents
  :local:

Installation
------------

If you want to use ZFS as your root filesystem, see the `Root on ZFS`_
links below instead.

ZFS packages are not included in official OpenSUSE repositories, but repository of
`filesystems projects of OpenSUSE<https://software.opensuse.org/download.html?project=filesystems&package=zfs>`__ 
includes such packages of filesystems including OpenZFS.

OpenSUSE progresses through 3 main distribution branches, these are called Tumbleweed, Leap and SLE. There are ZFS packages available for all three.


Command Line Installation
-------------------------

#. For openSUSE Tumbleweed::

    zypper addrepo https://download.opensuse.org/repositories/filesystems/openSUSE_Tumbleweed/filesystems.repo
    zypper refresh
    zypper install zfs zfs-kms-default

#. For openSUSE Leap 42.3::

    zypper addrepo https://download.opensuse.org/repositories/filesystems/openSUSE_Leap_42.3/filesystems.repo
    zypper refresh
    zypper install zfs zfs-kms-default

#. For openSUSE Leap 15.2::

    zypper addrepo https://download.opensuse.org/repositories/filesystems/openSUSE_Leap_15.2/filesystems.repo
    zypper refresh
    zypper install zfs zfs-kms-default

#. For openSUSE Leap 15.1::

    zypper addrepo https://download.opensuse.org/repositories/filesystems/openSUSE_Leap_15.1/filesystems.repo
    zypper refresh
    zypper install zfs zfs-kms-default

#. For openSUSE Leap 15.0::

    zypper addrepo https://download.opensuse.org/repositories/filesystems/openSUSE_Leap_15.0/filesystems.repo
    zypper refresh
    zypper install zfs zfs-kms-default

#. For SLE 15 SP2::

    zypper addrepo https://download.opensuse.org/repositories/filesystems/SLE_15_SP2/filesystems.repo
    zypper refresh
    zypper install zfs zfs-kms-default

#. For SLE 15 SP1::

    zypper addrepo https://download.opensuse.org/repositories/filesystems/SLE_15_SP1/filesystems.repo
    zypper refresh
    zypper install zfs zfs-kms-default

#. For  SLE 15::

    zypper addrepo https://download.opensuse.org/repositories/filesystems/SLE_15/filesystems.repo
    zypper refresh
    zypper install zfs zfs-kms-default

#. For SLE 12 SP5::

    zypper addrepo https://download.opensuse.org/repositories/filesystems/SLE_12_SP5/filesystems.repo
    zypper refresh
    zypper install zfs zfs-kms-default

#. For SLE 12 SP4::

    zypper addrepo https://download.opensuse.org/repositories/filesystems/SLE_12_SP4/filesystems.repo
    zypper refresh
    zypper install zfs zfs-kms-default

#. For SLE 12 SP3::

    zypper addrepo https://download.opensuse.org/repositories/filesystems/SLE_12_SP3/filesystems.repo
    zypper refresh
    zypper install zfs zfs-kms-default

External Links
--------------

* `OpenSUSE OpenZFS page <https://en.opensuse.org/OpenZFS>`__

Root on ZFS
-----------
.. toctree::
  :maxdepth: 1
  :glob:

  *Root on ZFS


