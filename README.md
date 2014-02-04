# Exercise 7

## Sass exercise

- individual exercise
- fork this repo
- follow the steps below

- here are screenshots of the final end result
    - desktop mode
        - http://grab.by/u5Gq
        - http://grab.by/u5GO
    - mobile mode
        - http://grab.by/u5GW
        - http://grab.by/u5H0

---

1. create a variable named **$delius-font** and set the value to **'Delius Swash Caps', sans-serif**
2. add a new *font-family* directive and add the **$delius-font** to 
  - h1
  - h2, h3, h4, h5, h6
  - #footer a 
3. create a variable named **$quattro-font** and set the value to **'Quattrocento Sans', sans-serif**
4. add a new *font-family* directive and add the **$quattro-font** to 
  - p, ul, ol, li, a, span, div
5. create a variable named **$blue-highlight-color** and set the value to **#00A2AD**
6. add a new directive to change the *font color* to t**$blue-highlight-color** for 
  - #header h1
  - #footer a
7. refactor the **#header** and **#header h1** style selectors to be nested selectors *(around line 31 to line 43)*
8. refactor the **#footer** and **#footer a** style selectors to be nested selectors *(around line 57 to line 69)*
9. refactor the **#slideshow** and **#slideshow .orbit-timer** and **#slideshow ul li** style selectors to be nested selectors *(around line 71 to line 83)*
10. in the same way as 7. 8. 9. refactor the entire **#main_nav** set of styles within 
  /* STYLES FOR IPAD AND LARGER (MEDIUM UP) */ 
  @media only screen and (min-width: 40.063em) 
  *around lines 96 to line 159*
11. same as 10. refactor the **#main_nav** set of styles within
  /* STYLES FOR MOBILE SIZE ONLY */
  @media only screen and (max-width: 40em)
  *around lines 173 to line 218*
12. create a variable named **$dark-grey** and set the value to **#444**
13. set the *background color* to **$dark-grey** for
  - /* STYLES FOR IPAD AND LARGER (MEDIUM UP) */
      - #main_nav
      - #main_nav .top-bar
      - #main_nav .top-bar .top-bar-section .right > li,
        #main_nav .top-bar .top-bar-section .left > li
      - #main_nav .top-bar .top-bar-section .right > li > a,
        #main_nav .top-bar .top-bar-section .left > li > a
      - #main_nav .top-bar .title-area
  - /* STYLES FOR MOBILE SIZE ONLY */
      - #main_nav
      - #main_nav .top-bar
      - #main_nav .top-bar .top-bar-section
      - #main_nav .top-bar .top-bar-section .right
      - #main_nav .top-bar .top-bar-section .right > ul
      - #main_nav .top-bar .top-bar-section .right > ul > li
      - #main_nav .top-bar .top-bar-section .right > ul > li > a
      - #main_nav .top-bar .top-bar-section .right > ul > li.has-dropdown > a
