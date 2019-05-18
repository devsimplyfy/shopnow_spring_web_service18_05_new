

# Instructions
1. Open pom.xml with Intelij or Eclipse
2. Run Main.java
3. Open browser on http://localhost:8080/shopnow


webservices
1-Home-
url-http://localhost:8080/shopnow/Home/16
input - customerId-113



2-Category-
url-http://localhost:8080/shopnow/CategoryNew/5
input-category_id



3-Product_list

url-http://localhost:8080/shopnow/product_list/
input-{
"customerId":"",
"id":"",
"orderBy":"",
"page_number":"",
"search":"",
"min_price":"",
"max_price":"",
}

4-Product_detail-
url-http://localhost:8080/shopnow/product_detail/1488
input-products id 




5-Customer_list
url-http://localhost:8080/shopnow/Customer_list/71
input-customer id from customer table1


6-register_cutomer-
url- http://localhost:8080/shopnow/customer_list_insert/
{"email":"","password":""}


7-login-
url- http://localhost:8080/shopnow/Customer_list_login/
input- {"email":"rrrs@gmail.com","password":"89999"}


8-change_password-
http://localhost:8080/shopnow/customer_add_update/
{"email":"rrr@gmail.com","password":"ajay","newpsw":"99999"}



9.1Addres

Address_list
url-http://localhost:8080/shopnow/customer_address/113 if not provice customer id fetch all address
input-customer_id

Address-insert

http://localhost:8080/shopnow/customer_address_insert/
"{    
    ""customerId"": 107,
    ""type_billing_shipping"": ""billing"",
    ""firstName"": ""Aneel"",
    ""lastName"": ""Thadani"",
    ""address1"": ""surat"",
    ""address2"": ""surat 22"",
    ""address3"": ""surat 333"",
    ""city"": ""surattt "",
    ""state"": ""Gujarat"",
    ""country"": ""India "",
    ""phoneNumber"": ""9999999999"",
    ""isPrimary"": 1,
    ""createdDatetime"": ""2018-01-09""
  }"

Address_delete
http://localhost:8080/shopnow/customer_address_del/
{"id":87,"customerId":107}




10-Deal_detail-
http://localhost:8080/shopnow/Products_Deal/1
input-deal_id

11-view Wish_list 
url - http://localhost:8080/shopnow/wish_list_view/71
input-customer_id


add_wishList,
http://localhost:8080/shopnow/wish_list_insert/
{"custid":"113","id":"160"}
 
  
Delete wishList
http://localhost:8080/shopnow/wish_list_delete/
{"custid":"113","id":"160"}




