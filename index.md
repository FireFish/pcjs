---
layout: page
permalink: /
machines:
  - type: pcx86
    id: ibm5150
    name: "IBM PC (Model 5150) with Monochrome Display"
    config: /devices/pcx86/machine/5150/mda/64kb/machine.xml
  - type: c1p
    id: demoC1P
    config: /devices/c1p/machine/8kb/large/machine.xml
---

Welcome to PCjs, home of [PCx86](/docs/pcx86/), the original IBM PC simulation written entirely JavaScript.  It is
one of several JavaScript Machines in the [PCjs Project](https://github.com/jeffpar/pcjs), an open-source project that
includes:

* [PCx86](/docs/pcx86/), an x86-based IBM PC and PC-compatible emulator
* [PC8080](/modules/pc8080/), a 8080-based machine emulator (e.g., [Space Invaders](/devices/pc8080/machine/invaders/))
* [C1Pjs](/docs/c1pjs/), a 6502-based emulation of the Ohio Scientific [Challenger 1P](/devices/c1p/)

All PCjs computer simulations are written entirely in [JavaScript](/modules/).  No Flash, Java or other plugins are
required.  Supported browsers include modern versions of Chrome, Safari, Firefox, Internet Explorer (v9.0 and up), Edge,
and assorted mobile browsers.

{% include machine.html id="ibm5150" %}

The [JavaScript Machine](/devices/pcx86/machine/5150/mda/64kb/) above uses [PCx86](/docs/pcx86/) configured with an Intel
8088 running at 4.77Mhz, with 64Kb of RAM and an IBM Monochrome Display Adapter.  For more control, there are also
[Control Panel](/devices/pcx86/machine/5150/mda/64kb/debugger/) and [Soft Keyboard](/devices/pcx86/machine/5150/mda/64kb/softkbd/)
configurations, featuring the built-in PCx86 Debugger.  For even greater control, build your own PC. The
[PCx86 Documentation](/docs/pcx86/) will help you get started.

PCx86 has steadily evolved to support more classic x86-based machines, including the IBM PC XT, the 80286-based IBM PC AT,
and the 80386-based COMPAQ DeskPro 386.  PCx86 fully supports the original machine ROMs, video cards, etc, and all
machines run at their original speeds.

The goals of the [PCjs Project](/docs/about/) are to create fast, full-featured simulations of classic
computer hardware, help people understand how these early machines worked, make it easy to experiment with different
machine configurations, and provide a platform for running and analyzing old computer software.

Demos
---
Some pre-configured machines are shown below, ready to run BASIC, DOS, Windows, OS/2, and other assorted software.

{% include screenshot.html src="/apps/pcx86/1981/visicalc/thumbnail.jpg" width="200" height="120" title="IBM PC running VisiCalc" link="/apps/pcx86/1981/visicalc/" %}
{% include screenshot.html src="/devices/pcx86/machine/5150/cga/64kb/donkey/thumbnail.jpg" width="200" height="120" title="IBM PC running DONKEY.BAS" link="/devices/pcx86/machine/5150/cga/64kb/donkey/" %}
{% include screenshot.html src="/disks/pcx86/os2/ibm/1.0/thumbnail.jpg" width="200" height="120" title="IBM PC AT w/EGA, OS/2 1.0" link="/disks/pcx86/os2/ibm/1.0/" %}
{% include screenshot.html src="/devices/pcx86/machine/5160/cga/256kb/win101/thumbnail.jpg" width="200" height="120" title="IBM PC XT w/CGA, Windows 1.01" link="/devices/pcx86/machine/5160/cga/256kb/win101/" %}
{% include screenshot.html src="/disks/pcx86/windows/1.01/thumbnail.jpg" width="200" height="120" title="IBM PC XT w/EGA, Windows 1.01" link="/disks/pcx86/windows/1.01/" %}
{% include screenshot.html src="/disks/pcx86/windows/2.0x/thumbnail.jpg" width="200" height="120" title="COMPAQ DeskPro 386, Windows/386 2.01" link="/disks/pcx86/windows/2.0x/" %}
{% include screenshot.html src="/disks/pcx86/windows/3.00/thumbnail.jpg" width="200" height="120" title="IBM PC AT w/EGA, Windows 3.00" link="/disks/pcx86/windows/3.00/" %}
{% include screenshot.html src="/disks/pcx86/windows/3.10/thumbnail.jpg" width="200" height="120" title="IBM PC AT w/VGA, Windows 3.10" link="/disks/pcx86/windows/3.10/" %}
{% include screenshot.html src="/disks/pcx86/windows/win95/4.00.950/thumbnail.jpg" width="200" height="120" title="COMPAQ DeskPro 386, Windows 95" link="/disks/pcx86/windows/win95/4.00.950/" %}
{% include screenshot.html src="/disks/pcx86/cpm/1.1b/thumbnail.jpg" width="200" height="120" title="IBM PC w/MDA, CP/M-86" link="/disks/pcx86/cpm/1.1b/" %}
{% include screenshot.html src="/disks/pcx86/games/microsoft/adventure/thumbnail.jpg" width="200" height="120" title="IBM PC w/MDA, Microsoft Adventure" link="/disks/pcx86/games/microsoft/adventure/" %}
{% include screenshot.html src="/disks/pcx86/games/infocom/zork1/thumbnail.jpg" width="200" height="120" title="IBM PC w/CGA, Zork I" link="/disks/pcx86/games/infocom/zork1/" %}

There are many more [PCx86 Demos](/devices/pcx86/machine/#ready-to-run-app-demos), including an
[IBM PC with Dual Displays](/devices/pcx86/machine/5150/dual/64kb/) demonstrating early multi-monitor support,
and multiple IBM PC XT machines running side-by-side with [CGA Displays](/devices/pcx86/machine/5160/cga/256kb/array/)
and [EGA Displays](/devices/pcx86/machine/5160/ega/640kb/array/).

C1Pjs
---
Below is the [OSI Challenger C1P](/docs/c1pjs/), another simulation in the PCjs Project.
It simulates Ohio Scientific's 6502-based microcomputer, released in 1978.  More details about this simulation
and the original machine are available in the [C1Pjs Documentation](/docs/c1pjs/).

{% include machine.html id="demoC1P" %}

License
---
The [PCjs Project](https://github.com/jeffpar/pcjs) is now an open-source project on [GitHub](http://github.com/).
All published portions are free for redistribution and/or modification under the terms of the
[GNU General Public License](/LICENSE) as published by the Free Software Foundation, either version 3 of the License,
or (at your option) any later version.

You are required to include the following copyright notice, with a link to [{{ site.pcjs.domain }}]({{ site.url }}/):

> [PCjs]({{ site.url }}/) © 2012-2016 by [Jeff Parsons](mailto:Jeff@pcjs.org) ([@jeffpar](http://twitter.com/jeffpar))

in every source code file of every copy or modified version of this work, and to display that notice on every web page
or computer that runs any version of this software.

See [LICENSE](/LICENSE) for details.

More Information
---
Learn more about the [PCjs Project](/docs/about/) and [PCx86](/docs/about/pcx86/).  To
create your own PCx86 machines, see the [PCx86 Documentation](/docs/pcx86/) for details.

If you have questions or run into any problems, feel free to [tweet](http://twitter.com/jeffpar) or
[email](mailto:Jeff@pcjs.org).
