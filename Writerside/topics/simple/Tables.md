[//]: # (title: Custom table component)

<dataFrame src="pivotGroupBy.html"/>

<!---END-->

To group by all columns except pivoted use `groupByOther`:

<!---FUN pivotGroupByOther-->

```kotlin
df.pivot { city }.groupByOther()
```

<dataFrame src="pivotGroupByOther.html"/>

<!---END-->

## Aggregation

To aggregate data groups with one or several statistics use `aggregate`:

<dataFrame src="pivotAggregate.html"/>

<!-- 
This line should generate error:
DF002: Cannot read the iframe contents from the specified location

<dataFrame src="pivotSeparate.html"/>
-->
