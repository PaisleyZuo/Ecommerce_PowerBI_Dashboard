
# E-Commerce Data Power BI Dashboard

## Project Description

This project is a **Power BI dashboard** based on the [Kaggle E-Commerce Dataset](https://www.kaggle.com/) aimed at uncovering key insights regarding sales, profitability, product performance, and customer segmentation.

---

## Data Story Objectives

### Objective

- Review current product lines and identify areas for improvement  

### Users

- Head of Finance

### Actions

- Identify areas that can improve revenue  
- Identify low-performing products and regions  

### Usage Frequency

- Monthly

---

## Key Performance Indicators (KPIs)

| KPI Name | Objective | Definition | Visual | Data Source|
|----------|------|----------|----------|-------------|
| Profit| Profit is the financial driver of the business | Profit | Order Details.csv | Trend, Composition, ΚΡΙ |
| Quantity| Quantity tells you how much volume is going through each area of the business | Units | Order Details.csv | KPI |
| Order Volume| Order volume indicates the shipment volume in the warehouse | Distinct Count of Order ID | List of Orders.csv | KPI |

---

## Project Structure

1. **Data Story Definition**
2. **Load and Transform Data**
   - Format Data
   - Join Data
   - Others: blank rows, duplicate data...
3. **Visualizing the Dataset**
   - choose KPIs chart: Z pattern
   - Multi-row card
   - Profit trend chart
   - Profit by category chart: chart setup, format matrix chart
e.Profitability by customer chart: chart setup, format scatter chart
f.Profit by state chart: chart setup, format tree map
4. **Additional Insights 深入洞察**
   - 利润洞察页面
   - 带时间轴的交互式图表
   - Key Influencers 图表
   - Q&A 图表
5. **Final Touches 最后美化**
   - 添加切片器与交互筛选器

---

## 🔍 Insights 洞察总结

- 总体盈利能力直到 2019 年 10 月前一直为负。
- **Electronic Games** 和 **Tables** 两个品类盈利能力为负，应重点关注。
- 332 位客户中有 **182 位客户盈利为负**，占比约为 **55%**。
- 不盈利客户集中于：**Madhya Pradesh**、**Maharashtra**
- **Bookcases** 和 **Printers** 是推动收入的关键产品子类。

---

## 💡 Recommendations 建议

- 请门店经理评估最不盈利的客户。
- 分析表现不佳的州，找出客户盈利能力差异大的原因。
- 暂停销售 Tables 和 Electronic Games，直到成本结构得到优化。
- 扩大盈利子类的销售，以维持持续的盈利趋势。

---

## 📁 Project Files 项目文件

- `Ecommerce_Dashboard.pbix`: Power BI 项目文件  
- `Order Details.csv`, `List of Orders.csv`: 原始数据文件  
- `Dashboard_Screenshots/`: 仪表板截图  

---

## 📸 Dashboard Screenshots 仪表板截图

![Dashboard 1](Dashboard_Screenshots/dashboard1.png)  
![Dashboard 2](Dashboard_Screenshots/dashboard2.png)
