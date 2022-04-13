---
title: Instalacja Jekyll pod Windows
layout: page
category: tutorial

---
Windows nie jest oficlajnie wspiraną platformą. Do swoje prawidłowego działania potrzebuje:
- Ruby
- RubyGems
- GCC i Make


Instalacja pod Windowsem nie jest przyjemna.
- gem 'wdm', '>= 0.1.0' if Gem.win_platform?
- bundle add webrick