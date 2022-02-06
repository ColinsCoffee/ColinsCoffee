### Review Blog of _Coins - A Journey Through a Rich Cultural Collection_

**Project:** Coins - A Journey Through a Rich Cultural Collection  
**Project Director(s):** Flavio Gortana, Daniela Guhlmann, Franziska von Tenspolde, Prof. Dr. Marian Dörk, Prof. Dr. Bernhard Weisser, Dr. Angela Berthold, Dr. Karsten Dahmen.  
**Project URL:** https://uclab.fh-potsdam.de/coins/

_Coins - A Journey Through a Rich Cultural Collection_ immerses its visitors into a vast collection of coins from across both our world and history. It was built on PixiJS, d3, and React to bring a physical collection of 500,000 coins in the Münzkabinett Berlin museum to the interactive digital world.  

![treasure pile](https://user-images.githubusercontent.com/98109342/152704276-a5a7fe5e-c135-4f3f-96d1-bd0fe5230885.png)

The primary function of this project is clicking on an individual coin in a great big pile of them. When the site first loads up, there are thousands of coins piled ontop of each other which can be selected by hovering one’s mouse over one and clicking it. This is initially worrisome, as the coins are aesthetically arranged in a pirate-treasure styled pile. Dragging one’s mouse across the pile will be ineffective, as hundreds of individual blurbs regarding each coin will render and then disappear quickly.  

After picking the first coin (likely at random), the horde of coins suddenly shifts apart in well animated motion, singling out the selected coin in a bullseye ring. Coins of the same origin as the singled out one will be closer to the spotlighted one for easy access, which is a small but appreciated function. A small box appears with the coin’s specifications and a link to its standing in the Münzkabinett collection. It lists important information, but some items, like the linked image below, are of uncertain origin. For these, a question mark is added after its potential item.  

![singledcoin](https://user-images.githubusercontent.com/98109342/152704311-451f5e56-97e5-4884-80ea-bc1683b8854b.png)

After a few more moments of exploring, the user finds easy ways to organize and filter the coins. They can make separate piles organized by region, country/nation/culture, diameter, material, weight, and age. After dividing the coins into a desired category, the layout of the coins can be rearranged to the desired position. The “plain grid” function was particularly useful and easy to look at in exchange for the pile.  

![listofcoins](https://user-images.githubusercontent.com/98109342/152704553-4e1deb01-a887-4c2b-b182-208c8ef0b259.png)

Users can even select two different properties to organize the coins by, which are then split into piles organized by a grid. For example, properties of Country and Period will organize the coins into a grid with Country on the x axis and Period on the y axis. A continuous variable such as diameter would change the chart into something resembling a bar graph, since that lends itself better to displaying continuous variables than the discrete options. 

![gridfashioned](https://user-images.githubusercontent.com/98109342/152704418-51b5b66e-75cd-4a1b-8d3e-0011053d1d69.png)

Once the intuitive “controls” are learned, it becomes easy and fun to explore the site by scrolling in and out to focus on individual, well rendered coins, and dragging the screen to explore the piles. Without the luxury of a well-working trackpad or possession of dexterous fingers, the navigation of Coins will leave something to be desired. It relies greatly on user ability to carefully and particularly control their cursor when that may not be an option. There are no keybinds for navigation or control, meaning users lacking control in their fingers are barred from the primary functions of this project. This issue could be solved by assigning keybinds to actions such as organization, filters, zooming in and out, or even moving from one specific coin to its neighbor.

After clicking a specific coin you may be linked to the associated Münzkabinett collection on a different site. The collection is based in Germany so the original information is written in German. Google Chrome's translation function for foreign websites does a good job of translating the website for an English audience. 

![munzkabinette](https://user-images.githubusercontent.com/98109342/152704610-b10b0468-b65a-4e31-b7e5-6382d872ecd9.png)

Overall the site moves in a logical, smooth fashion that makes a potentially mundane subject into something fun. It is still important to note that easy navigation is restricted to those with careful control over their hands, and some display options for the coins are overwhelming. Barring these drawbacks which could be fixed in the future, the project has my recommendation and continued interest.
