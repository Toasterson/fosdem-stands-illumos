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
    <li>The NFS server can now run in a zone, allowing for multi-tenancy NFS
    server setups.<p>
    Zones are a lightweight virtualization mechanism allowing running another,
    completely isolated instance of the native OS on the same kernel. They were
    introduced back in 2005, designed from the ground up to be secure.</li>
    <li>ZFS now supports encryption, and there were several other improvements
    coming from OpenZFS.</li>
    <li>We got a new CCID driver to natively support USB chip card readers and
    similar devices like YubiKeys.</li>
    <li>We got an all-new and improved ksh93 for scripting and interactive use.</li>
    <li>We improved our AMD CPU support for running on RyZen and Threadripper
    CPUs.</li>
  </ol>
showcase: |
    Come and chat with illumos developers, users, and creators of distributions!
    We'll be here to talk about illumos and answer questions.<p>
    We'll try to be around in the FOSDEM Matrix chat, but if you're like us and
    prefer IRC, please visit us on #illumos-fosdem on freenode. If you don't
    have an IRC client, try <a href="https://webchat.freenode.net">freenode's
    webchat</a>.
themes:
- Operating systems
title: illumos
website: https://www.illumos.org/
show_on_overview: true
chatroom: illumos
---
