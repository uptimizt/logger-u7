# Logger U7

Logging a data for debug code


For adding data in log use hook:

## Simple example
```
$var_data = 'test';
do_action("logger_u7", $var_data);
```

## Example with multiple var for log and labels

```
$var_data1 = 'test1';
do_action("logger_u7", ['tag1', $var_data1]);

$var_data2 = 'test2';
do_action("logger_u7", ['tag2', $var_data2]);

```


After debug data can view in admin: Tools / Logger
