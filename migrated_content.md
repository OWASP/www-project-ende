---

layout: col-sidebar
title: OWASP Ende
tags: example-tag
level: 0
type: tool

---
# Main

<div style="width:100%;height:90px;border:0,margin:0;overflow: hidden;">

![_lab_big.jpg](_lab_big.jpg "_lab_big.jpg")

</div>

<table>
<tbody>
<tr class="odd">
<p>OWASP EnDe is an Encoder, Decoder, Converter, Transformer, Calculator, for various codings used in the wild wide web. Collection of functions (herein called actions) for various codings, encodings, decodings and convertions. The aim is/was mainly driven by the requirements for HTTP/HTML-based functionality.</p>
<h3 id="introduction">Introduction</h3>
<h3 id="quick_installation">Quick Installation</h3>
<p>=</p>
<ul>
<li>download <a href="http://ende.my-stp.net/EnDe.tgz">Stable tarball</a> or from github <a href="http://github.com/OWASP/EnDe">Git Repository</a></li>
<li>unpack EnDe.tgz</li>
<li>point your browser to index.html in the installation directoy</li>
<li>enjoy</li>
</ul>
<h3 id="description">Description</h3>
<p>Abstract: EnDe is a collection of tools (built-in in the browser) for data encoding/decoding and conversion.<br />
The tools are:</p>
<table>
<thead>
<tr class="header">
<th><p>Tool</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Character</strong></p></td>
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
<tr class="even">
</tr>
<tr class="odd">
</tr>
</tbody>
</table>
<p>Just a short list of supported <em>conversions</em>:<br />
:ASCII↔Unicode, text↔URL-encoded, text↔Base64, text↔uuencode, MD4, MD5, SHA, SHA256, CRC-16, AES, Block TEA, Unix Timestamp↔Windows Timestamp↔ASP.NET Timestamp, dezimal dottet IP↔IPv6↔Integer↔binary, ... <sub>where <em>text</em> means any valid Unicode data</sub></p>
<h2 id="licensing">Licensing</h2>
<p>OWASP EnDe is free to use. It is licensed under the GPL v2 license.</p></td>
<p>OWASP EnDe provides:</p>
<ul>
<li>Encoder/Decoder</li>
<li>Timestamp en-/decoder</li>
<li>IP en-/decoder</li>
<li>RegEx beautifier</li>
</ul>
<h2 id="presentation">Presentation</h2>
<h2 id="project_leader">Project Leader</h2>
<p><a href="mailto:achim@owasp.org">Achim Hoffmann</a></p>
<h2 id="related_projects">Related Projects</h2>
<h2 id="main_links">Main Links</h2>
<ul>
<li><a href="http://github.com/OWASP/EnDe">Git Repository</a></li>
<li><a href="http://ende.my-stp.net/EnDe.tgz">Stable tarball: unpack and load EnDe.html in your browser</a></li>
<li><a href="https://github.com/OWASP/EnDe/archive/master.zip">Latest zip (5/2013) from github: unpack and make gen.all and load EnDe.html in your browser</a></li>
<li><a href="http://ende.my-stp.net/EnDe.man.html#QUICK_START">Introduction</a></li>
<li><a href="http://ende.my-stp.net/index.html">OWASP EnDe Project - Tool</a></li>
<li><a href="http://ende.my-stp.net/EnDe.man.html#INSTALLATION">Installation</a></li>
<li><a href="http://ende.my-stp.net/EnDe.man.html#NAME">Documentation</a></li>
<li><a href="http://ende.my-stp.net/EnDe.man.html?EnDe.FAQ.txt">FAQ</a></li>
<li><a href="http://www.owasp.org/index.php/Category:OWASP_CAL9000_Project">related/based on: OWASP CAL9000 Project</a></li>
<li><a href="http://ende.my-stp.net/EnDe.man.html#TARGET_AUDIENCE">Target Audience: builders, breakers, defenders</a></li>
</ul>
<h2 id="ohloh">Ohloh</h2></td>
<ul>
<li><a href="http://ende.my-stp.net/EnDe-1.0rc12.tgz">EnDe version 1.0RC12</a></li>
</ul>
<h2 id="email_list">Email List</h2>
<p><a href="https://lists.owasp.org/mailman/listinfo/owasp-ende-project">Sign Up!</a></p>
<h2 id="news_and_events">News and Events</h2>
<ul>
<li>[2015] functions for en-/decoding APEX, DWR, GWT</li>
<li>[2014] more special unicode characters (combining diaresis, diacrit, etc.)</li>
<li>[2013] minor improvments</li>
<li>[2012] latest tested and stable tarball</li>
</ul>
<p>Please see <a href="https://github.com/OWASP/EnDe"><a href="https://github.com/OWASP/EnDe">https://github.com/OWASP/EnDe</a></a> for latest version.</p>
<h2 id="in_print">In Print</h2></td>
</tr>
</tbody>
</table>

# FAQs

[Click here for the FAQ
document.](http://ende.my-stp.net/EnDe.man.html?EnDe.FAQ.txt)

# Acknowledgements

## Volunteers

EnDe is developed by a worldwide team of volunteers. The primary
contributors to date have been:

  - xxx

# Road Map and Getting Involved

As of July, the priorities are:

  - Abstarct

EnDe consist of two parts: the core library (API) and the browser
interface (GUI). The issues are mapped to either of these categories.

## Objectives

OWASP EnDe Project - Encoder, Decoder, Converter, Transformer,
Calculator

Collection of functions for various codings, encodings, decodings and
convertions used in the wild wide web. The aim is/was mainly driven by
the requirements for HTTP/HTML-based functionality. Copy\&paste must be
possible within a browser and functions should be called by just one
click.

## Current State

EnDe is currently (2012 .. 2015) stable according the offered
functionality.

## Pending ..

  - ...

## Pending or Planed Requirements / Improvements

### API

  - implementing more hashes like Adler-32, Ghost, Haval, Tiger, ...
  - implementing more encryptions like CAST, DES, TrippleDES, GOST,
    Loki97, RC2, SaferPlus, Serpent, TwoFish
  - implementing codings like UTF-EBCDIC
  - building an object oriented API beside the existing
    procedural/functional API

### GUI

  - replace the hardcoded dispatcher with a generated one
  - build stand-alone applicaion with XUL
  - build Firefox add-on

## Fixed / Completed

  - 12/2016 moved from <https://github.com/EnDe/EnDe> to
    <https://github.com/OWASP/EnDe>
  - 12/2012 EnDe.lib.zap for usage in
    [ZAP](OWASP_Zed_Attack_Proxy_Project "wikilink")
  - 06/2012 setup at github.com
  - 12/2011 implementing BlowFish encryption
  - 7/2009 selecting license (GPL2, CC-2.5, or a mix?)
  - 5/2009 generating some documentation
  - 7/2008 implementing sha384, sha512 encryption

Involvement in the development and promotion of EnDe is actively
encouraged\! You do not have to be a security expert in order to
contribute. Some of the ways you can help:

  - xxx

# Project About

__NOTOC__ <headertabs />

[Category:OWASP Project](Category:OWASP_Project "wikilink")
[Category:OWASP_Builders](Category:OWASP_Builders "wikilink")
[Category:OWASP_Defenders](Category:OWASP_Defenders "wikilink")
[Category:OWASP_Document](Category:OWASP_Document "wikilink")
[Category:OWASP Tool](Category:OWASP_Tool "wikilink") [Category:OWASP
Download](Category:OWASP_Download "wikilink")
