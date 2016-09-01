# librmb
Librados Mailbox (librmb) is a library build on top of [Ceph](http://ceph.com)'s [librados](http://docs.ceph.com/docs/master/rados/api/librados/) to abstract mailboxes.

This library is still in the planning, design and development phase.

# Goals
The end-goal is to allow for massive e-mail storage on Ceph without the need for CephFS or the RADOS Gateway.

Using native RADOS access and objects e-mail should be stored inside the Ceph system.

Data safety and consistency are guarenteed by using the RADOS semantics and atomic operations.

# Dovecot
For easy adoption librmb will be integrated into [Dovecot](http://dovecot.fi/), one of the most popular IMAP/POP3 servers.

It will allow for building massively scalable e-mail platforms using software admins are familair with.

# Roadmap
A roadmap is not available yet. As soon as more information is available it will be placed here.

Most of the things which need to happen are described in issue [#12430](http://tracker.ceph.com/issues/12430) on the Ceph tracker.
