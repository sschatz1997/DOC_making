***
## Database List

## views
```
+----------------+--------------+------+-----+---------------------+-------------------------------+
| Field          | Type         | Null | Key | Default             | Extra                         |
+----------------+--------------+------+-----+---------------------+-------------------------------+
| id             | int(11)      | NO   | PRI | NULL                | auto_increment                |
| access_page    | varchar(150) | NO   |     | NULL                |                               |
| access_counter | int(11)      | YES  |     | NULL                |                               |
| access_date    | timestamp    | NO   |     | current_timestamp() | on update current_timestamp() |
+----------------+--------------+------+-----+---------------------+-------------------------------+
```

## IPviews
```
+-------------+--------------+------+-----+---------------------+-------------------------------+
| Field       | Type         | Null | Key | Default             | Extra                         |
+-------------+--------------+------+-----+---------------------+-------------------------------+
| id          | int(11)      | NO   | PRI | NULL                | auto_increment                |
| access_page | varchar(150) | NO   |     | NULL                |                               |
| ipAddr      | varchar(45)  | NO   |     | NULL                |                               |
| access_date | timestamp    | NO   |     | current_timestamp() | on update current_timestamp() |
+-------------+--------------+------+-----+---------------------+-------------------------------+
```

## geoIP
```
+-------------+--------------+------+-----+---------------------+-------------------------------+
| Field       | Type         | Null | Key | Default             | Extra                         |
+-------------+--------------+------+-----+---------------------+-------------------------------+
| id          | int(11)      | NO   | PRI | NULL                | auto_increment                |
| country     | varchar(150) | NO   |     | NULL                |                               |
| ipAddr      | varchar(45)  | NO   |     | NULL                |                               |
| access_date | timestamp    | NO   |     | current_timestamp() | on update current_timestamp() |
+-------------+--------------+------+-----+---------------------+-------------------------------+
```

## users1
```
+----------+--------------+------+-----+---------------------+-------------------------------+
| Field    | Type         | Null | Key | Default             | Extra                         |
+----------+--------------+------+-----+---------------------+-------------------------------+
| id       | int(11)      | NO   | PRI | NULL                | auto_increment                |
| username | varchar(255) | NO   |     | NULL                |                               |
| password | varchar(255) | NO   |     | NULL                |                               |
| date     | timestamp    | NO   |     | current_timestamp() | on update current_timestamp() |
+----------+--------------+------+-----+---------------------+-------------------------------+
```

## cpuP1
```
+---------+-----------+------+-----+---------------------+-------------------------------+
| Field   | Type      | Null | Key | Default             | Extra                         |
+---------+-----------+------+-----+---------------------+-------------------------------+
| id      | int(11)   | NO   | PRI | NULL                | auto_increment                |
| percent | int(11)   | NO   |     | NULL                |                               |
| date    | timestamp | NO   |     | current_timestamp() | on update current_timestamp() |
+---------+-----------+------+-----+---------------------+-------------------------------+
```

## memP1
```
+---------+-----------+------+-----+---------------------+-------------------------------+
| Field   | Type      | Null | Key | Default             | Extra                         |
+---------+-----------+------+-----+---------------------+-------------------------------+
| id      | int(11)   | NO   | PRI | NULL                | auto_increment                |
| percent | int(11)   | NO   |     | NULL                |                               |
| date    | timestamp | NO   |     | current_timestamp() | on update current_timestamp() |
+---------+-----------+------+-----+---------------------+-------------------------------+
```

## diskP1
```
+-------+-----------+------+-----+---------------------+-------------------------------+
| Field | Type      | Null | Key | Default             | Extra                         |
+-------+-----------+------+-----+---------------------+-------------------------------+
| id    | int(11)   | NO   | PRI | NULL                | auto_increment                |
| used  | int(11)   | NO   |     | NULL                |                               |
| free  | int(11)   | NO   |     | NULL                |                               |
| total | int(11)   | NO   |     | NULL                |                               |
| date  | timestamp | NO   |     | current_timestamp() | on update current_timestamp() |
+-------+-----------+------+-----+---------------------+-------------------------------+
```

## downLoadP1
```
+-----------------+-----------+------+-----+---------------------+-------------------------------+
| Field           | Type      | Null | Key | Default             | Extra                         |
+-----------------+-----------+------+-----+---------------------+-------------------------------+
| id              | int(11)   | NO   | PRI | NULL                | auto_increment                |
| downloadCurrent | int(11)   | NO   |     | NULL                |                               |
| downloadMax     | int(11)   | NO   |     | NULL                |                               |
| date            | timestamp | NO   |     | current_timestamp() | on update current_timestamp() |
+-----------------+-----------+------+-----+---------------------+-------------------------------+
```

## downHist
```
+-------+-----------+------+-----+---------------------+-------------------------------+
| Field | Type      | Null | Key | Default             | Extra                         |
+-------+-----------+------+-----+---------------------+-------------------------------+
| id    | int(11)   | NO   | PRI | NULL                | auto_increment                |
| max   | int(11)   | NO   |     | NULL                |                               |
| date  | timestamp | NO   |     | current_timestamp() | on update current_timestamp() |
+-------+-----------+------+-----+---------------------+-------------------------------+
```

## uploadP1
```
+---------------+-----------+------+-----+---------------------+-------------------------------+
| Field         | Type      | Null | Key | Default             | Extra                         |
+---------------+-----------+------+-----+---------------------+-------------------------------+
| id            | int(11)   | NO   | PRI | NULL                | auto_increment                |
| uploadCurrent | int(11)   | NO   |     | NULL                |                               |
| uploadMax     | int(11)   | NO   |     | NULL                |                               |
| date          | timestamp | NO   |     | current_timestamp() | on update current_timestamp() |
+---------------+-----------+------+-----+---------------------+-------------------------------+
```

## upHist
```
+-------+-----------+------+-----+---------------------+-------------------------------+
| Field | Type      | Null | Key | Default             | Extra                         |
+-------+-----------+------+-----+---------------------+-------------------------------+
| id    | int(11)   | NO   | PRI | NULL                | auto_increment                |
| max   | int(11)   | NO   |     | NULL                |                               |
| date  | timestamp | NO   |     | current_timestamp() | on update current_timestamp() |
+-------+-----------+------+-----+---------------------+-------------------------------+
```