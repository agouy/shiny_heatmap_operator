# Shiny Heatmap Tercen operator

##### Description

The `Shiny Heatmap operator` plots a clustered heatmap.

##### Usage

Input projection|.
---|---
`row`           | factor, variables
`col`           | factor, observations 
`y-axis`           | numeric, measurement (corresponding to the color on the heatmap) 

Output relations|.
---|---
`Operator view`        | view of the Shiny application

##### References

This operator is based on the [pheatmap R function]https://www.rdocumentation.org/packages/pheatmap/versions/1.0.12/topics/pheatmap.

##### See Also

[pairwise_distance_operator](https://github.com/tercen/pairwise_distance_operator), [hclust_operator](https://github.com/tercen/hclust_operator)
