# Learning Alteryx

### DataTypes
- String
    - sequence of chars
    - qualitative or dimensional
    - varialbe (name) or fixed (zipcode)
- Numeric
    - quantitative or measures
    - 7 sub-numeric types
        - bytes, int16, int32, int64, fixed, float, double
- DateTime
    - Dates
    - Times
    - DateTimes
    - many formats
- Boolean
    - smallest data type
    - true (not 0) or false (0)
- Spatial
    - a point (x,y)
    - line
    - polygon

#### Viewing DataTypes

- preview pane
- metadata
- in the outputs, the output node will determine the datatypes available
    - for example, databases will have many datatypes but CSVs will only have strings

### Text Input Tool
Good for manually creating a lookup table in your pipeline  


### Select Tool
- change data types
- remove columns
    - do this early on
    - it will improve processing speed and memory consumption
- change column order for visual purposes
    - can use the up and down arrows
- the unknown column can be selected to prepare for future changes
- review results in the preview pane at the bottom - columns have been affected
- some tools contain embedded select tools, such as JOIN node


### Browse Tool
- interactive explore the whole data
- however it is very memory intensive
- best to explore as much as possible with just the preview panes

