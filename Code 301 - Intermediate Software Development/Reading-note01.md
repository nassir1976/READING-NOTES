
[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-1
### SMACSS and Responsive Web Design
What’s the Difference between Adaptive and Responsive Design? So first up, what’s the key differences between responsive and adaptive design?

- responsive is fluid and adapts to the size of the screen no matter what the target device. Responsive uses CSS media queries to change styles based on the target device such as display type, width, height, etc., and only one of these is necessary for the site to adapt to different screens.

- Adaptive design, on the other hand, uses static layouts based on breakpoints which don’t respond once they’re initially loaded. Adaptive works to detect the screen size and load the appropriate layout for it – generally you would design an adaptive site for six common screen widths:

320

480

760

960

1200

1600.
- On the surface, it appears that adaptive requires more work as you have to design layouts for a minimum of six widths. However, responsive can be more complex as improper use of media queries (or indeed not using them at all) can make for display and performance issues.

- The latter in particular has created a lot of discussion over the past few years as it’s been the case that many sites deliver the full desktop model which, even if it’s not loading on the mobile device, slows sites down considerably. To get around this, you can use media queries–but there will be a few tradeoffs since a responsive site is never going to be as quick as a dedicated mobile site.

 ### Why Use Adaptive Design?
- Adaptive is useful for retrofitting an existing site in order to make it more mobile-friendly. This allows you to take control of the design and develop for specific, multiple viewports. The number of viewports that you choose to design for is entirely up to you, your company and overall budget. It does, however, afford you a certain amount of control (for example over content and layout) that you won’t necessarily have using responsive design.
### Why Use Responsive Design?
- The majority of new sites now use responsive, which has been made easier for less experienced designers and developers, thanks to the availability of themes accessible through CMS systems such as WordPress, Joomla, and Drupal.

- Responsive doesn’t offer as much control as adaptive, but takes much less work to both build and maintain. Responsive layouts are also fluid and whilst adaptive can and do use percentages to give a more fluid feel when scaling, these can again cause a jump when a window is resized. For example, in the image below, which shows a fluid layout, the designer is using percentage widths so that the view will be adjusted for each user.

- With responsive, you will be designing with all layouts in mind and this, of course, can confuse the process and make it quite complex. This means that you should focus on creating a viewport for mid-resolution and you can then use media queries to adjust for low and high resolutions later on.

- “SMACSS is becoming one of the most useful contributions to front-end discussions in years” * I’ve been analyzing my process (and the process of those around me) and figuring out how best to structure code for projects on a larger scale. What I've found is a process that works equally well for sites small and large.
Learn how to structure your CSS to allow for flexibility and maintainability as your project and your team grows.

- attribution https://www.uxpin.com/studio/blog/- responsive-vs-adaptive-design-whats-best-choice-designers/