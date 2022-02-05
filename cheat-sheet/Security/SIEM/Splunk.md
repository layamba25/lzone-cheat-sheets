## Searches, Reports and Alerts | Dashboards

- Searching

  ![image](https://user-images.githubusercontent.com/37131079/152657579-90f423dc-b7ab-42f1-9d69-9abbe73fa958.png)

To search data from an index (e.g firewall data), on the search bar, type in: 
```ruby
  index = firewall
```
Assuming you have multiple firewall vendors data ingesting into the firewall index, to search a single firewall vendor, add the "sourcetype" to the search query. 
```ruby
  index = firewall sourcetype="palo:threat"
```
You can set the time range you want to search for using the Time Range Picker at the right side of the search bar. OR you can include it in your search query as below. (Make sure to use the exact time format the data has)
```
index = firewall sourcetype="palo:threat" earliest=10/19/2018:00:00:00 latest=10/27/2018:00:00:00
```
You can also include time modifier as: ``earliest = -24h@h latest=-2h@h``

[ Splunk Reference ](https://docs.splunk.com/Documentation/Splunk/8.2.4/Search/Specifytimemodifiersinyoursearch)
- Dashboards

## Administrator




