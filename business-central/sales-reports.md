---
title: Sales Reports and Analytics
description: See which sales reports and analytics are available in the standard version of Business Central so that you can keep track of your business.
author: AndreiPanko

ms.service: dynamics365-business-central
ms.topic: conceptual
ms.search.keywords: reporting
ms.date: 06/01/2021
ms.author: andreipa

---
# Sales Reports and Analytics in Business Central

Sales reporting in [!INCLUDE [prod_short](includes/prod_short.md)] allows sales and business professionals to get insights and statistics about current and past sales activities.  

## Reports

The following table describes some of the key reports in sales reporting.

|Report |Object ID|Description  |
|---------|---------|---------|
|**Customer – Order Summary**|107| Shows the order detail with the quantity not yet shipped for each customer in three periods of 30 days each, starting from the specified date. There are also columns with orders to be shipped before and after the three periods and a column with the total order detail for each customer. Use the report to analyze a company's expected sales volume. |
|**Customer – Top 10 list**|111| Shows information on customers' purchases and balances for a selected period. You can choose the number of customers that will be included in the report. Only customers that have either purchases during the period or a balance at the end of the period will be included.<br>The customers are sorted in order of amount, and you can choose whether they are sorted by sales amount or balance. The report gives a quick overview of the customers that purchase the most or that owe the most.|
|**Customer/Item Sales**|113|Shows a list of item sales for each customer during a selected time period. The report contains information on quantity, sales amount, profit, and possible discounts. It can be used, for example, to analyze a company's customer groups.|
|**Inventory – Customer Sale**|713|An overview from the perspective of the warehouse sight. This is a different view compared to the **Customer/Item sale** report, and it shows the item first and then the customer who bought this product.|
|**Customer – Sales list**|119|Shows customer sales for a period. You use it to report to the customs and tax authorities. You can choose to include only customers with total sales that exceed a minimum amount. You can also specify whether you want the report to show address details for each customer.<br>The report is based on recorded sales (LCY) from customer ledger entries. At the bottom of the report, the total reported sales are shown in LCY. The total is based on the customers you have included in the report, that is the customers that are within the filters on the Customer FastTab and that have total sales greater than the amount specified in the **Amounts (LCY) Greater Than** field on the **Options** FastTab.|
|**Customer – Balance to date**|121|Shows a detailed balance for selected customers. Use the report at the close of an accounting period or fiscal year, for example.|
|**Customer – Trial Balance**|129|Shows a detail balance for selected customers. You can use the report to verify that the balance for a customer posting group is equal to the balance on the corresponding G/L account on a certain date. Use the report at the close of an accounting period or fiscal year, for example. If you need a more detailed version of this type of report, use the **Customer Detail Trial Balance** (104) report.|
|**Sales Statistic**|112|[!INCLUDE [reports-sales-statistics](includes/reports-sales-statistics.md)] |
|**Sales Reservation Avail.**|209|Shows the availability of items for shipment on sales documents. You determine whether the report indicates the status of each document or of each sales line. When you print the report, you can also update the quantity that is available for shipment in the **Qty. to Ship** field on the sales lines. Then you can use the report to determine which documents to post.<br>There is also a capability with which you could set the amount of goods to be shipped. **Note**: This report is not available for advanced warehouse functionality.|
|**Warehouse Shipment Status**|7313|This report can be used for all locations where the **Require Shipment** field is selected. The **Warehouse Shipment Status** report shows you all unposted warehouse shipment documents, including the locations, bin codes, document status, quantities, and so on. This report is perfect to get an overview.|
|**Inventory Picking List**|813|Displays a list of the sales orders in which an item is included. The following information is shown for each item: Sales order line with the name of the customer, variant code, location code, bin code, shipment date, quantity to be shipped, and unit of measure. The quantity to be shipped is totaled for each item. The report can be used when items will be collected from the inventory.<br>**Note**: This report is not available for advanced warehouse functionality.|
|**Inventory Sales Back Orders**|718|Shows a list with the order lines whose shipment date has been exceeded. The following information is shown for the individual orders for each item: number, customer name, customer's telephone number, shipment date, order quantity and quantity on back order. The report also shows whether there are other items for the customer on back order.|
|**Inventory Order Details**|708|Displays a list of the orders that have not yet been shipped and the items in the orders. It shows the order number, customer's name, shipment date, order quantity, delayed quantity, outstanding quantity, and unit price, as well as any potential discount percentage and amount. The quantity on back order and outstanding quantity and amount are totaled for each item. Use the report to find out whether there are currently shipment problems or any can be expected.|



## Tasks

The following articles describe some of the key tasks for analyzing the state of your business:

* [Create Analysis Reports](bi-how-create-analysis-views-reports.md)  
* [View the Availability of Items](inventory-how-availability-overview.md)


## See also

[Setting Up Sales](sales-setup-sales.md)  
[Sales](sales-manage-sales.md)  
[Reserve Items](inventory-how-to-reserve-items.md)

[!INCLUDE[footer-include](includes/footer-banner.md)]
