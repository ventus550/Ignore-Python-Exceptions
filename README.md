# Ignore-Python-Exceptions
Allows you to swiftly and gracefully ignore any exception with syntactic support of python context managers!

## Usage example
```python
with ignored(KeyError):
  raise KeyError
```

```python
with ignored(KeyError, ValueError):
  ...
```

Now you too can ignore exceptions! :)
