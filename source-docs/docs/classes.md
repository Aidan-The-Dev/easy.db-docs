# .set

Use `.set` to put a value into the database that can be called using the key

```javascript
db.set('key', 'value')
```
-----------------------------------
# .get

Use `.get` to get a value from the database using the key

```javascript
db.get('key')
```

-----------------------------------
# .delete

Use `.delete` to delete a value and a key using the key

```javascript
db.delete('key')
```

-----------------------------------

# .deleteAll

Use `.deleteAll` to completely wipe your database and restore it to brand new

```javascript
db.deleteAll()
```

-----------------------------------

# .fetch

Use `.fetch` to get the a value from the database using the key
(basically .get)

```javascript
db.fetch('key')
```