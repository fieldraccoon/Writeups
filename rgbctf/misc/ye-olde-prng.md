# ye olde prng

We get that the numbers are generated by squaring the number and taking the middle digits or something?

script below:

```python
n = int(input())
print(str(n**2)[50:-50])
```

## flag: rgbCTF{d0nt\_us3\_midd13\_squ4r3}
