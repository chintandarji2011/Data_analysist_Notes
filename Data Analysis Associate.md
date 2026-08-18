# Data_analysist_Notes
---
Roadmap

---

## 1. Data Analysis Associate:

---
---

 ### __1. Univariate Analysis__: Analysis on `one variable`/`Feature` of the data.
  - There are three ways
      1. __`Summery statistics`__: Determine the value `center` and `spread`.
      2. __`Frequency table`__: This shows how frequently various `values`. 
      3. __`Charts`__: A visual representation of the `distributions of values`.
  ---
  __1. Summary Statistics__:

  ---
  - Measure of __`Center tendencies`__:
    - `Mean`: Average of all numbers and sometimes called `Arithmetic mean`.
    - `Median`:The middle number in `sequence of numbers`
              (to find median, organize each number in `order by size`; the number in the middle is the __`median`__')
    - `Mode`: The number `that occurs most often` within `set of numbers`.
  ---
  - Measure of __`variability`__:
    - `Range`: The difference between __`highest value`__ and __`lowest value`__ within `set of numbers`,
    - `Variance`: The Average square difference of the values from `the mean`.
                 (Unlike previous measure of variability __`Rane`__, `the variance` includes all values in calculation by comparing each value in the calculation)

      $$
      \sigma^2 = \frac{\sum (X-\mu)^2}{N}
      $$

      
    - `Standard deviations`: It is measure that quantify `the amount of variation or dispersion` of set of data values.

    $$
    \sigma = \sqrt\{\frac{\sum (X-\mu)^2}{N}}
    $$
---

__2. Frequency Distribution__

---
__Histogram__: is most commonly used graph to show `the frequency distribution`.
(It looks very much like a bar chart, but there are important differences between them.)

---

__Charts- Visual Analytics__:

__`Visual chart`__: it helps you __compare__ `different values`, understand how __different parts__ impact the `whole`, or `analyze trends`.
- __`chart`__ and __`graph`__ can also be useful for __recognizing data__ that `vary away` from what you are `used to` or `help you` see __relationships between `groups`__.
- __`Visual charts`__: `Column/Bar` chart, `Waterfall` chart, `Tree-map` chart, `Line` chart, `Box` plot

---
---

### 2. __Bivariate Analysis__:Analysis on two `variables`/`Features` of the data.
- some of the common type of bivariate analysis.
  - __`Scatter plot`__: It provides you with `a visual idea` of the `pattern` that your variables follow.
  - __`Regression Analysis`__: It is __catch-all term__ for `a wide variety of tools` that can be used to determine how `data points` might be __related__.
    - `The Points` in the image below seem like they __follow an exponential curve__ (as opposed to a straight line).
      <img width="808" height="488" alt="image" src="https://github.com/user-attachments/assets/76bceecf-c693-4d89-8fc2-195dee3586c3" />

  - __`Correlation coefficients`__: Calculation of __values__ for `correlation coefficients` are performed using a computer, (although here, you can find the `steps` to find __the correlation coefficient__ by hand. This `coefficient` acknowledges you if __variables are related__. )
    <img width="1086" height="482" alt="image" src="https://github.com/user-attachments/assets/126a6c38-328f-4cef-b1b2-7cc70835f93f" />

---
---
### PIVOT TABLE:
- The Pivot table is the powerful tool in Excel.
  - That help to `summarize`, `analyze` and `visualize` __large amount of `data`__.
- It allows users to `rearrange`, `filter` and `group data dynamically` without modifying __the original data__.
- __`Quick data summarization`__: Automatically calculate `sum`, `Averages`, `Counts` etc.
- __`Easy Data Analysis`__: Helps in identify `patterns` and `trends`.
- __`Flexible Data Organization`__: `Rearrange` data using __`drag-and-drop` features__.
- __`Interactive Reports`__: Allows `filtering` and `sorting` without `altering` __the raw data__. 

---
---
### Comparison Analysis:
- It Involve comparing `different variables`, `groups`, or `scenarios` to __identify `similarities`, `differences`, `patterns`, and `trends`__.
- Eg. Compare `sales` and `profit` across all the regions.

<img width="1083" height="501" alt="image" src="https://github.com/user-attachments/assets/42a4611d-42e8-4fa1-abdb-1a7e39f6ac65" />

| COMPARISON | CORRELATION |
|------------|-------------|
|To compare different `entities`, `variables` or `groups`. | Examine the strength and direction of linear relationship between two continuous features. |
|Tells the relative performance, characteristics or behaviors of different variables.|Quantifies the degree of association or dependency between two variables, indicates how chance in one variable relates to change in another variable.|
    

