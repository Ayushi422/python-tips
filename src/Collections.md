# Collections

## defaultdict
```python
enhanced_dict = default_dict(list)

enhanced_dict['xxx'].append(1) # [1] 
enhanced_dict['xxx'].append(2) # [1,2] 
enhanced_dict['xxx'].append(3) # [1,2,3] 
```
```
print(enhanced_dict['yyy']) # prints []
print(enhanced_dict['xxx']) # [1,2,3]
```

## namedtuple
```python
named1 = namedtuple('Display name', 'item1 item2 item3')

named2 = namedtuple('Display', 'a, b, c')
```

```python
print(named1.item1)
print(named1.item2)
print(named1.item3)

print(named2.a)
# ...
```