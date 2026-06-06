GOLDFISH FORMAT TOOL V1.3 - USER MANUAL

By Matt Zielinski | 2026-06-05

~<><~

WHAT IS GOLDFISH?

Goldfish keeps your Excel sheets clean. Strict framework, gentle enforcement.



Think of it like a fish tank filter. It stops the mess before it starts, so you never have to clean up later. Tiny, uses no memory, has no memory. Small program, big appetite.



You get 5 locked columns and 4 rules that run automatically. Efficiency through simplicity. It doesn’t think, it just works.



GETTING STARTED - 3 MINUTES



Start Goldfish

Open the "GoldfishV13_Master" folder. Hold Shift + right-click empty space, pick “Open PowerShell window here”. Type "npm start" and hit Enter. Leave that window open.



Add to Excel 

Open Excel → Insert → My Add-ins → Upload My Add-in. Pick "manifest.xml" from the folder and upload.



Find Your Button

You’ll see a new tab called GoldfishV1.3 at the top. One button inside called "Goldfish ON/OFF". Limited features is the feature.



No tab showing? Close Excel all the way, then try step 2 again.



HOW TO USE



Goldfish works on any table with 5 columns: A, B, C, D, E. Row 1 is your headers.



Columns Stay Locked  

Goldfish isn’t picky about names. Call them Item, Task, Widget, whatever makes sense to you. 



If someone deletes a column or clears row 1, just click "Goldfish ON/OFF". Goldfish puts Column 1 through Column 5 back and flashes them yellow. Problem fixed.



No Extra Spaces  

Type “  Toner  ” in column A and Goldfish changes it to “toner” right away. Knock out clutter, not memory space. Extra spaces make Excel think things are different when they’re not.



No Duplicates  

Column A is one item per row. Type “Toner” in A2, then “toner” in A3 and A3 turns red. Goldfish is telling you it already exists. Change it.



No Formula Loops  

Column E is for dependencies. Normal formulas like "=B2*C2 work anywhere in B-E Table formulas that depend on the whole sheet go in the final row of column E only. If you try = anywhere else in Column E, Goldfish deletes it instantly. Loops crash Excel. Goldfish blocks them on instinct. Laughably simple, Shockingly effective.


Scan Dependencies

Right-click the final row in Column E → "Scan Dependencies". Goldfish reads all formulas above and writes what depends on what in that cell. Toggle Goldfish OFF then ON again to refresh the map. If the becomes a wall of text, your table is too complex. Split it.


Columns F and beyond? Add notes, dates, links, whatever you need. Goldfish ignores them. Only A-E are protected.



WHAT TO EXPECT



No popups asking “are you sure” every 5 seconds. No 20 buttons to learn. Small mind, big thoughts.



If your sheet ever looks off, close Excel, run "npm start" again, and click "Create Table". That fixes almost everything.



UNINSTALLING



Don’t need it anymore? Close Excel, double-click "uninstall.bat" , then delete the "GoldfishV13_Master" folder. Done. Uses zero memory when closed.



QUICK FIXES



Tab missing → Close Excel, run npm start, upload http://manifest.xml again  

Red cells in column A → You typed the same item twice. Rename one of them.

Still stuck? Ask any AI assistant and paste this error. Goldfish is simple, so fixes are usually 1 click.



FAQ

WHAT HAPPENS IF I IGNORE THE METHOD?
Goldfish only enforces 4 rules. If you jam 50 formulas in one table, nest data sideways, or fight the 5-column rule, you could lose data. But that only happens if you blatantly ignore the anti-complexity principle. Follow the method: split complex tables, use final row for logic, keep it simple. Goldfish protects your data, not your bad habits.

WHY ONLY 5 COLUMNS?
Goldfish keeps data simple on purpose. 5 locked columns mean your tables move as 1 clean block - no orphaned data. If A-E feels cramped, split into a new table instead. Simple sheets don’t break, and they copy/paste without spilling.

CAN I STACK TABLES?
Yes, but not in one Goldfish file. Use separate Goldfish files and arrange windows side by side. One table per file keeps enforcement fast and reliable. If necessary copy and paste into a non-goldfish file. That file is your fish tank, add more fish if you want/need to but watch for overcrowding.

WHY CAN’T I RENAME THINGS IN COLUMN A?
Column A names are IDs. Rename breaks formulas that point to it. Make a new row instead. Goldfish protects your links.

HOW DO I UPDATE DEPENDENCIES?
Right-click the final row of Column E → "Scan Dependencies". Goldfish scans B-E and rewrites the map. Do this after adding new formulas.

WHY IS MY DEPENDENCIES CELL FULL OF TEXT?
50 formulas = table too complex. Goldfish works best with 5 columns and <10 formulas per table. Split into 2 tables. Make a fish tank.


~><>~



Copyright 2026 Matt Zielinski. Goldfish Formatting Tool.  

Strict framework, gentle enforcement.



---