# The information of the APIs of 20 categories, a total of 8,459.
Explanation of the files in this directory.

+ `api_8459.json`, the information of APIs of 20 categories, each API is stored as a dictionary in the list. The fields of the dictionary and their meanings are as follows:
  + `api_id` The id of this API, provided by ProgrammableWeb.com.
  + `api_name` The name of this API.
  + `api_prim_cate` The category of this API, note that the category here is represented by an order number which can be tracked in `categories_20.json`.
  + `api_desc` The functionality description of this API. Descriptions are uniformly converted to lowercase letters.
  + `n_followers` The number of followers of this API, note that the followers information is crawled at July 15, 2019.
  + `n_appear_in_mashup` The number of times the API appears in all mashup services.
+ `categories_20.json` The `name` and `id` mapping list of the 20 categories.
+ `serv_net.csv` The link list of the service composability network. `id1` and `id2` are the two vertices of the link, and the `sign` means the sign of this link.
+ `servnet_id_mapping.csv` In `serv_net.csv`, the `id` of each vertix is started from zero. `servnet_id_mapping.csv` is created to map the `ids` of the vertices in `serv_net.csv` to the order number of the services they represent in the `api_8459.json`.
