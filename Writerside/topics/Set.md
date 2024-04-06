# Set

- **unordered**
- **unchangeable**
- **not duplicated values**

<tabs>
<tab title="Python">

```Python
my_set = {0, 1, 2, 'some string', True, False, 2}
len(my_set)  # 4
```

</tab>
<tab title="JavaScript">

```Javascript
const mySet = new Set([0, 1, 2, 'some string', true, false, 2]);
mySet.size // 6
```
</tab>
</tabs>

<note>
The values True and 1 are considered the same value in sets, and are treated as duplicates.
</note>

<note>
The values False and 0 are considered the same value in sets, and are treated as duplicates.
</note>

## Access items
<tabs>
<tab title="Python">

```Python
my_set = {0, 1, 2, 'some string', True, False, 2}
for item in my_set:
    print(item)
```

</tab>
<tab title="JavaScript">

```Javascript
const mySet = new Set([0, 1, 2, 'some string', true, false, 2]);
mySet.forEach(function(item){
    console.log(item);
});
```
</tab>
</tabs>


## Add item
<tabs>
<tab title="Python">

```Python
my_set = {0, 1, 2, 'some string', True, False, 2}
my_set.add('new item')
```

</tab>
<tab title="JavaScript">

```Javascript
const mySet = new Set([0, 1, 2, 'some string', true, false, 2]);
mySet.add('new item');
```
</tab>
</tabs>


## Remove item

### remove()
<tabs>
<tab title="Python">

```Python
my_set = {0, 1, 2, 'some string', True, False, 2}
my_set.remove(0)
my_set.remove('new item')  # raise an error
```

</tab>
<tab title="JavaScript">

```Javascript
const mySet = new Set([0, 1, 2, 'some string', true, false, 2]);
mySet.add('new item');
```
</tab>
</tabs>


### discard()
<tabs>
<tab title="Python">

```Python
my_set = {0, 1, 2, 'some string', True, False, 2}
my_set.discard(0)
my_set.discard('new item')  # **not** raise an error
```

</tab>
<tab title="JavaScript">

```Javascript
const mySet = new Set([0, 1, 2, 'some string', true, false, 2]);
mySet.delete(0); // true
mySet.delete('new item'); // fasle
```
</tab>
</tabs>


### clear()
<tabs>
<tab title="Python">

```Python
my_set = {0, 1, 2, 'some string', True, False, 2}
my_set.clear()
```

</tab>
<tab title="JavaScript">

```Javascript
const mySet = new Set([0, 1, 2, 'some string', true, false, 2]);
mySet.clear();
```
</tab>
</tabs>
