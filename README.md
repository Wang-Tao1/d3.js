1.  **' + '  类型转换**

   ```javascript
   // + 的作用是类型转化，不加输出的是 string类型，有 + 号的话输出的是 number类型
   const width = +svg.attr('width')  
   ```

2. **高度由比例尺自动生成**

   ```javascript
    yScale.bandwidth())
   ```

   

   3.**在 .domain() 中**

   ```javascript
    .domain([d3.min(data, xValue), d3.max(data, xValue)])  =  .domain(d3.extent(data, yValue))
    .domain([d3.min(data, yValue), d3.max(data, yValue)])  =  .domain(d3.extent(data, yValue).reverse())  // 记住使用reverse（）使y轴从底部开始,因为 y轴 数据是从上到下的，但是轴数据应该为从下到上；
   ```

   

