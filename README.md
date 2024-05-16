# Amazon System to Website Comparison
### Objective: 
* Need list of orders that are showing late on the Amazon website to provide alert to shipping locations.</br>
* Split late orders into 2 categories based on if they are pallet shipments or small parcel shipments.</br>
* Need list of orders not found in system, but found on website to resolve missing order situations quickly.</br>
* Need list of orders not found on website, but found in system to research if shipping department missed invoicing or are open in system but cancelled on website.</br>
* Previously manually comparing the website and the system was too time consuming to be done daily even with tools in excel.

### Tools used:
* Used python and spreadsheets able to be downloaded from website and system to search for and compile the desired lists.

### Results:
* Task now able to be completed within a few minutes of communication with plants instead of more than an hour.

### Execution instructions:
* Download open orders from website and rename "website.csv"</br>
* Download open orders from system and rename "as_400.csv"</br>
* Drag/drop the 2 csv files into google colab and select Runtime > Run all</br>
* Download newly generated files "late_orders.csv" and "unmatched.csv"
