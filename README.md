# Macintosh Classic Reloaded RAM Expansion Board

![Finished Board](/ClassicRAMBoard.jpg)

So you've bought a dead mac classic. The logic board is bombed, and there's no expansion board inside. Or there was, and it, too, has incurred the wrath of Maxell. Well, you now know you can get a Macintosh Classic Reloaded board, at least, but what about the RAM expansion? Well - between @Branchus and myself, i've worked on this in Sprint in my limited spare time lately.

The board as it stands, once populated with 256x4 SOJ RAM chips, will give you an additional 1MB of RAM, with the SIMM sockets allowing you to add a further two 1MB SIMM's. It won't work with anything larger than 4MB - that's a restriction the BBU chip imposes (limited address lines).

The Gerbers are available as individual files, or as a ZIP archive for easy board production (works fine with JLCPCB)

The BOM and Pick & Place data are available in the root, as Excel files - you may have to confirm the parts at production time, but barring Capacitor C1, all parts are 1206 package. Capacitor C1 is a 47uf 16v Tantalum, Size D (EIA 7343-31).

The SIMM sockets can be purchased from PE Connectors. 
