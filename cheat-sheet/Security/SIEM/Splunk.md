## Searches and Reports

- Searching

  ![image](https://user-images.githubusercontent.com/37131079/152657579-90f423dc-b7ab-42f1-9d69-9abbe73fa958.png)

On the search bar, type in: 
```ruby
  index = firewall
```
Assuming you have multiple firewall vendors data ingesting into the firewall index, to search a single firewall vendor, add the "sourcetype" to the search query. 
```ruby
  index = firewall sourcetype="palo:threat"
```
- Dashboards

## Administrator




