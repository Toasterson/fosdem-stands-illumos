---
description: The illumos project develops a Unix operating system core that was
    originally derived from OpenSolaris, providing next-generation features for
    downstream distributions, including advanced system debugging, next
    generation filesystem, networking, and virtualization options.<p>
    illumos is developed by both volunteers and companies building products
    based on the illumos system.<p>
    illumos is an excellent base for both traditional and cloud-native
    deployments.<p>
layout: stand
logo: stands/illumos/logo.png
new_this_year: |
  <p>Since last FOSDEM we had a couple of larger updates:</p>
  <ol>
    <li>bhyve finally went upstream, so all illumos distributions now get to
    benefit from it.<p>
    bhyve is a hypervisor running on Intel and AMD CPUs, providing fast
    networking and disk access to guest machines. On Intel systems it also
    supports PCI passthrough.
    </li>
    <li>NFS server support in zones</li>
    <li>new CCID driver to natively support USB chip card readers and similar
    devices like YubiKeys</li>
    <li>ZFS encryption and several other improvements from OpenZFS</li>
    <li>new and improved ksh93 for scripting and interactive use</li>
    <li>improved AMD RyZen CPU support</li>
  </ol>
showcase: |
  <p>Showcase 1</p>
  <p>Showcase 2</p>
  <p>Showcase 3</p>
themes:
- Operating systems
title: illumos
website: https://www.illumos.org/
show_on_overview: true
chatroom: illumos
---
