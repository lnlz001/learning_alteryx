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


