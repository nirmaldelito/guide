---
title: Dynamically Set the Coordinates for Each Bar
---
## Dynamically Set the Coordinates for Each Bar

```JAVASCRIPT
      svg.selectAll("rect")
         .data(dataset)
         .enter()
         .append("rect")
         .attr("width", 25)
         .attr("height", 100)
         .attr("x",(d, i) => {
            return i * 30;
         })
         .attr("y",0)

```

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/data-visualization/data-visualization-with-d3/dynamically-set-the-coordinates-for-each-bar/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.
