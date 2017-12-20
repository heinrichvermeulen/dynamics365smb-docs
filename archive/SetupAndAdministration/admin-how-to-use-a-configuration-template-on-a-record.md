---
    title: How to Use a Configuration Template on a Record | Microsoft Docs
    description: You can apply a data template to any record that is in [!INCLUDE[d365fin](includes/d365fin_md.md)] and use this technique to change or modify a record. However, when you do this, you overwrite existing values in the record with those of the template. Consequently, you should be careful when you apply a template to existing records.
    services: project-madeira
    documentationcenter: ''
    author: SorenGP

    ms.service: dynamics365-financials
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 07/01/2017
    ms.author: sgroespe

---
# How to: Use a Configuration Template on a Record
You can apply a data template to any record that is in [!INCLUDE[d365fin](includes/d365fin_md.md)] and use this technique to change or modify a record. However, when you do this, you overwrite existing values in the record with those of the template. Consequently, you should be careful when you apply a template to existing records.  
  
### To use a configuration template on a record  
  
1.  Create a new contact, customer, item, or vendor record. For example, to create a new customer record, Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customers**, and then choose the related link.  
  
2.  On the **Home** tab, in the **New** group, choose **New**. The **New - Customer Card** window opens.  
  
3.  Enter a customer number and enter a customer name. In the **Process** group, choose **Apply Template**.  
  
4.  Select a customer template that you have created from the list in the **Data Template List** window. Choose the **OK** button.  
  
 The default values from the chosen customer template are copied to the customer card.  
  
## See Also  
 [Migrate Customer Data](../migrate-customer-data.md)