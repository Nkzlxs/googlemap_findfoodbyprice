# googlemap_findfoodbyprice
google map find food by price (tiered: 1,2,3,4 in total)

just a quick and stupid tool to get feature that google map don't have which is search by price...

---

# usage

1. replace `API_KEY` to your google map api key

2. install extension that modifies response CORS headers  
   this will be good  
   https://chrome.google.com/webstore/detail/allow-cors-access-control/lhobafahddgcelffkeicbaginigeejlf?hl=en
3. open the file in browser like this  
   ```
   file:///C:/Users/nkzlxs/Desktop/googlemap_scripts/justmap.html?origin=13.761639498709437,%20100.52375864981822
   ```
   file://xxx/justmap.html
   params:
   1. (required) origin: this will be center of map
   2. (optional) maxprice, minprice
   3. (optional) radius

ref: https://developers.google.com/maps/documentation/places/web-service/search-text#required-parameters

by default the red dots are restaurant name that fulfill the criteria price tier < 1

the price tier are 0(most affortable)-4(most expensive)

![image](https://github.com/Nkzlxs/googlemap_findfoodbyprice/assets/35626992/40e957b3-4bcf-4a6e-ac27-cb48ce40b8ed)
